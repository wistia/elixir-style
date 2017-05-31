# elixir-style
Wistia's Elixir styles

## Overview

This repo contains common style configuration for Elixir apps (e.g. our [credo](https://github.com/rrrene/credo) config)

## Setup

To setup this repo for local development:

```
git clone https://github.com/wistia/elixir-style
ln -s elixir-style/.credo.exs ~/.credo.exs
```

To setup this repo in a Dockerfile:

```
wget https://github.com/wistia/elixir-style/blob/master/.credo.exs -O ~/.credo.exs
```

Then add `mix credo` to your CI build:

```
mix credo && mix test
```
