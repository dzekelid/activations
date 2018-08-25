---
swagger: "2.0"
x-collection-name: Twine
x-complete: 0
info:
  title: Twine List reward program activations
  description: Get a list of reward program activations matching the specified filters.
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
    get:
      summary: List reward program activations
      description: Get a list of reward program activations matching the specified
        filters.
      operationId: fetchRewardProgramActivations
      x-api-path-slug: reward-program-activation-get
      parameters:
      - in: query
        name: filter[patient]
        description: Patient identifier
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - List
      - Reward
      - Program
      - Activations
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