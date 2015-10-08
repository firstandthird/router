# router
docker router powered by nginx

## features
* auto route to containers as they are started
* send logs to logentries

## usage

`LOGENTRIES_TOKEN={token} docker-compose up -d`

## containers

Add `VIRTUAL_HOST=domain.com` to your containers as an environment var and nginx will automatically route to that container
