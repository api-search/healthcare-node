---
name: Fast Healthcare Interoperability Resources (FHIR)
description: >-
  FHIR is a platform specification that defines a set of capabilities for use
  across the healthcare process, in all jurisdictions, and in lots of different
  contexts. While the basics of the FHIR specification are relatively
  straight-forward (see the Overviews: General, Developers, Clinical, and
  Architects), it can still be difficult to know where to start when
  implementing a solution based on FHIR.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/template.yml
created: 2024-07-11T00:00:00.000Z
modified: 2024-07-11T00:00:00.000Z
specificationVersion: '0.18'
tags:
  - Healthcare
apis:
  - name: Fast Healthcare Interoperability Resources API
    description: >-
      FHIR is a platform specification that defines a set of capabilities for
      use across the healthcare process, in all jurisdictions, and in lots of
      different contexts. While the basics of the FHIR specification are
      relatively straight-forward (see the Overviews: General, Developers,
      Clinical, and Architects), it can still be difficult to know where to
      start when implementing a solution based on FHIR.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://www.hl7.org/fhir/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://www.hl7.org/fhir/
      - type: OpenAPI
        url: properties/fhir-openapi-original.yml
    aid: >-
      fast-healthcare-interoperability-resources-fhir:fast-healthcare-interoperability-resources-api
common:
  - type: Property
    url: https://example.com
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
aid: fast-healthcare-interoperability-resources-fhir
---