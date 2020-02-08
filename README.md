
# LOGIN | Research assignment 1
 Dana Marin & Derrik Campbell

## Description
Assignment Goals:

 >Allow user to login to a welcome page.
 >Displays date/time of LAST successful login.
 >Account lockout after 3 failed login attempts.
 >Display 3 different welcome messages based off of time of day.

## Getting Started
 >Clone the repo to your computer
 >Open in your preferred developing application

### Dependencies

Used HTML3, Javascript, PHP. 

### Installing

> Launch MAMP
> Open Localhost:8888/ and the correct path (On Mac)

## Authors

Contributors names 

* Marin, Dana
* Campbell, Derrik 


## Version History

* 0.1
    * Initial Release


## Acknowledgments

Research:


#### PHP Movie Review
This is the Docker environment set up for Movie Review


#### Prerequisites
1. Install `Docker` from [https://docs.docker.com/install/] 
2. IF you are in Linux, install `docker-compose` from [https://docs.docker.com/install/]


#### Set up
1. Clone the repo
   ```
   git clone https://github.com/spiderPan/Fanshawe-IDP-Inclass.git
   ```
2. Open the folder and run docker-compose
   ```
   cd movies_cms
   docker-compose up
   ```
3. When you finished work, you can turn if off by doing 
   ```
   docker-compose down
   ```

#### URLs
1. Your project is up in `http://localhost:8010` which is mapping to the `movies_cms` folder
2. The phpMyAdmin is in `http://localhost:8011` with the credential of 
```
Username: docker_u
Password: docker_p
```