---
name: Google API Discovery Service
x-slug: google-api-discovery-service
description: You can use the Google API Discovery Service to build client libraries,
  IDE plugins, and other tools that interact with Google APIs. It provides a lightweight,
  JSON-based API that exposes machine-readable metadata about Google APIs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2017-03-16 at 9.06.47 PM.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google API Discovery Service
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-api-discovery-service/master/_listings/google-api-discovery-service/apis.md
specificationVersion: "0.14"
apis:
- name: Google API Discovery Service API Get APIs
  x-api-slug: google-api-discovery-service-api
  description: Retrieve the list of APIs supported at this endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 9.06.47 PM.png
  humanURL: https://developers.google.com/discovery/
  baseURL: ://www.googleapis.com//discovery/v1//apis
  tags: API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-api-discovery-service/master/_listings/google-api-discovery-service/apis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-api-discovery-service/master/_listings/google-api-discovery-service/apis-get-openapi.md
- name: Google API Discovery Service API Get API Description
  x-api-slug: google-api-discovery-service-api
  description: Retrieve the description of a particular version of an api.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 9.06.47 PM.png
  humanURL: https://developers.google.com/discovery/
  baseURL: ://www.googleapis.com//discovery/v1//apis/{api}/{version}/rest
  tags: API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-api-discovery-service/master/_listings/google-api-discovery-service/apisapiversionrest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-api-discovery-service/master/_listings/google-api-discovery-service/apisapiversionrest-get-openapi.md
- name: Google API Discovery Service API
  x-api-slug: google-api-discovery-service-api
  description: You can use the Google API Discovery Service to build client libraries,
    IDE plugins, and other tools that interact with Google APIs. It provides a lightweight,
    JSON-based API that exposes machine-readable metadata about Google APIs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 9.06.47 PM.png
  humanURL: https://developers.google.com/discovery/
  baseURL: ://www.googleapis.com//discovery/v1
  tags: Google API Discovery Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-api-discovery-service/master/_listings/google-api-discovery-service/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/discovery/v1/using#discovery-doc-auth
- type: x-code
  url: https://developers.google.com/discovery/libraries
- type: x-getting-started
  url: https://developers.google.com/discovery/v1/getting_started
- type: x-performance
  url: https://developers.google.com/discovery/v1/performance
- type: x-website
  url: https://developers.google.com/discovery/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---