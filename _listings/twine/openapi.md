---
swagger: "2.0"
x-collection-name: Twine
x-complete: 1
info:
  title: Twine
  description: -overviewthe-twine-health-api-is-restful-api--the-requests-and-responses-are-formated-according-to-the-json-apihttpjsonapi-orgformat1-0-specification-in-addition-to-this-documentation-we-also-provide-an-openapihttpsgithub-comoaiopenapispecificationblobmasterversions2-0-md-yaml-file-describing-the-api-twine-api-specificationswagger-yaml--authenticationauthentication-for-the-twine-api-is-based-on-the-oauth-2-0-authorization-frameworkhttpstools-ietf-orghtmlrfc6749--twine-currently-supports-grant-types-of-client-credentials-and-refresh-token-see-post-oauthtokenoperationcreatetoken-for-details-on-the-request-and-response-formats--redocinject-securitydefinitions-
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
  /reward_program_activation/{id}:
    get:
      summary: Get a reward program activation
      description: Get a reward program activationrecord by id.
      operationId: fetchRewardProgramActivation
      x-api-path-slug: reward-program-activationid-get
      parameters:
      - in: path
        name: id
        description: Reward program activation identifier
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - Reward
      - Program
      - Activation
---