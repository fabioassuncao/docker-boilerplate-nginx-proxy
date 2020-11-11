# NGINX Boilerplate Proxy

<div align="center">
  <img src="examples/cover.svg" loading="lazy" />
</div>

Boilerplate for quick configuration of Docker containers for reverse proxy with [NGINX](https://github.com/nginx/nginx), automatic configuration of virtualhosts and generation of SSL certificates with Let's Encrypt.

## Requirements

* Docker 19.03 or higher
* Docker Compose 1.27 or higher

## Installation

1. [Download](https://github.com/fabioassuncao/docker-boilerplate-nginx-proxy/archive/master.zip) the latest version
2. Create a new Docker network called `web`
3. Create a new Docker network called `internal`
4. Running the Traefik Container: `docker-compose up -d`

## Tips

If you are looking for a script for initial server settings on DigitalOcean, Linone, AWS EC2 or similar, see the repository [fabioassuncao/setup-vps](https://github.com/fabioassuncao/setup-vps)

## Contributing

1. Fork this repository!
2. Create your feature from the **develop** branch: git checkout -b feature/my-new-feature
3. Write and comment your code
4. Commit your changes: `git commit -am 'Add some feature'`
5. Push the branch: `git push origin feature/my-new-feature`
6. Make a pull request to the branch **develop**

## Credits

* [Fábio Assunção](https://github.com/fabioassuncao)
* [All Contributors](../../contributors)


## License

Licensed under the MIT License.s