# Rocket2fa

This is the docker-compose yaml file for Rocketchat with 2nd factor authentication which works with LDAP and all other
authenticators. 
Since I couldn't wait for it to be merged with the main project I have just modified it a bit to point to a docker image in my docker
hub, so it works without problems.

USAGE:

docker-compose up


then your local machine will listen on port 3000 TCP and wizard of Rocket Chat will start.
