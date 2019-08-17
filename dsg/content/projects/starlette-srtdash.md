---
title: "Starlette SRT Dashboard"
date: 2019-08-10T12:00:00-00:00
description: "A Dshboard template for Starlette"
draft: false
featured_image: "../images/starlette.png"

---
{{< figure src="/images/starlette.png" width="600" alt="Starlette" >}}
# Starlette Admin with SRT Dashboard

This project is to serve as an experiment to learn [starlette](https://starlette.io/) and a basic template for other projects. It is built with the [SRT Dashboard template](https://github.com/puikinsh/srtdash-admin-dashboard).

Currently running at [SRTDash.DevSetGo.com](https://srtdash.devsetgo.com)
{{< figure src="/images/srtdash.PNG" width="600" alt="Starlette" >}}

[ChangeLog](https://github.com/devsetgo/starlette-SRTDashboard/blob/master/CHANGELOG.md)

Would love to have help to build a great example for others to use.

## How to Use
- See project [README.md](https://github.com/devsetgo/starlette-SRTDashboard/blob/master/README.md) for up-to-date documentatione

### Use it
- git clone https://github.com/devsetgo/starlette-SRTDashboard
- create a virtualenv on linux or Windows Subsystem Linux
- Run it
~~~~
UVICORN
    Development: 
        uvicorn main:app --port 5000 --reload
    
    Production:
        uvicorn main:app --workers 2
        gunicorn -c gunicorn_cfg.py main:app
        # Note: gunicorn is the config for the dockerfile

Docker
    Docker: docker pull mikeryan56/srtdash:latest (unreleased)
~~~~

## Issues/Bugs

- [ ] cleanup

## TODO

- [x] Refactor by endpoint (sample, user, etc..)
- [ ] Create tests
- [x] Better organization
    - [ ] Use of Routers/Endpoints (equivalent to Flask Blueprints)
- [ ] Configuration Scripts

- Access Controls
  - [ ] Add Access controls
  - [ ] Signup functionality

- [x] Gunicorn/Uvicorn configuration
- [x] Logging (using [Loguru](https://github.com/Delgan/loguru))
- [ ] Setup CI/CD Pipeline for test and deployment
- [ ] Make [Twelve Factor App](https://12factor.net/) ready
- [ ] Build a [cookiecutter](https://github.com/audreyr/cookiecutter) template for 
- [ ] Add code comments
- [ ] Websocket example

- Docker
  - [x] Docker-Compose
    - [ ] Docker Swarm settings
  - [ ] Kubernetes Kompose

- Tutorials/Documentation
  - [ ] Basic Overview
  - [ ] Explantion of Functions
  - [ ] Explantion of Configuration


  