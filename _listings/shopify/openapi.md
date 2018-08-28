swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/blogs.json:
    get:
      summary: Get a list of all blogs
      description: Get a list of all blogs.
      operationId: getAdminBlogs.json
      x-api-path-slug: adminblogs-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Blogs
    post:
      summary: Create a new blog
      description: Create a new blog.
      operationId: postAdminBlogs.json
      x-api-path-slug: adminblogs-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Blog
  /admin/blogs/62581763.json:
    get:
      summary: Get a single blog by its ID
      description: Get a single blog by its id.
      operationId: getAdminBlogs62581763.json
      x-api-path-slug: adminblogs62581763-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Blog
      - By
      - Its
      - ID
  /admin/blogs/62581763/articles.json:
    get:
      summary: Get a list of all articles from a certain blog
      description: Get a list of all articles from a certain blog.
      operationId: getAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Articles
      - From
      - Certain
      - Blog
    post:
      summary: Create a new article for a blog
      description: Create a new article for a blog.
      operationId: postAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Articlea
      - Blog
  /admin/blogs/62581763/articles/196805774.json:
    get:
      summary: Get a single article by its ID and the ID of the parent blog
      description: Get a single article by its id and the id of the parent blog.
      operationId: getAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Article
      - By
      - Its
      - ID
      - ID
      - Parent
      - Blog
    put:
      summary: Update an article
      description: Update an article.
      operationId: putAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Article
  /admin/blogs/62581763/articles/197247246.json:
    delete:
      summary: Delete an article of a blog tags of articles
      description: Delete an article of a blog tags of articles.
      operationId: deleteAdminBlogs62581763Articles197247246.json
      x-api-path-slug: adminblogs62581763articles197247246-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Article
      - Blog
      - Tags
      - Articles
  /admin/blogs/62581763/articles/count.json:
    get:
      summary: Get a count of all articles from a certain blog
      description: Get a count of all articles from a certain blog.
      operationId: getAdminBlogs62581763ArticlesCount.json
      x-api-path-slug: adminblogs62581763articlescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Articles
      - From
      - Certain
      - Blog
  /admin/blogs/92408974.json:
    put:
      summary: Update a blog
      description: Update a blog.
      operationId: putAdminBlogs92408974.json
      x-api-path-slug: adminblogs92408974-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Blog
    delete:
      summary: Delete a blog
      description: Delete a blog.
      operationId: deleteAdminBlogs92408974.json
      x-api-path-slug: adminblogs92408974-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Blog
  /admin/blogs/count.json:
    get:
      summary: Get a count of all blogs
      description: Get a count of all blogs.
      operationId: getAdminBlogsCount.json
      x-api-path-slug: adminblogscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Blogs