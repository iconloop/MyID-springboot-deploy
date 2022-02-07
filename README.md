# MyID-springboot-deploy



## Prerequisites

Docker & Docker Compose environment

* Install Docker Engine: https://docs.docker.com/engine/install/
* Install Docker Compose: https://docs.docker.com/compose/install/


### Directory Structure

```
.
├── Dockerfile
├── docker-compose.yml
├── logs                      # Create when starting the container 
└── src
    ├── ROOT.jar              # Upload provided source file 
    ├── logrotate-was.tmpl
    └── was-startup.sh
```

## Run
```
$ docker-compose up -d
```

### Rebuild Image
```
$ docker-compose build
```
