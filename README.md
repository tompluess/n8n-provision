# n8n-provision
Self-hosted n8n - these are my provision scripts.


## Setup

* Copy `example.env` to `.env` and adapt it.
* Copy and adapt the `caddy_config` folder to your `$DATA_FOLDER`.

Start your setup with

> docker compose up

or in detached mode with a specific project name:

> docker compose -p n8n up -d


## n8n Workflows

Alls Workflows stored in `n8n/backup/workflows` will be restored on every startup of the `docker-compose.yml`.

I am maintaining some workflows to synchronize data between [Moco](https://www.mocoapp.com) and [Bexio](https://www.bexio.com).
