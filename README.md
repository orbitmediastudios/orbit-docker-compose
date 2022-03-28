### Collection docker compose with apache, php and mysql.

__See php version folder for your project requirement.__

PHP is based on official image with additional extensions, composer, drush(use local for D8+), wp-cli.   
See image [OrbitMedia Docker Hub](https://hub.docker.com/r/orbitmedia/php/).

Initial DB credentials are in docker-vh/db_env.env file. Update before first run. Keep root as root.

### _To use:_

- clone to your machine - so you can pull latest version
- grab content (```docker-compose.yml``` and ```docker-vh```) of desired version directory and copy in your project directory
- run docker-compose up -d to start - it'll create .data folder for database
- run docker-compose down to stop containers
