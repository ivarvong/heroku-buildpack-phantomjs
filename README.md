Heroku buildpack: PhantomJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of PhantomJS (http://phantomjs.org) 2.1.1. It pulls a `tgz` directly from https://bitbucket.org/ariya/phantomjs/downloads.

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/ivarvong/heroku-buildpack-phantomjs.git

# or if your app is already created:
$ heroku buildpacks:add https://github.com/ivarvong/heroku-buildpack-phantomjs

$ git push heroku master
```
