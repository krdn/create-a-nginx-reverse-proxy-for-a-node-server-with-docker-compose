## Create a Nginx Reverse Proxy for a Node Server with Docker Compose


https://www.youtube.com/watch?v=U60MdJeov_0


https://wittcode.com/blogs/create-a-nginx-reverse-proxy-for-a-node-server-with-docker-compose


### 프로그램 실행

```
docker compose up
⠿ Network node-nginx-reverse-proxy_default  Created                                                                                                                                      0.1s
⠿ Container nginx-c                         Created                                                                                                                                      0.1s
⠿ Container node-c                          Created                                                                                                                                      0.1s
Attaching to nginx-c, node-c
nginx-c  | /docker-entrypoint.sh: Launching /docker-entrypoint.d/20-envsubst-on-templates.sh
nginx-c  | 20-envsubst-on-templates.sh: Running envsubst on /etc/nginx/templates/default.conf.template to /etc/nginx/conf.d/default.conf
nginx-c  | /docker-entrypoint.sh: Configuration complete; ready for start up
node-c   | 
node-c   | > node-nginx-reverse-proxy@1.0.0 start
node-c   | > node ./src/index.js
node-c   | 
node-c   | Express listening on port 8888
```
