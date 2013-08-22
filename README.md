mturk-thing
===========

a thing for posting HITs on Mechanical Turk

commands to set it up on heroku:

```
heroku apps:create mturk-thing
heroku addons:add mongohq:sandbox

heroku config:set HOST=http://mturk-thing.herokuapp.com
heroku config:set SESSION_SECRET=change_me

git push heroku master
```
