createSpecification:
  handler: src/lambdaHandler/lambdaHandler.createSpecificationLambda
  events:
    - http:
        path: specification
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        bodyType: "createSpecificationRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getSpecificationResponse"

updateSpecification:
  handler: src/lambdaHandler/lambdaHandler.updateSpecificationLambda
  events:
    - http:
        path: specification/{id}
        method: PATCH
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        # description: "It will get data from DB"
        bodyType: "createSpecificationRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getSpecificationResponse"

getSpecificationDetails:
  handler: src/lambdaHandler/lambdaHandler.getSpecificationDetailsLambda
  events:
    - http:
        path: specification/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getSpecificationResponse"

getSpecifications:
  handler: src/lambdaHandler/lambdaHandler.getSpecificationsLambda
  events:
    - http:
        path: specifications
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false

getSpecificationByApplication:
  handler: src/lambdaHandler/lambdaHandler.getSpecificationByApplicationLambda
  events:
    - http:
        path: specification/application/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getSpecificationListResponse"

deleteSpecification:
  handler: src/lambdaHandler/lambdaHandler.deleteSpecificationLambda
  events:
    - http:
        path: specification/{id}
        method: DELETE
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getSpecificationResponse"

createEnvSpecification:
  handler: src/lambdaHandler/lambdaHandler.createEnvSpecificationLambda
  events:
    - http:
        path: env-spec
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        bodyType: "createEnvSpecificationRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getEnvSpecificationResponse"

updateEnvSpecification:
  handler: src/lambdaHandler/lambdaHandler.updateEnvSpecificationLambda
  events:
    - http:
        path: env-spec/{id}
        method: PATCH
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        # description: "It will get data from DB"
        bodyType: "createEnvSpecificationRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getEnvSpecificationResponse"

getEnvSpecificationDetails:
  handler: src/lambdaHandler/lambdaHandler.getEnvSpecificationDetailsLambda
  events:
    - http:
        path: env-spec/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getEnvSpecificationResponse"

getEnvSpecificationByApplication:
  handler: src/lambdaHandler/lambdaHandler.getEnvSpecificationByApplicationLambda
  events:
    - http:
        path: env-spec/application/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getEnvSpecificationListResponse"

deleteEnvSpecification:
  handler: src/lambdaHandler/lambdaHandler.deleteEnvSpecificationLambda
  events:
    - http:
        path: env-spec/{id}
        method: DELETE
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getEnvSpecificationResponse"

createCodeSpecification:
  handler: src/lambdaHandler/lambdaHandler.createCodeSpecificationLambda
  events:
    - http:
        path: code-spec
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        bodyType: "createCodeSpecificationRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getCodeSpecificationResponse"

updateCodeSpecification:
  handler: src/lambdaHandler/lambdaHandler.updateCodeSpecificationLambda
  events:
    - http:
        path: code-spec/{id}
        method: PATCH
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        # description: "It will get data from DB"
        bodyType: "createCodeSpecificationRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getCodeSpecificationResponse"

getCodeSpecificationDetails:
  handler: src/lambdaHandler/lambdaHandler.getCodeSpecificationDetailsLambda
  events:
    - http:
        path: code-spec/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getCodeSpecificationResponse"

getRepoBranches:
  handler: src/lambdaHandler/lambdaHandler.getRepoBranchesLambda
  events:
    - http:
        path: code-spec/{id}/branches
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getRepoBranchesResponse"

getCodeSpecificationByApplication:
  handler: src/lambdaHandler/lambdaHandler.getCodeSpecificationByApplicationLambda
  events:
    - http:
        path: code-spec/application/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getCodeSpecificationListResponse"

deleteCodeSpecification:
  handler: src/lambdaHandler/lambdaHandler.deleteCodeSpecificationLambda
  events:
    - http:
        path: code-spec/{id}
        method: DELETE
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getCodeSpecificationResponse"

createTechnicalDesign:
  handler: src/lambdaHandler/lambdaHandler.createTechnicalDesignLambda
  events:
    - http:
        path: tech-design
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        bodyType: "createTechnicalDesignRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getTechnicalDesignResponse"

updateTechnicalDesign:
  handler: src/lambdaHandler/lambdaHandler.updateTechnicalDesignLambda
  events:
    - http:
        path: tech-design/{id}
        method: PATCH
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        request:
          parameters:
            paths:
              id: true
        # description: "It will get data from DB"
        bodyType: "createTechnicalDesignRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getTechnicalDesignResponse"

getTechnicalDesignDetails:
  handler: src/lambdaHandler/lambdaHandler.getTechnicalDesignDetailsLambda
  events:
    - http:
        path: tech-design/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getTechnicalDesignResponse"

getTechnicalDesignByApplication:
  handler: src/lambdaHandler/lambdaHandler.getTechnicalDesignByApplicationLambda
  events:
    - http:
        path: tech-design/application/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getTechnicalDesignListResponse"

getTechnicalDesignByIssue:
  handler: src/lambdaHandler/lambdaHandler.getTechnicalDesignByIssueLambda
  events:
    - http:
        path: tech-design/issue/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getTechnicalDesignListResponse"

deleteTechnicalDesign:
  handler: src/lambdaHandler/lambdaHandler.deleteTechnicalDesignLambda
  events:
    - http:
        path: tech-design/{id}
        method: DELETE
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getTechnicalDesignResponse"

getDbSchemas:
  handler: src/lambdaHandler/lambdaHandler.getDbSchemasLambda
  events:
    - http:
        path: db-schema
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        bodyType: "getDbSchemaRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getDbSchemasResponse"

getGitHubRepos:
  handler: src/lambdaHandler/lambdaHandler.getGitHubReposLambda
  events:
    - http:
        path: git-hub/repos
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # bodyType: "getDbSchemaRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getGitHubReposResponse"

createConfig:
  handler: src/lambdaHandler/lambdaHandler.createConfigLambda
  events:
    - http:
        path: config
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        bodyType: "createConfigRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

updateConfig:
  handler: src/lambdaHandler/lambdaHandler.updateConfigLambda
  events:
    - http:
        path: config/{id}
        method: PATCH
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        request:
          parameters:
            paths:
              id: true
        # description: "It will get data from DB"
        bodyType: "createConfigRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

getConfigDetails:
  handler: src/lambdaHandler/lambdaHandler.getConfigDetailsLambda
  events:
    - http:
        path: config/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

getConfigByCompany:
  handler: src/lambdaHandler/lambdaHandler.getConfigByCompanyLambda
  events:
    - http:
        path: configs
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        # request:
        #   parameters:
        #     paths:
        #       id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigListResponse"

deleteConfig:
  handler: src/lambdaHandler/lambdaHandler.deleteConfigLambda
  events:
    - http:
        path: config/{id}
        method: DELETE
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

getConfigByTypeAndCompany:
  handler: src/lambdaHandler/lambdaHandler.getConfigByTypeAndCompanyLambda

#env-property

createEnvProperties:
  handler: src/lambdaHandler/lambdaHandler.createEnvPropertiesLambda
  events:
    - http:
        path: env-property
        method: POST
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: true
        # description: "It will get data from DB"
        bodyType: "createConfigRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

updateEnvProperty:
  handler: src/lambdaHandler/lambdaHandler.updateEnvPropertyLambda
  events:
    - http:
        path: env-property/{id}
        method: PATCH
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        # description: "It will get data from DB"
        bodyType: "createConfigRequest"
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

getEnvPropertyDetails:
  handler: src/lambdaHandler/lambdaHandler.getEnvPropertyDetailsLambda
  events:
    - http:
        path: env-property/{id}
        method: GET
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        # description: "It will get data from DB"
        # bodyType: "createCommentRequest"
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"

# getConfigByCompany:
#   handler: src/lambdaHandler/lambdaHandler.getConfigByCompanyLambda
#   events:
#     - http:
#         path: configs
#         method: GET
#         cors:
#           origin: "*"
#           headers:
#             - Content-Type
#             - Authorization
#             - X-Api-Key
#             - _X_AMZN_TRACE_ID
#             - trackingId
#             - accesstoken
#         private: true
#         # description: "It will get data from DB"
#         # bodyType: "createCommentRequest"
#         # request:
#         #   parameters:
#         #     paths:
#         #       id: true
#         responseData:
#           200:
#             # description: "Data Get successfully"
#             bodyType: "getConfigListResponse"

deleteEnvProperty:
  handler: src/lambdaHandler/lambdaHandler.deleteEnvPropertyLambda
  events:
    - http:
        path: env-property/{id}
        method: DELETE
        cors:
          origin: "*"
          headers:
            - Content-Type
            - Authorization
            - X-Api-Key
            - _X_AMZN_TRACE_ID
            - trackingId
            - accesstoken
        private: false
        request:
          parameters:
            paths:
              id: true
        responseData:
          200:
            # description: "Data Get successfully"
            bodyType: "getConfigResponse"
