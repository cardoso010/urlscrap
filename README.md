# Urlscrap

Extract urls from sites.

## Setup

Get dependencies

```shell
mix deps.get
```

Compile application

```shell
mix escript.build
```

Run app with following args

```shell
./bin/urlscrap --extract-links --url "https://github.com" --save
```

## Args

| Args          | Descrition                  |
| ------------- | --------------------------- |
| extract-links | Get all urls from site      |
| url           | Url of site                 |
| save          | If you want to save in file |
