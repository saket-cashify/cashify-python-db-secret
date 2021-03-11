# cashify-python-db-secret

Cashify Python Repo to get Database values from AWS Secret manager.

Pre-requisite:
1. Boto3 library


How to use:
- Simply import the package and use function "get_secret" with arguments (secret_name, region_name) in try block and "get_secret_fallback" with arguments (secret_name, region_name) in except block to get general secret.
