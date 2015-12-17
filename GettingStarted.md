# Elixir |> Baltimore

## Getting Started

Some resources for getting started with Elixir.

Visit the [Elixir site](http://elixir-lang.org).

Pragmatic Programmers 
- [Short Video](https://www.youtube.com/watch?v=hht9s6nAAx8&feature=youtu.be).
- [Longer intro](https://www.youtube.com/watch?v=a-off4Vznjs&feature=youtu.be)

### Installation
[Installing Elixir](http://elixir-lang.org/install.html)


### Learning and Practicing

* [Cheat sheet](https://media.pragprog.com/titles/elixir/ElixirCheat.pdf)
* [Études for Elixir](http://chimera.labs.oreilly.com/books/1234000001642): Learning step-by-step 
* [Exercism.io](http://exercism.io/languages/elixir): Practice exercises
* [Elixir Golf](http://elixirgolf.com/): Simple problems to solve in the fewest number of characters. The completed ones have very clever solutions.
* [Advent of Code](http://adventofcode.com): Small code problems to work through


### Phoenix Framework
Visit the [Phoenix Framework site](http://www.phoenixframework.org/).

#### Installation
[Installing Phoenix](http://www.phoenixframework.org/docs/installation).

````bash
$ mix local.hex

$ mix archive.install https://github.com/phoenixframework/phoenix/releases/download/v1.0.4/phoenix_new-1.0.4.ez
````
#### Deploying to Heroku
Guide to [deploying a Phoenix app to Heroku](http://wsmoak.net/2015/07/05/phoenix-on-heroku.html).

````bash
$ mix local.hex

$ mix phoenix.new bmore_on_elixir
$ cd bmore_on_elixir
$ git init && git add . && git commit -m "Initial commit of B'more on Elixir app."

$ heroku create
$ heroku buildpacks:set https://github.com/gjaldon/phoenix-static-buildpack
$ heroku buildpacks:add --index 1 https://github.com/HashNuke/heroku-buildpack-elixir

$ git push heroku master
````

#### Misc.
[Awesome Elixir](https://github.com/h4cc/awesome-elixir).
