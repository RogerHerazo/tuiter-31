# Project

[tuiter-31.herokuapp.com](https://tuiter-31.herokuapp.com/)

## Install

### Clone the repository

```shell
git clone git@github.com:RogerHerazo/tuiter-31.git
cd tuiter-31
```

### Check your Ruby version

```shell
ruby -v
```

The ouput should start with something like `ruby 3.1.0`

If not, install the right ruby version using [rbenv](https://github.com/rbenv/rbenv) (it could take a while):

```shell
rbenv install 3.1.0
```

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler) and [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Initialize the database

```shell
rails db:create db:migrate
```

## Serve

```shell
rails s
```