# DockerImage for Strapi V4 (unofficial)

Unofficial docker image for building strapi V4 to use postgresql.

# Diff from official image

- Enable to use Strapi V4 with Docker.
- Enable to install @strapi/plugin-graphql.

# How to run

### build image

```shell
docker-compose build
docker compose up # 5分ほど時間がかかる
```

### access

http://localhost:1337/admin

### Ref.

[issue] V4 images on DockerHub #321
https://github.com/strapi/strapi-docker/issues/321
