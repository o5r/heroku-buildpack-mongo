# Heroku buildpack: MongoDB

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run mongo commands (http://www.mongodb.org/).

It installs MongoDB 4.2.3 for Ubuntu 16.04 or 18.04 from https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu1604-4.2.3.tgz or https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu1804-4.2.3.tgz.

Usage
-----

Example usage:

    $ heroku create myapp --buildpack http://github.com/Lendix/heroku-buildpack-mongo.git
    $ git push heroku master
    
or:

    $ heroku buildpacks:add http://github.com/Lendix/heroku-buildpack-mongo.git
