# Readme

Here is your nice new github repository, please replace this with useful information about what this repository does.

You can find information below if your creating an:

- [backend service](#backend)
- [frontend service](#frontend)
- [npm package](#creating-an-npm-package)


## Installation

// Installation instructions

## Local Development

// Local development instructions

## Deployment Checklist

### Secrets

- Environment variables
  - Ensure you have copied across and set all environment variables for each environment?
  - Ensured you've not added any passwords, private keys, secrets or otherwise sensitive information to this repository?
- Logging
  - Log out important information and consider using various log levels so dev/staging/production output relevant information.
  - Ensure any sensitive information is not being logged out into production.


### Frontend

- Informing IS to ensure a DNS entry has been added so it is accessible on corporate wifi
  - On eurostar's corporate wifi, any new subdomains/frontend applications (e.g. app-name.eurostar.com, app-name-staging.eurostar.com) need to be added to our internal DNS, you should let #devops know.
- Add health endpoint
  - Your application should return a 200 when calling `/health`


## Creating an NPM package

If you are creating an NPM package, you should ensure that you follow the naming convention, add the correct license, repository and set the *private publish registry*, like the following:

```json
{
  ...
  "name": "package-name",
  "repository": "",
  "license": "UNLICENSED",
  "publishConfig": {
    "registry": ""
  }
  ...
}
```
