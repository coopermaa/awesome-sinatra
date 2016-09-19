awesome-sinatra [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===============

> A curated list of awesome projects made or inspired with Sinatra.

# Contents

- [General](#general)
- [Generators](#generators)
- [Authroization](#authroization)
- [Authentication](#authentication)
- [Blogging](#blogging)
- [Boilerplate and Template](#boilerplate-and-template)
- [Community platform](#community-platform)
- [Continous Integration](#continous Integration)
- [CMS](#cms)
- [Debugging and Profiling](#debugging-and-profiling)
- [Email](#email)
- [File Uploading](#file-uploading)
- [Internet Application Clones](#internet-application-clones)
- [Micro Frameworks inspired by Sinatra](#micro-frameworks-inspired-by-sinatra)
- [Micro Frameworks inspired by Sinatra (Other Languages)](#micro-frameworks-inspired-by-sinatra-other-languages)
- [NoSQL](#nosql)
- [ORM](#orm)
- [Routers](#routers)
- [Service Integration](#service-integration)
- [Stylesheets](#stylesheets)
- [Testing](#testing)
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

## Generators

* [Corneal](https://github.com/thebrianemory/corneal) - A Sinatra app generator with Rails-like simplicity.
* [Hazel](https://github.com/c7/hazel) - A simple Sinatra app generator, heavily based on snfn.
* [Snfn](https://github.com/zachpendleton/snfn) - A Sinatra application generator. 

## Authroization

* [Sinatra Authorization](https://github.com/integrity/sinatra-authorization) - HTTP Authorization helpers for Sinatra.
* [Sinatra-authorize](https://github.com/gnab/sinatra-authorize) - Smooth authentication-agnostic rule-based 
  authorization extension for Sinatra.

## Authentication

* [hancock](https://github.com/atmos/hancock/) - An OpenID based Single Sign On server with a simple API, written in Sinatra   
* [hancock-client](https://github.com/atmos/hancock-client) - A sinatra app and rack middleware piece for the hancock SSO server
* [sinatra-oauth-provider](https://github.com/eddanger/sinatra-oauth-provider) - A Sinatra OAuth Provider.

## Blogging

* [Blorgit](https://github.com/eschulte/blorgit) - A simple org-mode based, git amenable, blogging engine running on sinatra.
* [Haze](https://github.com/madx/haze) - A minimalistic blogging engine, the successor of Honk (~200 LOC). 
* [Honk](https://github.com/madx/honk) - A minimalistic, YAML, text-based blogging engine.
* [Marley](https://github.com/karmi/marley) - Minimalist blogging engine without textareas based on 
  Markdown, Ruby, Sinatra and Git push hooks.
* [Postview](https://github.com/hallison/postview) - A simple blog-engine that render text files written in Markdown.  
* [Scanty](https://github.com/adamwiggins/scanty) - A really small blogging software.
* [Scanty with CouchDB](https://github.com/jtulloch/scanty) - Scanty using CouchDB.
* [scanty-redis](https://github.com/adamwiggins/scanty-redis) - Scanty using redis.
* [sin](https://github.com/kastner/sin) - A mini blog engine in Sinatra with hAtom and MetaWeblog API and S3 upload support (~160 LOC).
* [Sinandra](https://github.com/groupdock/sinandra) - A blog engine using Sinatra and Cassandra.
* [Wind](https://github.com/wagnerandrade/wind) - HTML5 blog engine focused in a easy, extensible and fast admin.
* [Yet-another-Sinatra-Blog-Engine](https://github.com/multikatt/Yet-another-Sinatra-Blog-Engine) - A simple blog engine written in Ruby using Sinatra.

## Boilerplate and Template

* [Frank-Sinatra](https://github.com/Wixel/Frank-Sinatra) - A boilerplate for modular MVC style Sinatra (1.4.2^) applications.
* [puresong](https://github.com/al-kivi/puresong) - A small Sinatra application that demonstrates use of Pure CSS with SQLite.
* [ratpack](https://github.com/ashleygwilliams/ratpack) - Sinatra boilerplate using activerecord, sqlite, and twitter bootstrap.
* [sinatra-boilerplate](https://github.com/karlcoelho/sinatra-boilerplate) - Starter Kit for Sinatra Apps. It uses
  [Twitter Bootstrap 3](http://getbootstrap.com/), [jQuery](http://jquery.com/) and [Modernizr](http://modernizr.com/)
* [sinatra-boilerplate](https://github.com/evanleck/sinatra-boilerplate) - Another boilerplate combined with
  [HTML 5 Boilerplate](http://html5boilerplate.com/), [Compass](http://compass-style.org/), [CoffeeScript](http://coffeescript.org/)
  and [Sprockets](https://github.com/sstephenson/sprockets).
* [sinatra-boilerplate](https://github.com/neverstopbuilding/sinatra-boilerplate) - Sinatra, Zurb 
  Foundation, Guard, Slim, Compass, RSpec, Capybarra... All the bling ready to go.
* [sinatra-boilerplate](https://github.com/mislav/sinatra-boilerplate) - Sinatra + Haml + Sass + Compass + Bourbon + CoffeeScript.
* [sinatra-foundation-skeleton](https://github.com/jerodsanto/sinatra-foundation-skeleton) - A skeleton 
  Sinatra application which utilizes Zurb's Foundation 3 framework.
* [sinatra-template](https://github.com/zapnap/sinatra-template) - A base Sinatra application template with DataMapper, and RSpec.
* [sinatra-twitter-bootstrap](https://github.com/mfojtik/sinatra-twitter-bootstrap) - Twitter Bootstrap Sinatra extension with HAML helpers.  

## Community Platform

* [sinforum](https://github.com/makevoid/sinforum) - Simple forum build with Sinatra, DataMapper, Haml, SASS and CoffeeScript.

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

## Debugging and Profiling

> For more, check the "Middlewares for Debugging or Profiling" section in [awesome-rack](https://github.com/coopermaa/awesome-rack)

* [Better Errors](https://github.com/charliesome/better_errors) - Better Errors replaces the standard 
  Rails error page with a much better and more useful error page. It is also usable outside of Rails 
  in any Rack app as Rack middleware.
* [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) - Middleware that displays speed 
  badge for every html page. A simple but effective mini-profiler for .NET, Ruby, Go and Node.js. 
  Introduced in [Railscasts #368 MiniProfiler](http://railscasts.com/episodes/368-miniprofiler)
* [racksh](https://github.com/sickill/racksh) - Console for Rack based ruby web apps. It's like 
  script/console in Rails (~ 100 LOC) or merb -i in Merb, but for any app built on Rack. Thanks to Rack::Test::Methods (from rack-test) and Ruby REPLs (pry and irb).
* [tux](https://github.com/cldwalker/tux) - A sinatra shell to interacte with helpers, view rendering and to 
  view your app's routes and settings.

## Email

* [sinatra-email-services-server](https://github.com/linhchauatl/sinatra-email-services-server) - An email services server using Sinatra.
* [sinatra-mailer](https://github.com/foca/sinatra-mailer) - Send emails from Sinatra in a very simple way.

## File Uploading

* [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) - A classier solution for file uploads for Rails,
  Sinatra and other Ruby web frameworks.

## Internet Application Clones

* [chirp](https://github.com/sausheong/chirp) - Simple Sinatra-based micro-blog/Twitter clone.
* [shorty](https://github.com/croaky/shorty) - URL shortener written in Sinatra & MongoDB.

## Micro Frameworks inspired by Sinatra

* [Angelo](https://github.com/kenichi/angelo) - Sinatra-like DSL for Reel that supports WebSockets and SSE
  in their own thread, called "cells" (or actors). 
* [Dolly](https://github.com/coopermaa/dolly) - Minimal Ruby microframework inspired by Sinatra.
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
* Elixir: [Plug](https://github.com/elixir-lang/plug), [Spirit](https://github.com/emancu/spirit)
* Erlang: [Fresh](https://github.com/devinus/fresh), [Spooky](https://github.com/flashingpumpkin/spooky)
* Haskell: [Bird](https://github.com/moonmaster9000/bird), [Miku](https://github.com/nfjinjing/miku),
  [Scotty](https://github.com/scotty-web/scotty)
* Go: [Martini](https://github.com/go-martini/martini), [Spooky](https://github.com/flashingpumpkin/spooky)
* Groovy: [Graffiti](https://github.com/webdevwilson/graffiti)
* Java: [Spark](https://github.com/perwendel/spark) 
* JavaScript: [Express](https://github.com/expressjs/express), [Sammy](https://github.com/quirkey/sammy)
* Julia: [Moresel.jl](https://github.com/JuliaArchive/Morsel.jl)
* Lua: [Mercury](https://github.com/nrk/mercury), [Orbit](http://keplerproject.github.io/orbit/)
* .NET: [Martini](https://github.com/thegrubbsian/Martin), [Nancy](https://github.com/NancyFx/Nancy), [Nina](https://github.com/jondot/Nina)
* Perl: [Dancer](https://github.com/PerlDancer/Dancer2), [Mojolicious](https://github.com/kraih/mojo)
* PHP: [FatFree](https://github.com/bcosca/fatfree), [Fitzgerald](https://github.com/gregmolnar/fitzgerald), [Klein](https://github.com/klein/klein.php),
  [Zaphpa](http://zaphpa.org/)
* Python: [itty](https://github.com/toastdriven/itty), [Flask](https://github.com/pallets/flask)
* Scala: [Finatra](https://github.com/twitter/finatra), [Scalatra](https://github.com/scalatra/scalatra)
* Vala: [Valatra](https://github.com/erik/valatra)

## NoSQL

> Column

* [Sinandra](https://github.com/groupdock/sinandra) - A blog engine using Sinatra and Cassandra.

> Document

* [sinatra-mongo](https://github.com/technicalpickles/sinatra-mongo) - A light extension to sinatra for using mongo.
* [sinatra-mongoid](https://github.com/croaky/sinatra-mongoid) - A Mongoid (ODM, Object-Document-Mapper for MongoDB) extension for Sinatra.

> Key-value

* [redis-sinatra](https://github.com/redis-store/redis-sinatra) - Redis stores for Sinatra.
* [riak-browser](https://github.com/jlambert121/riak-browser) - A simple ruby/Sinatra Riak browser and editor. 

## ORM

* [bowtie](https://github.com/tomas/bowtie) - Simple admin interface generator for MongoMapper (mongo) & DataMapper (dm) models.
* [sinatra-activerecord](https://github.com/janko-m/sinatra-activerecord) - Extends Sinatra with ActiveRecord helper methods and Rake tasks.
* [sinatra-datamapper](https://github.com/jmkeyes/sinatra-datamapper) - A Sinatra extension for DataMapper ORM support.
* [sinatra-sequel](https://github.com/rtomayko/sinatra-sequel) - Sinatra extension that adds Sequel ORM features, database config, and database migrations.

## Routers

* [http_router_sinatra](https://github.com/joshbuddy/http_router_sinatra) - Kick ass router for Sinatra based on http_router.
* [SimpleRouter](http://github.com/mynyml/simple_router) - Small and simple standalone router, meant for 
  use with Rack applications. Familiar Sinatra-like DSL for defining actions. Modular architecture.
* [sinatra-advanced-routes](https://github.com/rkh/sinatra-advanced-routes) - Make Sinatra routes first class objects (extracted from BigBand).
* [sinatra-router](https://github.com/brandur/sinatra-router) - A tiny vendorable router that makes it 
  easy to try routes from a number of different modular Sinatra applications

## Service Integration

> Slack

* [beach](https://github.com/willrax/beach) - Small Sinatra app to host web hooks for Slack.
* [dogetip-slack](https://github.com/tenforwardconsulting/dogetip-slack) - Sinatra app to enable Dogecoin tipping via slack
* [doorbell-server](https://github.com/Lostmyname/doorbell-server) - Simple Sinatra app which acts a bridge between Slack and the LMN doorbell.
* [snarkov](https://github.com/gesteves/snarkov) - Sinatra-based Markov bot for Slack. 

> MISC

* [frankie](https://github.com/deadprogram/frankie) - a Sinatra plugin allows you to easily create a 
  Facebook application.
* [shopify-sinatra-app](https://github.com/kevinhughes27/shopify-sinatra-app) - Lightweight extension for
  building Shopify apps using Sinatra

## Stylesheets

* [sinatra-compass](https://github.com/rkh/sinatra-compass) - Integrates the Compass stylesheet framework with Sinatra.
* [haml-more](https://github.com/rkh/haml-more) - Adds more functionality to Haml and Sass.

## Testing

* [cucumber-sinatra](https://github.com/bernd/cucumber-sinatra) - Help you to initialize a cucumber 
  environment for a sinatra application. It will generate the required files from templates.
* [mumuki-ruby-server](https://github.com/mumuki/mumuki-ruby-server) - Sinatra server for running Rspec
  tests within [Mumuki](https://github.com/mumuki/mumukit). Mumukit is a Test Server Development Kit.
* [mock_server](https://github.com/mvemjsun/mock_server) - A lightweight Sinatra application backed by
   sqlite that can mock ReST responses. Has interface to easily create, search & maintain mocks. 
* [rspec-sinatra](https://github.com/tansaku/rspec-sinatra) - Help you to initialize a RSpec 
  environment for a sinatra application. It will generate the required files from templates.

## Wiki Engine

* [bliki](https://github.com/bomberstudios/bliki) - A small blog + wiki engine built on Sinatra + Stone.
* [git-wiki](https://github.com/sr/git-wiki) - A quick & dirty git-powered Sinatra wiki (~200 LOC).
* [lilwiki](https://gist.github.com/erikpukinskis/363190) - A small wiki backed by sqlite.
* [rikiki](https://github.com/yarmand/rikiki) - Tiny wiki engine using in browser markdown and Sinatra.
* [Weaky](https://github.com/benatkin/weaky) - A basic CouchDB/Sinatra wiki.

## Writing APIs

* [API-mock-server](https://github.com/zlx/API-mock-server) - A Full-Featured API Mock Server built with Sinatra and MongoDB.
* [Pliny](https://github.com/interagent/pliny) - Pliny helps Ruby developers write and maintain excellent APIs.
* [pliny-template](https://github.com/interagent/pliny-template) - Base Sinatra app for writing excellent APIs in Ruby
* [sinatra-hat](https://github.com/nakajima/sinatras-hat) - Easy REST-ful apps with Sinatra. Mount models as web services.
* [sinatra-reset](https://github.com/blindgaenger/sinatra-rest) - Generates RESTful routes for the models of a 
  Sinatra application (ActiveRecord, DataMapper, Stone)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [coopermaa](http://coopermaa2nd.blogspot.tw/) has waived all copyright and related or neighboring rights to this work.