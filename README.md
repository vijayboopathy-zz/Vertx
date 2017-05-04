# Continuous Integration with Vert.x Application

## Install and configure jenkins

```
docker run -idt --name jenkins  -v /var/run/docker.sock:/var/run/docker.sock  -p 8080:8080 -p 50000:50000 schoolofdevops/jenkins-2.19.4-alpine
```

## List of Plug-ins need to be installed

* Maven Integration
* Artifactory
* SonarQube
* Deploy to Container
* Git
