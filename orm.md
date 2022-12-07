# Orm

ActiveRecord VS Ecto

|  | ActiveRecord | Ecto |
| --- | --- | --- |
| create db | rails db:create | mix ecto.create |
| drop db | rails db:drop | mix ecto.drop |
| migrate | rails db:migrate | mix ecto.migrate |
| rollback | rails db:rollback | mix ecto.rollback |
| seed | rails db:seed | mix run priv/repo/seeds.exs |

## create migration

```shell
rails g migration user nickname:string
mix ecto.gen.migration create_users
```

## create scaffold

```shell
rails g model user nickname:string
mix phx.gen.json Database Bank banks name:string:unique
```

## Environment

```shell
MIX_ENV
RAILS_ENV
```
