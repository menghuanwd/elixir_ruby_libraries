# Frameworks

Rails Vs Phoenix

## Rails

```shell
gem install rails
```

```shell
rails new rails-demo
cd rails-demo
bundle install
rails s
```

## Phoenix

```shell
mix local.hex
mix archive.install hex phx_new
```

```shell
mix phx.new phoenix-demo
cd phoenix-demo
mix deps.get
mix phx.server
```

mix == (rake, rails)
hex == (gem)

## Console

```ruby
irb
rails c
```

```elixir
iex
iex -S mix
iex -S mix phx.server
```

## Environment

```shell
MIX_ENV=test 
RAILS_ENV=test rspec
```
