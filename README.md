# Heroku buildpack: PHP with PEAR Mail

This is the official [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for PHP applications modified to run Pear Mail. Additionally, GZIP compression is enabled.

## Usage

Method 1: In your app setting page include this repository as a BUILDPACK_URL in the Config Vars.

Method 2: In your app directory run the following command:

    heroku config:add BUILDPACK_URL=https://github.com/blindstuff/heroku-buildpack-php.git