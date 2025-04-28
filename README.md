# api-docs
[Swagger API docs](https://qaecy.github.io/api-docs/index.html)
[Redoc API docs](https://qaecy.github.io/api-docs/redoc-static.html)

# Build and deploy
- Documentation is specified as swagger YAML in [api-docs.yml](./api-docs.yml). Use https://editor-next.swagger.io/ to live edit the file. 
- Redoc needs to be built with `npx @redocly/cli build-docs -o ./redoc-static.html ./api-docs.yml`