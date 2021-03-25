# JENNKINS

## Install and access
1. Start the jennkins container: docker-compose up -d
2. Get the initial admin password: docker exec jennkins cat /var/jenkins_home/secrets/initialAdminPassword
3. Confirm the jennkins container is running: docker ps

# Configure
1. Install common plugins
2. Configure user 

```
User: jsantos
Password: jennkins
Email: jsantos@tse.org.gt
```

## References
* [How to Run Jenkins in Docker using Docker Compose with Volumes](https://adamtheautomator.com/jenkins-docker/)
* [Curso Jenkins - 02 - Integrar en jenkins un proyecto github](https://www.youtube.com/watch?v=1jNXEWTBgDo)