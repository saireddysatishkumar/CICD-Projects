# CI/CD Wonders
Building seamless pipelines. Learn about continuous integration and continuous deployment with Jenkins, GitLab CI, and GitHub Actions.

## Prerequisites:  
> Setup Jenkins master in local system.  

> Setup Jenkins slave node   
[step1: setup vagrant](https://github.com/saireddysatishkumar/CICD-Projects/tree/main/vagrant)  
[step2: Install java and docker reffering](https://www.jenkins.io/blog/2022/12/27/run-jenkins-agent-as-a-service/)  
[step3: Setup maven](https://medium.com/ci-cd-devops/error-error-executing-maven-error-java-lang-illegalstateexception-unable-to-load-cache-item-39e886a67216)  
[step4:] start docker container and generate a token for jenkins to connect.  
sudo -i  
docker run dti --name sonarqube -p 9000:9000 sonarqube  
step5: Add sonarqube token in jenkins master secrets.  
