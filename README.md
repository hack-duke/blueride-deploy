# blueride-deploy
Deployment setup for Blueride

## deploying
copy the certificates (on the AWS EC2 instance rn in /blueride-deploy/caddy_data) or regenerate them

`$ docker-compose up -d` to run the instances

move the DNS records on CloudFlare

test by downloading the app and seeing that workflow still works
