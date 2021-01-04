# hyperf_docker_compose_autoconf

#### Introduction
Support one-key fool-style configuration to start the hyperf environment. Which built-in php, mysql, redis, rabbitmq, memcached mirror arrangement, supports custom designation of official mirror tags, and official mirror customization. You can also increase or decrease the required environment. Follow-up updates of each environment arrangement example.

#### Instructions for use

1. Copy `.env.example` file ```cp .env.example .env```
2. Customize and modify the configuration mapping file and port in the `.env` file and the required mirror version. If you don’t know the version, you can click [Search Mirror](https://registry.hub.docker.com/ "Search Mirror" Search in) to view `tag`
3. Use `docker-compose` related commands to operate, such as ```docker-compose up``` run, ```docker-compose up -d``` run in the background, specific usage [docker-compose](https ://www.runoob.com/docker/docker-compose.html "docker-compose").

#### Participate in Contribution

1. Fork this warehouse
2. Create new Feat_xxx branch
3. Submit the code
4. New Pull Request