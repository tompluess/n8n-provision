# n8n-provision
Self-hosted n8n - these are my provision scripts.


## Setup

* Copy `example.env` to `.env` and adapt it.
* Copy and adapt the `caddy_config` folder to your `$DATA_FOLDER`.


## n8n Workflows

Alls Workflows stored in `n8n/backup/workflows` will be restored on every startup of the `docker-compose.yml`.
