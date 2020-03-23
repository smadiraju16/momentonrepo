# momentonrepo
Repo for Momenton tech challenge

## Steps to Run:
- Create an EC2 linux instance. Install  Docker, Docker Compose. 
- Download all the artefacts from the GIT repository onto /home/ec2-user
  - https://github.com/smadiraju16/momentonrepo
- Modify VIRTUAL_HOST (docker-compose.yml) and location conifiguration(nginx.conf) to reflect either local hosts (local testing) or external domain names.
 - Note: These scripts can be further automated to take the domain names as parameters.
 - From /home/ec2-user directory run the command “docker-compose up”. Docker compose will build new docker images from the dockerfiles and deploys all necessary containers along with the appropriate dynamic and static content. 


