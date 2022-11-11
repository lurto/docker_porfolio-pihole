
# My web profolio and Pihole docker

This repo contains a web page at port 80 with my web profolio. On port 53 is my private dns sponsored by Pi-Hole™. On port 8080 is the admin panel for Pi-Hole™.
The offical version can be found on http://luceiss.com


## Must know 
You have to change the password for the admin panel in the docker-compose.yml file. It is the variable named "WEBPASSWORD".

For the web page, I had **great** inspiration from these sites [Neumorphism Social Share Button by Yuhomyan](https://codepen.io/yuhomyan/pen/abdRKrM?editors=1100) and [Neumorphic form by Pratham ](https://codepen.io/prathkum/pen/OJRvVzY), so kudos to them.




## install

Install the services with Docker compose

```bash
  docker compose up -d
```
    
