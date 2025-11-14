# cloudflard-docker-compose-example
A example start point for deploying a docker compose file that uses cloudflard by Cloudflare to create a secure tunnel between internet and internal systems.

Note there is **NOTHING** special about the file `.env_cloudflare`.
This file could be renamed to anything.
The only contents of the file should be text that conforms to a .env file for use by docker to specify environment variables.

This repo contains no recommendations as to how to configure your tunnel with cloudflare.
All configuration can be done via CLI or web UI in cloudflare zero trust.

# Note
You will require a registered domain ( `this-is-my-example-domain.com` ) and you will need to point your nameservers ( `ns1.` and `ns2.` ) to cloudflare for zero trust and tunneling.
