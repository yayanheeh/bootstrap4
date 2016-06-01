# [RWGPS Bootstrap](http://getbootstrap.com)

This is the RideWithGPS customized version of Bootstrap. We are currently on version 3. For the official Bootstrap README, see https://github.com/twbs/bootstrap.

# Quick Start

```sh
# install dependencies
npm i -g grunt
npm i
# compile minified files
grunt dist
```

# Updating [ridewithgps/ridewithgps](github.com/ridewithgps/ridewithgps)

1. Get a PR to this repo merged with your modifications
2. Make sure your dist folder is up-to-date `gulp dist`
3. Copy files:

```
cp dist/css/bootstrap{.css,.css.map} ../ridewithgps/public/stylesheets
cp dist/css/bootstrap-theme{.css,.css.map} ../ridewithgps/public/stylesheets
cp -R less/* ../ridewithgps/public/stylesheets/less/
```
