# Fender Digital Platform Engineering Challenge - EKWONG

## Description

Design and implement a RESTful web service to facilitate a user authentication system. The authentication mechanism should be *token based*. Requests and responses should be in **JSON**.

## Requirements

**Install Docker**: 
Windows: https://docs.docker.com/docker-for-windows/install/
Mac: https://docs.docker.com/docker-for-mac/install/
Linux: https://docs.docker.com/engine/install/ , click on Installations per distro

**Environment Variables**:
* Required environment variables :
    *  PGPASS - password used for database
    * PGTEST - boolean, set to true when running test.

* Setting environment variables:
    * Windows: http://www.dowdandassociates.com/blog/content/howto-set-an-environment-variable-in-windows-command-line-and-registry/
    * Mac: https://www.dowdandassociates.com/blog/content/howto-set-an-environment-variable-in-mac-os-x-terminal-only/
    * Linux: https://linuxize.com/post/how-to-set-and-list-environment-variables-in-linux/
* example : export PGPASS=password 
* verify environment variables:
    * echo $PGPASS should display the password set. 
 **Start/Stop database**:
* start: npm run startdb
* stop: npm run stopdb


