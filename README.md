Higgins [Heroku]
================

## Deploy Higgins on Heroku
```bash
$> heroku create myapp_name
$> heroku config:add BUILDPACK_URL=https://github.com/igrigorik/heroku-buildpack-dart.git -a myapp_name
$> heroku git:clone -a myapp_name
$> git remote add higgins https://github.com/ggirou/higgins-heroku.git
$> git pull higgins master
$> git push heroku master
```
