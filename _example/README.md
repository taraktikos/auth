# go-pkgz/auth example

## build and try

- build with provided compose file - `docker-compose build`
- start the example - `docker-compose up`
- open route: http://127.0.0.1:8080/open
- web application - http://127.0.0.1:8080/web

## parameters

No command line parameters needed. To enable github provider define two env variables:

- `AEXMPL_GITHUB_CID` - github client id
- `AEXMPL_GITHUB_CSEC` - github client secret

_see https://github.com/go-pkgz/auth#github-auth-provider_