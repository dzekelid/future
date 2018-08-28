swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/gigme/artist/{id}/events/future:
    get:
      summary: Get Gigme Artist Events Future
      description: Get gigme artist events future.
      operationId: getApiV1GigmeArtistEventsFuture
      x-api-path-slug: apiv1gigmeartistideventsfuture-get
      parameters:
      - in: path
        name: id
        description: Id
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Events
      - Future