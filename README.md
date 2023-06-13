Docker Develop Environment

使用前先创建网络：`docker network create traefik-network`，在配置 NETWORK 变量。

nginx 与 nginx-inner 选择其中一个，nginx-inner 配合 traefik 使用。