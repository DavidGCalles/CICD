# Jenkins through Docker

Jenkins Server is going to be deployed on docker compose.

## Deployment command

```docker-compose up -d```

### Development notes

- Development starts on this [url](https://www.adictosaltrabajo.com/2020/05/29/usando-jenkins-y-docker/).
	- This url shows a compose only valid for linux. To make it SO agnostic, volumes are named volumes, which docker manages the same way independent from SO.
	- First instance we are going to get the most skinned version of jenkins working, without blueocean, extra volumes or plugins. Just a barebones jenkins to interact with.