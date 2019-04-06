---
title: "Test API"
date: 2019-04-06T12:00:00-00:00
description: "Creating an API with FastAPI"
draft: false
featured_image: "../images/fastapi.png"

---
{{< figure src="/images/fastapi.png" width="600" alt="FastAPI" >}}
# Test API

This project is to server as an experiment to learn [FastApi](https://fastapi.tiangolo.com/) and server as a useful API to serve psuedo data when needed in other projects.

Currently running at [Test-API.DevSetGo.com](https://test-api.devsetgo.com)
- [OpenAPI](https://swagger.io/docs/specification/about/)/Swagger UI @ [Test-API.DevSetGo.com/docs](https://test-api.devsetgo.com/docs)
- [ReDoc](https://redoc.ly/) @ [Test-API.DevSetGo.com/ReDoc](https://test-api.devsetgo.com/redoc)

[ChangeLog](https://github.com/devsetgo/test-api/blob/master/CHANGELOG.md)

Would love to have help to build a great example for others to use.

## How to User
- see project [README.md](https://github.com/devsetgo/test-api/blob/master/README.md)
- More and better documentation to com

## ToDo
- [ ] Create tests
- [ ] Extend API parameters
- [ ] Better organization
- [ ] Standardize API pattern for versioning
- Access Controls
  - [ ] Add Access controls and signup
  - [ ] Add JWT/Token access
  - [ ] Rate limiting
- [ ] Hypercorn configuration
- [ ] Logging
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


## Release Information 
version if calendar versioning year and build number (YY.MM.MICRO) 

![alt text](https://img.shields.io/badge/calver-YY..MM.MICRO-22bfda.svg "Logo Title Text 1")
--------------
### 19.4-beta-1
- First release [19.4-beta-1](https://github.com/devsetgo/test-api/releases/tag/19.4.1-beta)
- Docker image [Test-API](https://cloud.docker.com/u/mikeryan56/repository/docker/mikeryan56/test-api)
- APIs
  - User: Random user information using [Silly](https://github.com/classam/silly)
  - Item: FastAPI example, nothing changed yet.
  - Sample: Can get an single request or a list and add a delay in seconds to the response
  - Using Routers (similar to Flask blueprints)

