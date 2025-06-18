# CI/CD with Jenkins + Ansible

## Tools Used
- Jenkins
- Maven
- Ansible
- GitHub
- Tomcat
- AWS EC2

## Pipeline Flow
1. Jenkins pulls code from GitHub
2. Maven builds WAR
3. Jenkins triggers Ansible
4. Ansible copies WAR & restarts Tomcat
5. Java app deployed
