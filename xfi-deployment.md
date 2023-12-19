# XFI Deployment

## assure-mosaic-innovation-xfi-feature

### Deployment
https://github.dxc.com/assure-delivery/assure-mosaic-innovation-xfi-feature-deploy

### Artifacts
1. xfi-artifacts (https://github.dxc.com/assure-delivery/assure-mosaic-innovation-xfi-artifacts)
1. rds-json-loader-lambda (https://github.dxc.com/assure-delivery/assure-mosaic-innovation-rds-json-loader-lambda)
1. xfi-lambda (https://github.dxc.com/assure-delivery/assure-mosaic-innovation-Postgresql-function-executor-lambda)
1. sm-sql-extension-handler (https://github.dxc.com/assure-delivery/assure-mosaic-innovation-sm-sql-extension-handler)
1. sf-trigger-handler (https://github.dxc.com/assure-delivery/assure-mosaic-innovation-sf-trigger-handler)

### Parameters
| Key | Value |
| --- | ----- |
|service_branch_name| feature/serverlessv2|
|source_email| Mosaic_Innovation_Ops@dxc.com|
|sql_schemas_scripts_string_list||
|sql_stored_procedures_scripts_string_list|03_sql_stored_procedures/ODS_data_functions/,03_sql_stored_procedures/DWHSTG_data_functions/|
|sql_tables_scripts_string_list||
|sql_tables_upgrade_scripts_string_list||
|sql_triggers_scripts_string_list||
|sql_users_scripts_string_list||
|to_email|Mosaic_Innovation_Ops@dxc.com|
