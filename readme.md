# Learning Jenkins


### 1. Run Jenkins Docker Command
```
docker run -d --rm --name jenkins -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```

### 2. Open Jenkins admin password
```
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

### 3. Then open localhost:8080
### 4. Put your admin password here
### 5. Set all your plugins and credential here

