<h1 align="center">Uchain.info frontend</h1>


## Running and configuring the app

You can configure your app by passing necessary environment variables when starting the container. See full list of ENVs and their description [here](./docs/ENVS.md).

```sh
docker run -d --name uchain-frontend -p 3000:3000 --env-file <path-to-your-env-file> ghcr.io/blockscout/frontend:latest
```
