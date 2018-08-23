# resin-caddy

[resin.io](https://resin.io/) stack with the following services:
* [caddy](https://caddyserver.com/)
* [ssh](https://www.ssh.com/ssh/)
* [duplicati](https://www.duplicati.com/)

## Getting Started

see https://docs.resin.io/learn/getting-started

## Deployment

### Application Environment Variables

|Name|Value|
|---|---|
|`TZ`|`America/Toronto`|

### Service Variables

|Service|Name|Value|
|---|---|---|
|`caddy`|`ACME_EMAIL`|`example@address.com`|
|`caddy`|`CLOUDFLARE_EMAIL`|`example@address.com`|
|`caddy`|`CLOUDFLARE_API_KEY`|`0bd1e80697be44bd8727050923faa84a`|

## Usage

* browse to `http://<device-ip>:80` to access the default webserver
* browse to `http://<device-ip>:8200` to access the duplicati admin interface

## Author

Kyle Harding <kylemharding@gmail.com>

## License

_tbd_

## Acknowledgments

* https://github.com/resin-io/resin-caddy
* https://github.com/abiosoft/caddy-docker
* https://github.com/linuxserver/docker-duplicati-armhf
