# Wordpress on Heroku

Wordpress on Heroku based on [Bedrock from roots.io](https://roots.io/bedrock/).

GitHub projects:

* [roots/bedrock](https://github.com/roots/bedrock)
* [frc/bedrock-on-heroku](https://github.com/frc/bedrock-on-heroku) _(upstream)_ - prepared by [Frantic](http://www.frantic.com/)

## Development

### Heroku local

Run commands:

    cp .env.local .env
    composer install
    heroku local

Open URL: http://localhost:5000/

### Vagrant

Run commands:

    cp .env.vagrant .env
    composer install
    vagrant up

Open URL: http://localhost:8000/

Vagrant box: [Homestead](https://laravel.com/docs/master/homestead)

## Wordress plugins and themes

To install Wordpress plugins or themes use: Composer and [WPackagist](https://wpackagist.org/)

## Read more

* [Roots.io: Bedrock](https://roots.io/bedrock/) from Roots.io
* [Roots.io: Using composer with Wordpress](https://roots.io/using-composer-with-wordpress/)
* [Heroku Dev Center: Heroku local](https://devcenter.heroku.com/articles/heroku-local)
