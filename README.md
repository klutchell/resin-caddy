# resin-caddy

[resin.io](https://resin.io/) stack with the following services:
* [caddy](https://caddyserver.com/)
* [ssh](https://www.ssh.com/ssh/)
* [duplicity](https://github.com/blacklabelops/volumerize)

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
|`volumerize`|`AWS_ACCESS_KEY_ID`|`QQWDQIWIDO1QO`|
|`volumerize`|`AWS_SECRET_ACCESS_KEY`|`ewlfkwkejflkjwlkej3fjw381`|
|`volumerize`|`PASSPHRASE`|`secretgpgpassword`|
|`volumerize`|`VOLUMERIZE_FULL_IF_OLDER_THAN`|`7D`|
|`volumerize`|`VOLUMERIZE_TARGET`|`s3://s3.eu-central-1.amazonaws.com/duplicitytest`|

## Usage

browse to `http://<device-ip>:80` to access the default webserver

## Author

Kyle Harding <kylemharding@gmail.com>

## License

_tbd_

## Acknowledgments

* https://github.com/resin-io/resin-caddy
* https://github.com/abiosoft/caddy-docker
* https://github.com/blacklabelops/volumerize
