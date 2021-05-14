# blog

This is the sample application for a blog app

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.2.17
$ bundle _2.2.17_ config set --local without 'production'
$ bundle _2.2.17_ install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the rails server command

```
$ rails server
```
Check out the following route
/articles/

You can access the CRUD methods with the links on the show page