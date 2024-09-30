# hello-world

A monorepo I use for various testing and development purposes.

## nginx-hello-world

This app can be used to create a simple and unprivileged NGINX docker for testing purposes. It returns a single view on its root path and exposes port `8080`.

Pull and run the docker image via:

```bash
docker pull spuxx/nginx-hello-world
docker run nginx-hello-world -p 8080:8080
```
