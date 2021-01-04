# hyperf_docker_compose_autoconf

#### 介绍
支持一键傻瓜式配置启动hyperf环境。其中内置php,mysql,redis,rabbitmq,memcached镜像编排,支持自定义指定官方镜像tag,官方镜像自定义。也可自行增减所需环境。后续更新各个环境编排例子。

#### 使用说明

1.  复制`.env.example` 文件 ```cp .env.example .env```
2.  自定义修改`.env`文件中的配置映射文件以及端口以及所需镜像版本.不清楚版本的可以点击[搜索镜像](https://registry.hub.docker.com/ "搜索镜像")中搜索,查看`tag`
3.  使用`docker-compose` 相关命令操作,例如```docker-compose up ```运行, ```docker-compose up -d```后台运行, 具体使用方式[docker-compose](https://www.runoob.com/docker/docker-compose.html "docker-compose")。

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
