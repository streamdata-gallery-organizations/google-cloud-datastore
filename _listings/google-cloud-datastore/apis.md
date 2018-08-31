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
x-alexaRank: "0"
tags: Google Cloud Datastore
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Datastore - Allocate ID
  x-api-slug: v1projectsprojectidallocateids-post
  description: |-
    Allocates IDs for the given keys, which is useful for referencing an entity
    before it is inserted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Data, Google APIs, Stack Network, API Service Provider, API Provider, Databases,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidallocateids-post-openapi.md
- name: Google Cloud Datastore - Begin New Transaction
  x-api-slug: v1projectsprojectidbegintransaction-post
  description: Begins a new transaction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Data, Google APIs, Stack Network, API Service Provider, API Provider, Databases,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidbegintransaction-post-openapi.md
- name: Google Cloud Datastore - Commit Transaction
  x-api-slug: v1projectsprojectidcommit-post
  description: |-
    Commits a transaction, optionally creating, deleting or modifying some
    entities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Data, Google APIs, Stack Network, API Service Provider, API Provider, Databases,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidcommit-post-openapi.md
- name: Google Cloud Datastore - Lookup Entity by Key
  x-api-slug: v1projectsprojectidlookup-post
  description: Looks up entities by key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Data, Google APIs, Stack Network, API Service Provider, API Provider, Databases,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidlookup-post-openapi.md
- name: Google Cloud Datastore - Rollback Transaction
  x-api-slug: v1projectsprojectidrollback-post
  description: Rolls back a transaction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Data, Google APIs, Stack Network, API Service Provider, API Provider, Databases,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidrollback-post-openapi.md
- name: Google Cloud Datastore - Queries for Entities
  x-api-slug: v1projectsprojectidrunquery-post
  description: Queries for entities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nosql-tree.png
  humanURL: https://cloud.google.com/datastore/
  baseURL: ://datastore.googleapis.com//
  tags: Data, Google APIs, Stack Network, API Service Provider, API Provider, Databases,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-datastore/master/_listings/google-cloud-datastore/v1projectsprojectidrunquery-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.dataproc.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.datastore.stack.network
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