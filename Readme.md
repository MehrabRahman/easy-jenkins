# Easy Jenkins
Programmatic configuration of Jenkins CI with Docker

# Build
>docker build -t easy-jenkins .

# Run
>docker run -it -p 8080:8080 easy-jenkins

# Usage
Open http://localhost:8080 in a browser and login with admin/admin. Create Pipeline job with Jenkinsfile groovy script.