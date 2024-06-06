# README

Exercicio de refatoração realizado por:

- Guilherme de Araujo Gabriel - <guilhermag@gmail.com>
- Gustavo Luis Knecht Klein - <gustavo.klein@live.com>

Para a disciplina de [Processo de Modernização de Software](https://gist.github.com/tiagogeraldi/dd1fc01db7194166a79a57cd2d5e19de)

## Setup

```sh
asdf shell ruby 3.3.0
asdf shell nodejs 20.11.0

bundle

yarn

bundle exec rails app:update:bin

bin/rails db:create db:migrate db:seed
```

## Start the project

```sh
bin/dev
```

## Run specs

```sh
bin/rails db:create db:migrate RAILS_ENV=test

bundle exec rspec
```
