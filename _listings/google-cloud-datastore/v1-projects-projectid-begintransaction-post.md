---
swagger: "2.0"
info:
  title: Google Cloud Datastore
  description: Accesses the schemaless NoSQL database to provide fully managed, robust,
    scalable storage for your application.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: datastore.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/projects/{projectId}:beginTransaction:
    post:
      summary: Begin New Transaction
      description: Begins a new transaction
      operationId: datastore.projects.beginTransaction
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: projectId
        description: The ID of the project against which to make the request
      responses:
        200:
          description: OK
      tags:
      - transaction
definitions:
  AllocateIdsRequest:
    properties:
      keys:
        description: This is a default description.
        type: post
  AllocateIdsResponse:
    properties:
      keys:
        description: This is a default description.
        type: post
  ArrayValue:
    properties:
      values:
        description: This is a default description.
        type: post
  BeginTransactionRequest:
    properties: []
  BeginTransactionResponse:
    properties:
      transaction:
        description: This is a default description.
        type: post
  CommitRequest:
    properties:
      mode:
        description: This is a default description.
        type: post
      mutations:
        description: This is a default description.
        type: post
      transaction:
        description: This is a default description.
        type: post
  CommitResponse:
    properties:
      indexUpdates:
        description: This is a default description.
        type: post
      mutationResults:
        description: This is a default description.
        type: post
  CompositeFilter:
    properties:
      filters:
        description: This is a default description.
        type: post
      op:
        description: This is a default description.
        type: post
  Entity:
    properties:
      properties:
        description: This is a default description.
        type: post
  EntityResult:
    properties:
      cursor:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  Filter:
    properties: []
  GqlQuery:
    properties:
      allowLiterals:
        description: This is a default description.
        type: post
      namedBindings:
        description: This is a default description.
        type: post
      positionalBindings:
        description: This is a default description.
        type: post
      queryString:
        description: This is a default description.
        type: post
  GqlQueryParameter:
    properties:
      cursor:
        description: This is a default description.
        type: post
  Key:
    properties:
      path:
        description: This is a default description.
        type: post
  KindExpression:
    properties:
      name:
        description: This is a default description.
        type: post
  LatLng:
    properties:
      latitude:
        description: This is a default description.
        type: post
      longitude:
        description: This is a default description.
        type: post
  LookupRequest:
    properties:
      keys:
        description: This is a default description.
        type: post
  LookupResponse:
    properties:
      deferred:
        description: This is a default description.
        type: post
      found:
        description: This is a default description.
        type: post
      missing:
        description: This is a default description.
        type: post
  Mutation:
    properties:
      baseVersion:
        description: This is a default description.
        type: post
  MutationResult:
    properties:
      conflictDetected:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PartitionId:
    properties:
      namespaceId:
        description: This is a default description.
        type: post
      projectId:
        description: This is a default description.
        type: post
  PathElement:
    properties:
      id:
        description: This is a default description.
        type: post
      kind:
        description: This is a default description.
        type: post
      name:
        description: This is a default description.
        type: post
  Projection:
    properties: []
  PropertyFilter:
    properties:
      op:
        description: This is a default description.
        type: post
  PropertyOrder:
    properties:
      direction:
        description: This is a default description.
        type: post
  PropertyReference:
    properties:
      name:
        description: This is a default description.
        type: post
  Query:
    properties:
      distinctOn:
        description: This is a default description.
        type: post
      endCursor:
        description: This is a default description.
        type: post
      kind:
        description: This is a default description.
        type: post
      limit:
        description: This is a default description.
        type: post
      offset:
        description: This is a default description.
        type: post
      order:
        description: This is a default description.
        type: post
      projection:
        description: This is a default description.
        type: post
      startCursor:
        description: This is a default description.
        type: post
  QueryResultBatch:
    properties:
      endCursor:
        description: This is a default description.
        type: post
      entityResultType:
        description: This is a default description.
        type: post
      entityResults:
        description: This is a default description.
        type: post
      moreResults:
        description: This is a default description.
        type: post
      skippedCursor:
        description: This is a default description.
        type: post
      skippedResults:
        description: This is a default description.
        type: post
      snapshotVersion:
        description: This is a default description.
        type: post
  ReadOptions:
    properties:
      readConsistency:
        description: This is a default description.
        type: post
      transaction:
        description: This is a default description.
        type: post
  RollbackRequest:
    properties:
      transaction:
        description: This is a default description.
        type: post
  RollbackResponse:
    properties: []
  RunQueryRequest:
    properties: []
  RunQueryResponse:
    properties: []
  Value:
    properties:
      blobValue:
        description: This is a default description.
        type: post
      booleanValue:
        description: This is a default description.
        type: post
      doubleValue:
        description: This is a default description.
        type: post
      excludeFromIndexes:
        description: This is a default description.
        type: post
      integerValue:
        description: This is a default description.
        type: post
      meaning:
        description: This is a default description.
        type: post
      nullValue:
        description: This is a default description.
        type: post
      stringValue:
        description: This is a default description.
        type: post
      timestampValue:
        description: This is a default description.
        type: post
x-collection-name: Google Cloud Datastore
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