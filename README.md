# Ref data api spec OpenAPI Specification
[![Build Status](https://travis-ci.org/TimeZynk/ref-data-api-spec.svg?branch=master)](https://travis-ci.com/TimeZynk/ref-data-api-spec)

## Links

- [Reference Documentation (ReDoc)](https://timezynk.github.io/ref-data-api-spec/)
- [SwaggerUI](https://timezynk.github.io/ref-data-api-spec/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://timezynk.github.io/ref-data-api-spec/openapi.json) [YAML](https://timezynk.github.io/ref-data-api-spec/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
