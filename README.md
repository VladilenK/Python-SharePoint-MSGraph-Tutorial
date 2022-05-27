# How to run the completed project

This project is based on Microsoft ["Build Python Django apps with Microsoft Graph"](https://docs.microsoft.com/en-us/graph/tutorials/python) tutorial.

## Prerequisites

To run the completed project in this folder, you need the following:

- [Follow original project instructions](https://github.com/microsoftgraph/msgraph-training-pythondjangoapp) **but see below **

except:

1. While registering and configuring app - Set **Supported account types** to **This tenant only**.
2. While registering and configuring app - add 'sites.read.all' Graph API permissions
3. While editing the `oauth_settings.yml` file - Replace `common` with the tenant `contoso.onmicrosoft.com`
4. While editing the `oauth_settings.yml` file - add 'sites.read.all' to a list of scopes
