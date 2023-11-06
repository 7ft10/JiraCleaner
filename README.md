# JiraCleaner

The jupyter notebooks can be run in VS Code or Google Colab - and potentially any other jupyter engine (but these are the ones that I have tested in).

## Secrets

Secrets are stored need to be stored within a .env file with the following format

SECRETS_HOST = "<https://your-company.atlassian.net/>"
SECRETS_USERNAME = "<you@your-company.com.au>"
SECRETS_PASSWORD = "ATATT........75"

For cloud based jira instances the username must be a email and the password is an api key. To generate an api key visit <https://id.atlassian.com/manage-profile/security/api-tokens>.

For server based jira the username is the login user name and the password is the login password.

If using Google Colab a prompt is presented to allow for a .env file to be uploaded,  saved and renamed to the correct file.
