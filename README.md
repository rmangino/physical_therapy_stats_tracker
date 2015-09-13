## README ##

----

Starter Rails app which has devise configured (sign in, sign up, sign out) with email confirmation enabled.

To activate the app on heroku do:

* ```$ heroku login```

* ```$ heroku apps:create [heroku name]```

* ```$ heroku addons:create sendgrid:starter```

* ```$ heroku addons```

* ```$ heroku config:get SENDGRID_USERNAME```
* ```$ heroku config:get SENDGRID_PASSWORD```

* ```$ heroku config:set SENDGRID_USERNAME=[username] SENDGRID_PASSWORD=[password]```

* ```$ git push; git push heroku master; heroku run rake db:migrate; tput bel;```