This repository has a Dockerfile for SaltStack master and the dependencies for junos syslog engine.  
At each git push, the Docker Hub pull down this repository and build a docker image using the Dockerfile and push it onto the Docker Hub.  
To download the Docker image from the Docker registry, use this command:
```
docker pull ksator/saltstack_master_junos_syslog_engine_docker
```

