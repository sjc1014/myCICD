# myCICD
myCICD Groovy Library Repo

Library Has Four Types of Jenkinsfile option:
Default Jenkinfile this basic template
JenkinsfileJavaMaven that builds Pet Store Java app using maven
JenkinsfilejavaMavenSharedLibrary - same function as above but leveragin SL
JenkinsfileJavaMavenSharedLibraryMultibranch - same function as above with multibrnach options

docker run -d --restart=always \
-v /var/run/docker.sock:/var/run/docker.sock \
-p 127.0.0.1:2376:2375 \
--name docker-api-proxy \
alpine/socat \
tcp-listen:2375,fork,reuseaddr unix-connect:/var/run/docker.sock

docker container exec -it jenkins-master curl http://docker.for.mac.localhost:2376/v1.41/info

docker run -d -v jenkins_home:/var/jenkins_home \
-p 8080:8080 \
-p 50000:50000 \
--name jenkins-master jenkins/jenkins:lts-jdk11

docker container logs jenkins-master

