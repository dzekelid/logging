swagger: "2.0"
x-collection-name: Backupify
x-complete: 1
info:
  title: Backupify
  description: the-backupify-api-allows-you-to-integrate-the-leading-saas-backup-solution-into-your-software-making-it-easy-to-give-your-customers-the-data-protection-they-need--
  version: 1.0.0
host: api.backupify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/backup_instances/{backup_instance_id}/logs:
    get:
      summary: Returns the logs for a given backup instance
      description: Returns the logs for a given backup instance.
      operationId: getV1BackupInstancesBackupInstanceLogs
      x-api-path-slug: v1backup-instancesbackup-instance-idlogs-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance to pull logs for
      - in: query
        name: date
        description: 'Date (format: YYYY-MM-DD) for which to fetch logs (default:
          today)'
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Logs
  /v1/backup_instances/{backup_instance_id}/logs/{scroll_id}:
    get:
      summary: Returns the logs for a given backup instance
      description: Returns the logs for a given backup instance.
      operationId: getV1BackupInstancesBackupInstanceLogsScroll
      x-api-path-slug: v1backup-instancesbackup-instance-idlogsscroll-id-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance to pull logs for
      - in: path
        name: scroll_id
        description: scroll_id for pagination
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Logs
      - Scroll
      - Id