# cloud run
This is the repo created for cloud-run lab final for Security Analytics MSBX 5500.

# Contents
.gitignore, Dockerfile, requirements.txt, docker-compose.yml, main.py, make-request.py, phish-model-1649995335.cloudpickle, .dockerignore, .github

### • a docker-compose command to run Flask container
```bash
docker-compose up
#This command builds my own flask app
```

### • a docker-compose command to execute make-request.py within a running container
```bash
docker-compose exec web python make-request.py
#This command makes requests for the routes
```
