## Github Action to Convert from Collection to OpenAPI Specs

### Steps to reproduce
1. get the Share link of a Postman collection, which contains an API key
2. in github action, replace the plain-text API key with a github secret
3. enable github action write access in repo settings, so that the github action user can write to the repo
