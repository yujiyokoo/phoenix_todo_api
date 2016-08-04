# TodoApi

[![Build Status](https://travis-ci.org/yujiyokoo/phoenix_todo_api.svg?branch=master)](https://travis-ci.org/yujiyokoo/phoenix_todo_api)

Todo API from https://blog.codeship.com/an-introduction-to-apis-with-phoenix/

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000/api/todos`](http://localhost:4000/api/todos) from your browser.

Use curl as below to create todo items.

```
curl --data "todo[description]=water plant&todo[complete]=0" http://localhost:4000/api/todos
```
