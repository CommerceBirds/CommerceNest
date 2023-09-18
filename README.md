# What's this:
This is the backend system for CommerceNest System  

#How to use:
## Notice: Make sure that the permission of ./etc/mysql/my.cnf is 0444
`chmod 0444 my.cnf`
### Precondition:  
Install docker and docker-compose by yourself.  

## Optional for local devlopment
If you want to use different backend drupal image, copy .env.example to .env and set COMMERCENEST_IMAGE_TAG  
On local development, you can use image  "lawxen/drupal:d10-php82-dev" which contain xdebug  

### Start the docker daemon:
1. Run `docker-compose up -d`
