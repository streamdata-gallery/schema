---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Assets Create or update the JSON Schema of the specified entity type
  description: Create or update the json schema of the specified entity type.
  version: 1.0.0
host: predix-apphub-arcs-prod.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/system/schema/entities/{type}:
    get:
      summary: Get the JSON Schema of the specified entity type
      description: Get the json schema of the specified entity type.
      operationId: getV1SystemSchemaEntitiesType
      x-api-path-slug: v1systemschemaentitiestype-get
      parameters:
      - in: path
        name: type
        description: Entity type (e
      responses:
        200:
          description: Successful response
      tags:
      - JSON
      - Schema
      - Of
      - Specified
      - Entity
      - Type
    put:
      summary: Create or update the JSON Schema of the specified entity type
      description: Create or update the json schema of the specified entity type.
      operationId: putV1SystemSchemaEntitiesType
      x-api-path-slug: v1systemschemaentitiestype-put
      parameters:
      - in: body
        name: body
        description: JSON Schema for the specified entity type
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: type
        description: Entity type (e
      responses:
        200:
          description: Successful response
      tags:
      - Update
      - JSON
      - Schema
      - Of
      - Specified
      - Entity
      - Type
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---