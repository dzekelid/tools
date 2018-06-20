---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Create an external tool
  description: Create an external tool.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/external_tools:
    get:
      summary: List external tools
      description: List external tools.
      operationId: list-external-tools
      x-api-path-slug: coursescourse-idexternal-tools-get
      parameters:
      - in: query
        name: search_term
        description: The partial name of the tools to match and return
      - in: query
        name: selectable
        description: If true, then only tools that are meant to be selectable are
          returned
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Tools
    post:
      summary: Create an external tool
      description: Create an external tool.
      operationId: create-an-external-tool
      x-api-path-slug: coursescourse-idexternal-tools-post
      parameters:
      - in: query
        name: account_navigation[enabled]
        description: Set this to enable this feature
      - in: query
        name: account_navigation[text]
        description: The text that will show on the left-tab in the account navigation
      - in: query
        name: account_navigation[url]
        description: The url of the external tool for account navigation
      - in: query
        name: config_type
        description: Configuration can be passed in as CC xml instead of using query
          parameters
      - in: query
        name: config_url
        description: URL where the server can retrieve an XML tool configuration,
          as specifiednin the CC xml specification
      - in: query
        name: config_xml
        description: XML tool configuration, as specified in the CC xml specification
      - in: query
        name: consumer_key
        description: The consumer key for the external tool
      - in: query
        name: course_navigation[default]
        description: Whether the navigation option will show in the course by default
          or whethernthe teacher will have to explicitly enable it
      - in: query
        name: course_navigation[enabled]
        description: Set this to enable this feature
      - in: query
        name: course_navigation[text]
        description: The text that will show on the left-tab in the course navigation
      - in: query
        name: course_navigation[url]
        description: The url of the external tool for course navigation
      - in: query
        name: course_navigation[visibility]
        description: Who will see the navigation tab
      - in: query
        name: custom_fields
        description: Custom fields that will be sent to the tool consumer, specified
          as custom_fields
      - in: query
        name: description
        description: A description of the tool
      - in: query
        name: domain
        description: The domain to match links against
      - in: query
        name: editor_button[enabled]
        description: Set this to enable this feature
      - in: query
        name: editor_button[icon_url]
        description: The url of the icon to show in the WYSIWYG editor
      - in: query
        name: editor_button[selection_height]
        description: The height of the dialog the tool is launched in
      - in: query
        name: editor_button[selection_width]
        description: The width of the dialog the tool is launched in
      - in: query
        name: editor_button[url]
        description: The url of the external tool
      - in: query
        name: icon_url
        description: The url of the icon to show for this tool
      - in: query
        name: name
        description: The name of the tool
      - in: query
        name: not_selectable
        description: 'Default: false, if set to true the tool won&#39;t show up in
          the externalntool selection UI in modules and assignments'
      - in: query
        name: privacy_level
        description: What information to send to the external tool
      - in: query
        name: resource_selection[enabled]
        description: Set this to enable this feature
      - in: query
        name: resource_selection[icon_url]
        description: The url of the icon to show in the module external tool list
      - in: query
        name: resource_selection[selection_height]
        description: The height of the dialog the tool is launched in
      - in: query
        name: resource_selection[selection_width]
        description: The width of the dialog the tool is launched in
      - in: query
        name: resource_selection[url]
        description: The url of the external tool
      - in: query
        name: shared_secret
        description: The shared secret with the external tool
      - in: query
        name: text
        description: The default text to show for this tool
      - in: query
        name: url
        description: The url to match links against
      - in: query
        name: user_navigation[enabled]
        description: Set this to enable this feature
      - in: query
        name: user_navigation[text]
        description: The text that will show on the left-tab in the user navigation
      - in: query
        name: user_navigation[url]
        description: The url of the external tool for user navigation
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Tools
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