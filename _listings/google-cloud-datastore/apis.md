---
name: Google Cloud Datastore
x-slug: google-cloud-datastore
description: Cloud Datastore is a highly-scalable NoSQL database for your applications.
  Cloud Datastore automatically handles sharding and replication, providing you with
  a highly available and durable database that scales automatically to handle your
  applications load. Cloud Datastore provides a myriad of capabilities such as ACID
  transactions, SQL-like queries, indexes and much more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
x-kinRank: "9"
x-alexaRank: ""
tags: Google Cloud Datastore
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Datastore API Allocate ID
  x-api-slug: google-cloud-datastore-api
  description: |-
    Allocates IDs for the given keys, which is useful for referencing an entity
    before it is inserted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com////v1/projects/{projectId}:allocateIds
  tags: ID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidallocateids-post-openapi.md
- name: Google Cloud Datastore API Begin New Transaction
  x-api-slug: google-cloud-datastore-api
  description: Begins a new transaction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com////v1/projects/{projectId}:beginTransaction
  tags: Transaction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidbegintransaction-post-openapi.md
- name: Google Cloud Datastore API Commit Transaction
  x-api-slug: google-cloud-datastore-api
  description: |-
    Commits a transaction, optionally creating, deleting or modifying some
    entities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com////v1/projects/{projectId}:commit
  tags: Transaction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidcommit-post-openapi.md
- name: Google Cloud Datastore API Lookup Entity by Key
  x-api-slug: google-cloud-datastore-api
  description: Looks up entities by key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com////v1/projects/{projectId}:lookup
  tags: Lookup
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidlookup-post-openapi.md
- name: Google Cloud Datastore API Rollback Transaction
  x-api-slug: google-cloud-datastore-api
  description: Rolls back a transaction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com////v1/projects/{projectId}:rollback
  tags: Transaction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidrollback-post-openapi.md
- name: Google Cloud Datastore API Queries for Entities
  x-api-slug: google-cloud-datastore-api
  description: Queries for entities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com////v1/projects/{projectId}:runQuery
  tags: Query
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidrunquery-post-openapi.md
- name: Google Cloud Datastore API
  x-api-slug: google-cloud-datastore-api
  description: Cloud Datastore is a highly-scalable NoSQL database for your applications.
    Cloud Datastore automatically handles sharding and replication, providing you
    with a highly available and durable database that scales automatically to handle
    your applications load. Cloud Datastore provides a myriad of capabilities such
    as ACID transactions, SQL-like queries, indexes and much more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Google Cloud Datastore
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/openapi.md
x-common:
- type: x-best-practices
  url: https://cloud.google.com/datastore/docs/best-practices
- type: x-change-log
  url: https://cloud.google.com/datastore/release-notes
- type: x-concepts
  url: https://cloud.google.com/datastore/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/datastore/docs/
- type: x-getting-started
  url: https://cloud.google.com/datastore/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/datastore/docs/how-to
- type: x-issues
  url: https://github.com/GoogleCloudPlatform/google-cloud-datastore/issues
- type: x-pricing
  url: https://cloud.google.com/datastore/pricing
- type: x-service-level-agreement
  url: https://cloud.google.com/datastore/sla
- type: x-support
  url: https://cloud.google.com/datastore/docs/support
- type: x-website
  url: https://cloud.google.com/datastore/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---