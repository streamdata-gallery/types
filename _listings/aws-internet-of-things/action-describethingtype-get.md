---
swagger: "2.0"
info:
  title: AWS Internet of Things API Describe Thing Type
  version: 1.0.0
  description: Gets information about the specified thing type.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeThingType:
    get:
      summary: ' Describe Thing Type '
      description: Gets information about the specified thing type
      operationId: describeThingType
      parameters:
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - thing types
definitions: []
x-collection-name: AWS Internet of Things
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