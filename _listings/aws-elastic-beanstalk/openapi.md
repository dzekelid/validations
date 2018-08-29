---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ValidateConfigurationSettings:
    get:
      summary: Validate Configuration Settings
      description: |-
        Takes a set of configuration settings and either a configuration template or
              environment, and determines whether those values are valid.
      operationId: validateConfigurationSettings
      x-api-path-slug: actionvalidateconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application that the configuration template or
          environment belongs      to
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to validate the settings against
        type: string
      - in: query
        name: OptionSettings.member.N
        description: A list of the options and desired values to evaluate
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to validate the settings
          against
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
---