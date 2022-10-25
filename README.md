# docker-compose-laravel
This is a fork of the [docker-compose-laravel](https://github.com/aschmelyun/docker-compose-laravel), made by [Andrew Schmelyun](https://github.com/aschmelyun/docker-compose-laravel/commits?author=aschmelyun)

## My changes 

- removed the src folder, so that the laravel app must be placed in the root folder
- database credentials are fetched from .env file
- created mysql volume, so that the database persists over container restart

## troubleshooting
- when using php 8.0, laravel 9.* , some error occured, solve it by adding a bunch of symfony requires to composer.json (see [this article](https://webdevask.com/items/laravel-9-composer-syntax-error-unexpected-token))


Original documentation is copied [here](https://github.com/frankvanderwal/docker-compose-laravel/blob/master/README%20original.md) (in case the original repo will cease to exist)
