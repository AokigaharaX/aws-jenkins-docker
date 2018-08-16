# aws-jenkins-docker
based on jenkins:lts

install aws-cli(pip)/docker-ce/vi(m)/groff

docker group id to 497, jenkins to docker group

rename /etc/init.d/docker to docker_bak

mount /var/run/docker.sock if running in DooD mode
