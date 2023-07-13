# CI/CD pipeline with Jenkins and Docker

Feature:
- Application: FastAPI and Traefik config https
- Pytest
- Dockerfile local
- logfile:
  
## FastAPI

- Create python venv
- Write a simple fastapi app
- Add tests for app
  
## Dockerfile

- Write dockerfile to create docker image for app in local
- Add traefik config for dockerfile  

10/07/2023:
Do:
- Add logfile for Traefik
- Add Makefile to automatic buid, up, down, show_log for app (traefik + Fastapi)
- Retrieve README that delete in last commit. [How to retrieve deleted file in git](https://stackoverflow.com/questions/953481/how-do-i-find-and-restore-a-deleted-file-in-a-git-repository)
  
Next: 
- Jenkinsfile to make stage



# Reference:
1. [traefik-examples](https://github.com/JensKnipper/traefik-examples)
2. [traefik-v2-https-ssl-localhost](https://github.com/Heziode/traefik-v2-https-ssl-localhost.git)
3. [Jenkinsfile template for Fastapi](https://github.com/kaisbettaieb/fastapi-examle/blob/main/Jenkinsfile)