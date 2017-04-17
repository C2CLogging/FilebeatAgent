# FilebeatAgent
This Git repository is to maintain the content os different products that use C2C Logging Filebeat Agent.

Guideline for Product teams:
- In the GIT repository the folder name of the product which contains its contents should be its equivalent dashboard name.
- All the logtypes of the product should have their independent/individual template files.
- The name of these template files should be the name of the logtype.
  Eg. The template file for twas logtype twas_accesslog should be named as twas_accesslog.template.
- It is recommended to have prospectors and processors in the template files uncommented. If they are commented, they will  appear in the same manner in the yml file.
