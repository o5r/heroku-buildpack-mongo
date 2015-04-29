# Heroku buildpack: MongoDB

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run mongo commands (http://www.mongodb.org/).

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack http://github.com/Lendix/heroku-buildpack-mongo.git

    $ git push heroku master
