swagger: "2.0"
x-collection-name: WebTRIS
x-complete: 1
info:
  title: ""
  version: 1.0.0
host: webtris.highwaysengland.co.uk
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v{version}/areas:
    get:
      summary: Returns list of areas
      description: Returns list of areas.
      operationId: Areas_Get
      x-api-path-slug: vversionareas-get
      parameters:
      - in: path
        name: version
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Areas
  /v{version}/areas/{area_Ids}:
    get:
      summary: Returns details of selected area
      description: Returns details of selected area.
      operationId: Areas_Get
      x-api-path-slug: vversionareasarea-ids-get
      parameters:
      - in: path
        name: area_Ids
      - in: path
        name: version
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Details
      - Of
      - Selected
      - Area