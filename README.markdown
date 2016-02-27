# `docker-nginx-gen-letsencrypt`

This is an opinionated improvisation to get a self-encrypting load balancer in front of Docker containers.
First clone this repository into its expected location and change the present working directory there with `git clone https://github.com/ecobytes/docker-nginx-gen-letsencrypt.git /srv/nginx && cd /srv/nginx`.

* Run with `./run`
* Debug with `docker-compose ps` or `docker-compose logs`
* Remove with `docker-compose stop` and `docker-compose rm`

## License

Licensed by [almereyda](https://almereyda.de/) under the GNU General Public License 3.0. See the LICENSE for its terms.
