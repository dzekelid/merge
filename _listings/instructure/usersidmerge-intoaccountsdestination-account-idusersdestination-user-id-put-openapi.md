---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Merge user into another user
  description: Merge user into another user.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/merge_into/accounts/destination_account_id/users/{destination_user_id}:
    put:
      summary: Merge user into another user
      description: Merge user into another user.
      operationId: merge-user-into-another-user
      x-api-path-slug: usersidmerge-intoaccountsdestination-account-idusersdestination-user-id-put
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
      - Merge
      - Into
      - Accounts
      - Destination
      - Account
      - Id
      - Users
      - Destination
      - User
      - Id
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