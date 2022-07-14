# Prerequisites

- `docker`
- `docker-compose`

# Usage

- `mkdir .jupyter`
- `mkdir notebooks`
- `docker-compose up --build -d` to start a jupyterlab container
- `docker logs jupyterlab-with-r_jupyterlab-r_1` to obtain a token
- Access the jupyterlab from a web browser (default port: `8888`) and key in the token
- `docker-compose down` to halt the container
