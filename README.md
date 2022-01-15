# PVS deploy
Self-host a production-optimized PVS in any place.

Note that this deployment is not for development use.

### Before start

Ensure Docker has already been installed in your environment.
[Install guide](https://docs.docker.com/get-docker/)

### Deploy steps

1. clone this repository.
2. create your `.env` file in the project root. There's an example env file you may use in this repository.
3. `docker compose up -d`
4. The front end will be exposed on the `3000` port, and the backend will be the `9100` port.

### Images on docker hub

- [Frontend](https://hub.docker.com/r/xanonymous/pvs-frontend)
- [Backend](https://hub.docker.com/r/xanonymous/pvs-backend)
