swagger: "2.0"
x-collection-name: Elastic Email
x-complete: 1
info:
  title: Elastic Email SMTP API
  description: api-for-sending-and-management-email-
  version: v1
host: api.elasticemail.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  mailer/status/log:
    get:
      summary: Log Activity
      description: The detailed activity log api allows you to get detailed information
        from your activity log on the emails that you have sent. Information can be
        narrowed by email status, channel and datetime.
      operationId: getMailerStatusLog
      x-api-path-slug: mailerstatuslog-get
      parameters:
      - in: query
        name: api_key
        description: Your API Key
      - in: query
        name: channel
        description: If you included a channel name when submitting your requests
          you can filter here
      - in: query
        name: compress
        description: True if you want the results returned as a compressed zip file
      - in: query
        name: format
        description: xml or csv
      - in: query
        name: from
        description: 'Server time in the format: 5/19/2011 10:54:20 PM'
      - in: query
        name: status
        description: 'One of the following status values: 0 or all, 1 for ReadyToSend,
          2 for InProgress, 4 for Bounced, 5 for Sent, 6 for Opened, 7 for Clicked,
          8 for Unsubscribed, 9 for Abuse Report'
      - in: query
        name: to
        description: 'Server time in the format: 5/19/2011 10:54:20 PM'
      - in: query
        name: username
        description: Your user name
      responses:
        200:
          description: OK
      tags:
      - Mailer
      - Status
      - Log