# Docker Color Logo
This is a version of the standard docker logo (ascii art) that is modified to use some coloring. Current colors are temporary, as I will try to move them more to the colors of the real Docker logo. I use this logo in my MOTD for system deployments.

![Example Logo](https://raw.githubusercontent.com/jmhardison/dockercolorlogo/master/DockerLogo.png)

## Installation
  - sudo wget "https://raw.github.com/jmhardison/dockercolorlogo/master/01-docker" -O /etc/update-motd.d/01-docker
  - sudo chmod +x /etc/update-motd.d/01-docker
  - sudo chown root:root /etc/update-motd.d/01-docker
