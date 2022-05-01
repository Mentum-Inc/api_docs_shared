## Making Changes

1. Install VS code and [OpenAPI Linter](https://marketplace.visualstudio.com/items?itemName=mermade.openapi-lint). This extension provides better linting than JetBrains products for OpenAPI files.
2. Make changes in `openapi.yml`

## Previewing Changes Locally

1. Install redoc-cli
   1. `brew update`
   2. `brew install node`
   3. `npm -g redoc-cli`
2. Run server `redoc-cli serve openapi.yml`

## Validating OpenAPI Locally

1. `npm install rdme --save-dev`
2. `npx rdme openapi openapi/openapi.yml`

Note: This repo should remain public as long as its referenced by other OpenAPI files.
