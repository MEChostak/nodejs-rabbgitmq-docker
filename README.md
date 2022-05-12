# nodejs-rabbgitmq-docker
example queue with nodeJs, rabbit and docker


Following this tutorial it is possible to see the creation process in detail;

https://geshan.com.np/blog/2021/07/rabbitmq-docker-nodejs/

steps:

clone -> docker-compose up -> docker-compose exec consumer /bin/bash -c 'for ((i=1;i<=15;i++)); do node publisher.js; done'

to check

localhost:15673 -> user guest -> password guest

;)
