# docker-php-nginx-mysql

Starting a PHP Web Application with Docker

## Usage

```bash
$ cd docker

# create .env file and edit it the first time
$ cp .env.sample .env

# Start the containers
$ make up

# Start serving
# http://localhost:3000

# Enter the app container
$ make app

# Stop the containers
$ make down
```

## License

MIT
