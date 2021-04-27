# cashify-python-db-secret

Cashify Python Repo to get Database values from AWS Secret manager.

Pre-requisite:
1. Boto3 library


How to use:
- Install library using pip install git+https://git@github.com/saket-cashify/cashify-python-db-secret.git
- Simply import the package and use function "get_secret" with arguments (secret_name, region_name) in try block and "get_secret_fallback" with arguments (secret_name, region_name) in except block to get general secret.
- add this line to requirements.txt file to install "-e git+https://git@github.com/saket-cashify/cashify-python-db-secret.git#egg=cashifypythondbsecret" automatically