---
swagger: "2.0"
x-collection-name: Twine
x-complete: 0
info:
  title: Twine Create a reward program activation
  description: Create a reward program activation for a patient. There can only be
    one activation for a patient for a given reward program.
  version: 7.18.0
host: api.twinehealth.com
basePath: /pub
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reward_program_activation:
    post:
      summary: Create a reward program activation
      description: Create a reward program activation for a patient. There can only
        be one activation for a patient for a given reward program.
      operationId: createRewardProgramActivation
      x-api-path-slug: reward-program-activation-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - Reward
      - Program
      - Activation
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