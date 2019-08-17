---
title: "Test API"
date: 2019-04-20T12:00:00-00:00
description: "Creating an API with FastAPI"
draft: false
featured_image: "../images/fastapi.png"

---
{{< figure src="/images/fastapi.png" width="600" alt="FastAPI" >}}
# Test API

This project is to serve as an experiment to learn [FastApi](https://fastapi.tiangolo.com/) and serve as a useful API to serve psuedo data when needed in other projects.

Currently running at [Test-API.DevSetGo.com](https://test-api.devsetgo.com)
- [OpenAPI](https://swagger.io/docs/specification/about/)/Swagger UI @ [Test-API.DevSetGo.com/docs](https://test-api.devsetgo.com/docs)
- [ReDoc](https://redoc.ly/) @ [Test-API.DevSetGo.com/ReDoc](https://test-api.devsetgo.com/redoc)

[ChangeLog](https://github.com/devsetgo/test-api/blob/master/CHANGELOG.md)

Would love to have help to build a great example for others to use.

## How to Use
- See project [README.md](https://github.com/devsetgo/test-api/blob/master/README.md)
- More and better documentation to come

## TODO

- [x] Refactor by endpoint (ToDo, User, etc..)
- [ ] Create tests
- [ ] Extend API parameters
- [x] Better organization
- [ ] Standardize API pattern for versioning
- Access Controls
  - [ ] Add Access controls and signup
  - [ ] Add JWT/Token access
  - [ ] Rate limiting
- [ ] Hypercorn configuration from file/Yaml (similar to gunicorn?)
- [x] Logging (using [Loguru](https://github.com/Delgan/loguru))
- [ ] Setup CI/CD Pipeline for test and deployment
- [ ] Make [Twelve Factor App](https://12factor.net/) ready
- [ ] Build a [cookiecutter](https://github.com/audreyr/cookiecutter) template for future projects similar to the [FastAPI example](https://github.com/tiangolo/full-stack-fastapi-postgresql)
- [ ] Add code comments
- Docker
  - [ ] Docker Stack example
  - [ ] Docker Swarm example
  - [ ] Kubernetes example
- Tutorials/Documentation
  - [ ] Basic Overview
  - [ ] Explantion of functions

## [Unreleased]
- websockets (working on it)


## [19.2-beta-1] - 2019-04-20
### Added
- routers for todo, users, and silly
- .env file update
- Logging via Loguru

### Changed
- Refactor application
- Changed list to database (SQLite or Postgres)

### Removed
- a lot... due to refactoring
- Removed list for todos
- Some of the Silly endpoints to limit to just list or one user generation

## [19.1-beta-1] - 2019-04-06
### Added
- initial commit
- building base frame of project
  - 'User' random data (extension of FastAPI example)
    - Random user contact information
  - 'Item' little change from FastAPI example
  - 'Sample' Generates randomized data
    - can set a delay in seconds (0 -10) as a parameter 
    - list can generate from 1 to 1000 

### Changed
- Nothing, since it is an initial commit

### Removed
- Nothing, since it is an initial commit

