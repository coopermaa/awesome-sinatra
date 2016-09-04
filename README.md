awesome-sinatra [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===============

> A curated list of awesome projects made or inspired with Sinatra.

# Contents

- [General](#general)
- [Authroization](#authroization)
- [Authentication](#authentication)
- [Blogging](#blogging)
- [Continous Integration](#continous Integration)
- [CMS](#cms)
- [File Uploading](#file-uploading)
- [Micro Frameworks inspired by Sinatra](#micro-frameworks-inspired-by-sinatra)
- [Micro Frameworks inspired by Sinatra (Other Languages)](#micro-frameworks-inspired-by-sinatra-other-languages)
- [NoSQL](#nosql)
- [ORM](#orm)
- [Service Integration](#service-integration)
- [Stylesheets](#stylesheets)
- [Wiki Engine](#wiki-engine)
- [Writing APIs](#writing-apis)

## General

* [Sinatra](http://www.sinatrarb.com/) - Sinatra Official website.
* [Sinatra on Github](https://github.com/sinatra/sinatra)
* [Sinatra Receipes](http://recipes.sinatrarb.com/) - Community contributed recipes and techniques.
* [Sinatra - The Book](http://sinatra-org-book.herokuapp.com/) - A cookbook full of excellent tutorials
  and recipes for developing Sinatra web applications. It's git repo is [here](https://github.com/sinatra/sinatra-book)
* [sinatra.github.com repo](https://github.com/sinatra/sinatra.github.com/) - This repo contains the 
  Sinatra website and documentation sources published at http://sinatra.github.com/.
* [Sinatra in the wild](https://github.com/sinatra/sinatra.github.com/blob/master/wild.markdown) - Various
  applications, extensions and websites built with Sinatra.
* [Sinatra mailing list](http://groups.google.com/group/sinatrarb/topics)

## Authroization

* [Sinatra Authorization](https://github.com/integrity/sinatra-authorization) - HTTP Authorization helpers for Sinatra.
* [Sinatra-authorize](https://github.com/gnab/sinatra-authorize) - Smooth authentication-agnostic rule-based 
  authorization extension for Sinatra.

## Authentication

* [hancock](https://github.com/atmos/hancock/) - An OpenID based Single Sign On server with a simple API, written in Sinatra   
* [hancock-client](https://github.com/atmos/hancock-client) - A sinatra app and rack middleware piece for the hancock SSO server

## Blogging

* [Blorgit](https://github.com/eschulte/blorgit) - A simple org-mode based, git amenable, blogging engine running on sinatra.
* [Haze](https://github.com/madx/haze) - A minimalistic blogging engine, the successor of Honk (~200 LOC). 
* [Honk](https://github.com/madx/honk) - A minimalistic, YAML, text-based blogging engine.
* [Marley](https://github.com/karmi/marley) - Minimalist blogging engine without textareas based on 
  Markdown, Ruby, Sinatra and Git push hooks.
* [Postview](https://github.com/hallison/postview) - A simple blog-engine that render text files written in Markdown.  
* [Scanty](https://github.com/adamwiggins/scanty) - A really small blogging software.
* [Scanty with CouchDB](https://github.com/jtulloch/scanty) - Scanty using CouchDB.
* [Sinandra](https://github.com/groupdock/sinandra) - A blog engine using Sinatra and Cassandra.
* [Wind](https://github.com/wagnerandrade/wind) - HTML5 blog engine focused in a easy, extensible and fast admin.
* [Yet-another-Sinatra-Blog-Engine](https://github.com/multikatt/Yet-another-Sinatra-Blog-Engine) - A simple blog engine written in Ruby using Sinatra.

## Continuous Integration

* [Integrity](https://github.com/integrity/integrity) - A continuous integration server.
* [Travis CI](https://github.com/travis-ci/travis-ci) - Free continuous integration platform for GitHub projects.
  Some sub-projects of Travis CI uses Sinatra, including [travis-api](https://github.com/travis-ci/travis-api),
  [travis-listener](https://github.com/travis-ci/travis-listener), [travis-logs](https://github.com/travis-ci/travis-logs)
  , [travis-build](https://github.com/travis-ci/travis-build) and [travis-web](https://github.com/travis-ci/travis-web)

## CMS

* [Nesta](https://github.com/gma/nesta) - A lightweight CMS, implemented in Sinatra. Content can be written
  in Markdown or Textile and stored in text file
* [Spontaneous](https://github.com/SpontaneousCMS/spontaneous) - An CMS with intuitive, attractive and responsive HTML5 interface  

## File Uploading

* [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) - A classier solution for file uploads for Rails,
  Sinatra and other Ruby web frameworks.

## Micro Frameworks inspired by Sinatra

* [Angelo](https://github.com/kenichi/angelo) - Sinatra-like DSL for Reel that supports WebSockets and SSE
  in their own thread, called "cells" (or actors). 
* [Gin](https://github.com/jcasts/gin) - A small Ruby web framework, built on Rack, which borrows from Sinatra expressiveness, 
  and targets larger applications.
* [Hobbit](https://github.com/patriciomacadden/hobbit) - A minimalistic microframework built on top of Rack (thanks to `Rack::Builder`).
   Hobbit is a DSL inspired by Sinatra. (~ 150 LOC).
* [Nancy](https://github.com/guilleiguaran/nancy) - Minimal Ruby microframework for web development inspired in `Sinatra` and `Cuba` (~150 LOC).
* [padrino](https://github.com/padrino/padrino-framework) - Padrino is a full-stack ruby framework built upon Sinatra.
* [Rack::App](https://github.com/rack-app/rack-app) - Bare bone minimalistic (masochistic) pico framework for building rack apps.
  Inspired by sinatra, grape and the pure use form of Rack.  
* [Sin](https://github.com/raggi/sin) - A multi-app web-app DSL derived from Sinatra, riding on rack.
  Sin is a rebuild of sinatra, splitting up the classes into files and going for a reusable application class.
* [Scorched](https://github.com/Wardrop/Scorched) - Light-weight, DRY as a desert, web framework for Ruby. Simliar to Sinatra. 
  Scorched is a true evolutionary enhancement of Sinatra, with more power, focus, and less clutter.

## Micro Frameworks inspired by Sinatra (Other Languages)

* Bash: [Astley](https://github.com/matschaffer/astley), [sh.inatra](https://github.com/emasaka/sh.inatra)
* C: [Bogart](https://github.com/tyler/Bogart)
* C++: [Garland](https://github.com/MarMarAba/Garland)
* Clojure: [Compojure](https://github.com/weavejester/compojure)
* CoffeeScript: [Zappa](https://github.com/mauricemach/zappa)
* Crystal: [frank](https://github.com/manastech/frank), [kemal](https://github.com/sdogruyol/kemal)
* Dart: [Start](https://github.com/lvivski/start)
* Erlang: [Fresh](https://github.com/devinus/fresh), [Spooky](https://github.com/flashingpumpkin/spooky)
* Haskell: [Bird](https://github.com/moonmaster9000/bird), [Miku](https://github.com/nfjinjing/miku),
  [Scotty](https://github.com/scotty-web/scotty)
* Go: [Martini](https://github.com/go-martini/martini), [Spooky](https://github.com/flashingpumpkin/spooky)
* Groovy: [Graffiti](https://github.com/webdevwilson/graffiti)
* Java: [Spark](https://github.com/perwendel/spark) 
* JavaScript: [Express](https://github.com/expressjs/express), [Sammy](https://github.com/quirkey/sammy)
* Julia: [Moresel.jl](https://github.com/JuliaArchive/Morsel.jl)
* Lua: [Mercury](https://github.com/nrk/mercury), [Orbit](http://keplerproject.github.io/orbit/)
* .NET: [Martini](https://github.com/thegrubbsian/Martin), [Nina](https://github.com/jondot/Nina)
* Perl: [Dancer](https://github.com/PerlDancer/Dancer2), [Mojolicious](https://github.com/kraih/mojo)
* PHP: [FatFree](https://github.com/bcosca/fatfree), [Fitzgerald](https://github.com/gregmolnar/fitzgerald), [Klein](https://github.com/klein/klein.php),
  [Zaphpa](http://zaphpa.org/)
* Python: [itty](https://github.com/toastdriven/itty), [Flask](https://github.com/pallets/flask)
* Scala: [Finatra](https://github.com/twitter/finatra), [Scalatra](https://github.com/scalatra/scalatra)

## NoSQL

> Column

* [Sinandra](https://github.com/groupdock/sinandra) - A blog engine using Sinatra and Cassandra.

> Document

* [sinatra-mongo](https://github.com/technicalpickles/sinatra-mongo) - A light extension to sinatra for using mongo.

> Key-value

* [redis-sinatra](https://github.com/redis-store/redis-sinatra) - Redis stores for Sinatra.
* [riak-browser](https://github.com/jlambert121/riak-browser) - A simple ruby/Sinatra Riak browser and editor. 

## ORM

* [sinatra-activerecord](https://github.com/janko-m/sinatra-activerecord) - Extends Sinatra with ActiveRecord helper methods and Rake tasks.
* [sinatra-datamapper](https://github.com/jmkeyes/sinatra-datamapper) - A Sinatra extension for DataMapper ORM support.
* [sinatra-sequel](https://github.com/rtomayko/sinatra-sequel) - Sinatra extension that adds Sequel ORM features, database config, and database migrations.

## Service Integration

> Slack

* [beach](https://github.com/willrax/beach) - Small Sinatra app to host web hooks for Slack.
* [dogetip-slack](https://github.com/tenforwardconsulting/dogetip-slack) - Sinatra app to enable Dogecoin tipping via slack
* [doorbell-server](https://github.com/Lostmyname/doorbell-server) - Simple Sinatra app which acts a bridge between Slack and the LMN doorbell.
* [snarkov](https://github.com/gesteves/snarkov) - Sinatra-based Markov bot for Slack. 

> MISC

* [shopify-sinatra-app](https://github.com/kevinhughes27/shopify-sinatra-app) - Lightweight extension for
  building Shopify apps using Sinatra

## Stylesheets

* [sinatra-compass](https://github.com/rkh/sinatra-compass) - Integrates the Compass stylesheet framework with Sinatra.
* [haml-more](https://github.com/rkh/haml-more) - Adds more functionality to Haml and Sass.

## Wiki Engine

* [bliki](https://github.com/bomberstudios/bliki) - A small blog + wiki engine built on Sinatra + Stone.
* [git-wiki](https://github.com/sr/git-wiki) - A quick & dirty git-powered Sinatra wiki (~200 LOC).
* [rikiki](https://github.com/yarmand/rikiki) - Tiny wiki engine using in browser markdown and Sinatra.
* [Weaky](https://github.com/benatkin/weaky) - A basic CouchDB/Sinatra wiki.

## Writing APIs

* [Pliny](https://github.com/interagent/pliny) - Pliny helps Ruby developers write and maintain excellent APIs.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [coopermaa](http://coopermaa2nd.blogspot.tw/) has waived all copyright and related or neighboring rights to this work.