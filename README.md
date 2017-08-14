# Symfony 3 base application
This is a Symfony 3 base application with:
  - [FOSUserBundle]
  - [EasyAdminBundle]
  - [Twitter Bootstrap]
  - [Bower] for managing JS dependencies
  - [Gulp] for managing assets

# Installation
1. Install Bower and bower dependencies which are Gulp tools *(gulp-concat, gulp-stylus, gulp-sass, gulp-uglify etc..)*
```sh
npm install bower
bower install
```

2. Run gulp for assets.
```sh
gulp
```

3. Install vendors by running
```sh
composer update
```

4. Enjoy !

# What I'd like TODO next
  - Create a docker container
  - Add a simple custom user profile space
  - Add a default mail template for user's email
  - API with API-Platform

   [FOSUserBundle]: <https://github.com/FriendsOfSymfony/FOSUserBundle>
   [EasyAdminBundle]: <https://github.com/javiereguiluz/EasyAdminBundle>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [Bower]: <https://bower.io/>
   [Gulp]: <http://gulpjs.com>
