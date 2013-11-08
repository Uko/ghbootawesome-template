This is a template for static sites that I use to do quite often.

Contains basic setup for:

  * [Github pages](http://pages.github.com)
  * [Twitter bootstrap](http://getbootstrap.com)
  * [Font awesome](http://fontawesome.io)

Personal/Organization page
--------------------------

Either fork and rename to `name.github.io`, where the _name_ is your username or organization name;

Or do

    git clone https://github.com/Uko/ghbootawesome-template.git name.github.io

where the _name_ is your username or organization name, create a repository with a same name and push it there.

Project page
------------

To add this to an existing project you have to do something like this:

    git remote add ghbootawesome https://github.com/Uko/ghbootawesome-template.git
    git fetch ghbootawesome
    git checkout -b gh-pages ghbootawesome/master

Usage
-----

Basic Jekyll idea.

Install gems

    bundle install

Start Jekyll server

    jekyll serve -w

Edit your site and check how it looks like at [http://localhost:4000/](http://localhost:4000/)