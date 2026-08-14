<div align="center">
  <p>👉 <a href="https://github.com/sponsors/yosriady">Become a sponsor</a></p>
</div>

# Awesome HTTP API Development Tools with stars

## Introduction

This is a collection of useful resources for building RESTful HTTP+JSON APIs. There are a lot of good tools and entire ecosystems out there! It can be overwhelming not knowing what options are available, so you can use this as a reference starting point.

Contributions are most welcome. Categories are also open to suggestions!

## Table of Contents

* [API Specification Languages](#api-specification-languages)
* [API Specification Tools](#api-specification-tools)
* [API Specifications](#api-specifications)
* [API Frameworks](#api-frameworks)
* [API Client Development Tools](#api-client-development-tools)
* [API Documentation](#api-documentation)
* [API Clients](#api-clients)
* [API Debugging and Mocking](#api-debugging-and-mocking)
* [API Design Guides](#api-design-guides)
* [API Publishing](#api-publishing)
* [API Gateways](#api-gateways)
* [API Security](#api-security)
* [API Monitoring](#api-monitoring)
* [API Testing](#api-testing)
* [API Developer Portal](#api-developer-portal)
* [JSON Format Standards](#json-format-standards)
* [Learning Resources](#learning-resources)
* [Blogs](#blogs)
* [References](#references)

## API Specification Languages

* [OpenAPI (formerly known as Swagger)](https://github.com/OAI/OpenAPI-Specification) ⭐ 31,156 | 🐛 121 | 🌐 Markdown | 📅 2026-08-13
* [API Blueprint](https://github.com/apiaryio/api-blueprint) ⚠️ Archived
* [JSON Schema](http://json-schema.org/)
* [RAML](https://raml.org/)

## API Specification Tools

* [OpenAPI DevTools](https://github.com/AndrewWalsh/openapi-devtools) ⭐ 4,304 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-19: Browser extension that generates API specs for any app or website
* [Dredd](https://github.com/apiaryio/dredd) ⚠️ Archived: Validate API documentation written in API Blueprint against its backend implementation.
* [Spectral](https://github.com/stoplightio/spectral) ⭐ 3,179 | 🐛 274 | 🌐 TypeScript | 📅 2026-08-13: Define rulesets to lint YAML or JSON, including OpenAPI 2.x, 3.x and AsyncAPI
* [Swagger Inspector](https://swagger.io/tools/swagger-inspector/): Test and auto-generate OpenAPI documentation for any API.
* [Swagger Editor](http://editor.swagger.io/): An editor for designing Swagger specifications.
* [Swagger Tools and Integrations](https://swagger.io/open-source-integrations/): A list of libraries and frameworks serving the Swagger ecosystem.
* [OpenAPI extension for VS Code](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi):  Visual Studio Code (VS Code) extension that provides support for the OpenAPI Specification.
* [OpenAPI plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor): Jetbrains plugin that provides support for the OpenAPI Specification.
* [API Spec Converter](https://lucybot-inc.github.io/api-spec-converter/): Convert between different API spec formats.
* [Apimatic](https://www.apimatic.io/): Supports API description formats including Swagger, OAI format, RAML, API Blueprint, IO Docs, WADL, Postman Collections and HAR 1.4 and more
* [OpenAPI Definition Designer](https://openapidesigner.com): Free visual OpenAPI3 definition creation and editing tool.
* [Stoplight Studio](https://stoplight.io/studio/): Create, prototype, and share OpenAPI descriptions and JSON Schemas using a visual editor.
* [Optic](https://www.useoptic.com/docs/openapi/generate-from-traffic): Verify the accuracy of your OpenAPI 3.x spec using real traffic, and automatically apply patches that keep it up-to-date
* [RateMyOpenAPI](https://ratemyopenapi.com/): Open-source tools that scans your OpenAPI spec and identifies issues with documentation, security, and SDK generation - and generates a report with fix suggestions.

## API Specifications

* [API Commons](http://apicommons.org/): A repository of language-agnostic API specifications / Data Models.
* [APIS.guru](https://apis.guru/openapi-directory/): Directory of API specs in OpenAPI(aka Swagger) 2.0 format.
* [AnyAPI](https://any-api.com/): Documentation and Test Consoles for Public APIs.

## API Frameworks

### Ruby

* [grape](https://github.com/ruby-grape/grape) ⭐ 9,994 | 🐛 248 | 🌐 Ruby | 📅 2026-08-09: An opinionated micro-framework for creating REST-like APIs in Ruby.
* [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers) ⭐ 5,342 | 🐛 190 | 🌐 Ruby | 📅 2025-12-08: Brings convention over configuration to your JSON generation.
* [rails-api](https://github.com/rails-api/rails-api) ⭐ 5,129 | 🐛 13 | 🌐 Ruby | 📅 2021-05-02: Rails for API only applications.
* [jbuilder](https://github.com/rails/jbuilder) ⭐ 4,420 | 🐛 45 | 🌐 Ruby | 📅 2026-06-01: Create JSON structures via a Builder-style DSL.
* [rabl](https://github.com/nesquena/rabl) ⭐ 3,634 | 🐛 122 | 🌐 Ruby | 📅 2026-03-18: Generate JSON and XML from any ruby object.
* [roar](https://github.com/trailblazer/roar) ⭐ 1,840 | 🐛 18 | 🌐 Ruby | 📅 2023-01-17: Parse and render REST API documents using representers.
* [pliny](https://github.com/interagent/pliny) ⭐ 806 | 🐛 20 | 🌐 Ruby | 📅 2026-04-29: Opinionated template Sinatra app for writing APIs in Ruby.

### Python

* [FastAPI](https://github.com/tiangolo/fastapi) ⭐ 101,605 | 🐛 73 | 🌐 Python | 📅 2026-08-14: FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
* [sanic](https://github.com/channelcat/sanic) ⭐ 18,646 | 🐛 144 | 🌐 Python | 📅 2026-07-29: Sanic is a Flask-like Python 3.5+ web server that's written to go fast.
* [Falcon](https://github.com/falconry/falcon) ⭐ 9,796 | 🐛 159 | 🌐 Python | 📅 2026-07-31: Falcon is a low-level, high-performance Python framework for building HTTP APIs, app backends, and higher-level frameworks.
* [flask-restful](https://github.com/flask-restful/flask-restful) ⭐ 6,916 | 🐛 146 | 🌐 Python | 📅 2024-07-19: Simple framework for creating REST APIs.
* [hug](https://github.com/timothycrosley/hug) ⭐ 6,884 | 🐛 188 | 🌐 Python | 📅 2024-07-04: hug aims to make developing Python driven APIs as simple as possible, but no simpler.
* [apistar](https://github.com/encode/apistar) ⚠️ Archived: A smart Web API framework, designed for Python3.
* [Connexion](https://github.com/zalando/connexion) ⭐ 4,608 | 🐛 185 | 🌐 Python | 📅 2026-08-03: Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation and OAuth2 support
* [Tastypie](https://github.com/django-tastypie/django-tastypie) ⭐ 3,948 | 🐛 411 | 🌐 Python | 📅 2026-07-27: Webservice API framework for Django.
* [restless](https://github.com/toastdriven/restless) ⭐ 823 | 🐛 32 | 🌐 Python | 📅 2024-08-15: A lightweight REST miniframework for Python.
* [Django REST framework](http://www.django-rest-framework.org/): Toolkit that makes it easy to build Web APIs.

### Javascript

* [Nest](https://github.com/kamilmysliwiec/nest) ⭐ 76,373 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-14: A modern node.js framework for efficient and scalable web applications built on top of TypeScript
* [Restify](https://github.com/restify/node-restify) ⭐ 10,687 | 🐛 132 | 🌐 JavaScript | 📅 2026-08-13: Node.js REST framework specifically meant for web service APIs.
* [Deployd](https://github.com/deployd/deployd) ⭐ 4,940 | 🐛 135 | 🌐 JavaScript | 📅 2019-04-16: Deployd is the simplest way to build realtime APIs for web and mobile apps
* [hapi.js](https://hapijs.com/): Web and services application framework for Node.js.
* [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
* [sailsjs](http://sailsjs.org/): Realtime MVC Framework for Node.js.
* [Actionhero](https://www.actionherojs.com/): Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
* [Baucis](https://github.com/wprl/baucis): To build
* [Koa](http://koajs.com/): Next generation web framework for Node.js
* [Loopback](http://loopback.io/): Node.js framework for creating APIs and easily connecting to backend data sources.
* [Seneca](http://senecajs.org/): A microservices toolkit for Node.js.
* [Feathers](https://feathersjs.com/): Build RESTful and real-time APIs through Socket.io or Primus.

### Go

* [Fiber](https://github.com/gofiber/fiber) ⭐ 40,066 | 🐛 51 | 🌐 Go | 📅 2026-08-14: :zap:Fiber is an Express inspired web framework written in Go with :coffee: .
* [go-restful](https://github.com/emicklei/go-restful) ⭐ 5,116 | 🐛 2 | 🌐 Go | 📅 2026-07-05: A declarative highly readable framework for building restful API's.
* [Go-Json-Rest](https://github.com/ant0ine/go-json-rest) ⭐ 3,486 | 🐛 45 | 🌐 Go | 📅 2021-01-23: Thin layer on top of `net/http` that helps building RESTful APIs easily
* [sleepy](https://github.com/dougblack/sleepy) ⭐ 669 | 🐛 10 | 🌐 Go | 📅 2017-11-26: RESTful micro-framework written in Go.
* [gocrud](https://github.com/manishrjain/gocrud) ⭐ 307 | 🐛 7 | 🌐 Go | 📅 2019-03-01: Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
* [go-relax](https://github.com/codehack/go-relax) ⭐ 153 | 🐛 0 | 🌐 Go | 📅 2026-02-14: Framework of pluggable components to build RESTful API's.
* [go-rest](https://github.com/ungerik/go-rest) ⭐ 128 | 🐛 2 | 🌐 Go | 📅 2017-01-20: Small and evil REST framework for Go.
* [restit](https://github.com/go-restit/restit) ⭐ 56 | 🐛 6 | 🌐 Go | 📅 2026-07-02: Go micro framework to help writing RESTful API integration test.
* [Resoursea](https://github.com/resoursea/api) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2015-02-01: REST framework for quickly writing resource based services.
* [Goat](https://github.com/bahlo/goat): Minimalistic REST API server in Go.
* [Zerver](https://github.com/cosiner/zerver): Zerver is a expressive, modular, feature completed RESTful framework.

### Scala

* [Akka HTTP](https://github.com/akka/akka-http) ⭐ 1,350 | 🐛 580 | 🌐 Scala | 📅 2026-08-12: The Akka HTTP modules implement a full server- and client-side HTTP stack on top of akka-actor and akka-stream.
* [Colossus](https://github.com/tumblr/colossus) ⭐ 1,129 | 🐛 4 | 🌐 Scala | 📅 2021-08-14: I/O and microservice library for Scala.
* [Swagger Akka HTTP](https://github.com/swagger-akka-http/swagger-akka-http) ⭐ 277 | 🐛 15 | 🌐 Scala | 📅 2023-10-17: Swagger-Akka-Http brings Swagger support for Akka-Http Apis.
* [Skinny Micro](https://github.com/skinny-framework/skinny-micro) ⭐ 60 | 🐛 4 | 🌐 Scala | 📅 2022-03-13: Micro-web framework to build servlet applications in Scala.
* [Finatra](https://twitter.github.io/finatra/): Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
* [Play](https://www.playframework.com/): The high velocity web framework for Java and Scala.
* [Scalatra](http://www.scalatra.org/): Simple, accessible and free web micro-framework.
* [Spray](http://spray.io/): Open-source toolkit for building REST/HTTP-based integration layers on top of Scala and Akka.

### Java

* [Rest.li](http://rest.li/): REST framework using type-safe bindings and asynchronous, non-blocking IO.
* [Dropwizard](https://www.dropwizard.io/en/latest/): Framework for developing ops-friendly, high-performance, RESTful web services.
* [Jersey](https://jersey.java.net/): RESTful web services in Java.
* [Spring Boot](https://projects.spring.io/spring-boot/): RESTful Web Service using Spring, high-performance and little configuration needed.
* [Metamug Mason](https://github.com/metamug/mason) ⭐ 27 | 🐛 68 | 🌐 Java | 📅 2023-04-14: Create REST APIs with JSP tags and SQL. Edit and hot deploy REST resources on the server.

### Haskell

* [Yesod](https://github.com/yesodweb/yesod) ⭐ 2,720 | 🐛 132 | 🌐 Haskell | 📅 2026-07-29: The Haskell RESTful web framework.
* [Servant](https://github.com/haskell-servant/servant) ⭐ 1,967 | 🐛 298 | 🌐 Haskell | 📅 2026-08-10: A Type-Level Web DSL.
* [Scotty](https://github.com/scotty-web/scotty) ⭐ 1,775 | 🐛 29 | 🌐 Haskell | 📅 2026-06-26: Micro web framework inspired by Ruby's Sinatra, using WAI and Warp.
* [Spock](https://github.com/agrafix/Spock) ⭐ 679 | 🐛 32 | 🌐 Haskell | 📅 2024-04-08: Another Haskell web framework for rapid development.

### Elixir

* [Phoenix](http://phoenixframework.org/): Framework for building HTML5 apps, API backends and distributed systems.
* [Plug](https://github.com/elixir-plug/plug) ⭐ 3,012 | 🐛 4 | 🌐 Elixir | 📅 2026-08-13: A specification and conveniences for composable modules between web applications.

### Erlang

* [Cowboy](https://github.com/ninenines/cowboy) ⭐ 7,523 | 🐛 63 | 🌐 Erlang | 📅 2026-07-28: Small, fast, modular HTTP server written in Erlang.
* [Mochiweb](https://github.com/mochi/mochiweb) ⭐ 1,890 | 🐛 11 | 🌐 Erlang | 📅 2026-08-10: Erlang library for building lightweight HTTP servers.
* [Gen Microservice](https://github.com/videlalvaro/gen_microservice) ⭐ 94 | 🐛 2 | 🌐 Erlang | 📅 2015-05-14: This library solves the problem of implementing microservices with Erlang.

### Postgres

* [PostgREST](https://github.com/begriffs/postgrest) ⭐ 27,597 | 🐛 388 | 🌐 Haskell | 📅 2026-08-13: Serve a RESTful API from any existing PostgreSQL database.
* [pREST](https://github.com/prest/prest) ⭐ 4,609 | 🐛 151 | 🌐 Go | 📅 2026-08-14: pREST is a way to serve a RESTful API from any databases written in Go.

### MySQL

* [xmysql](https://github.com/o1lab/xmysql) ⭐ 193 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-01: Generate REST APIs for any MySQL Database.

### PHP

* [Yii2 Framework](https://github.com/yiisoft/yii2) ⭐ 14,301 | 🐛 318 | 🌐 PHP | 📅 2026-08-13: Provides a whole set of tools to simplify the task of implementing RESTful Web Service APIs
* [Dingo API](https://github.com/dingo/api) ⭐ 9,364 | 🐛 189 | 🌐 PHP | 📅 2022-05-19: A RESTful API package for the Laravel and Lumen frameworks
* [API Platform](https://github.com/api-platform/api-platform) ⭐ 9,175 | 🐛 11 | 🌐 PHP | 📅 2026-08-01: API framework on top of Symfony with JSON-LD, Schema.org and Hydra support
* [Fractal](https://github.com/thephpleague/fractal) ⭐ 3,545 | 🐛 54 | 🌐 PHP | 📅 2025-12-16: Fractal provides a presentation and transformation layer for complex data output, the like found in RESTful APIs, and works really well with JSON

### R

* [Plumber](https://www.rplumber.io/): API Framework to build APIs for simple R Functions

### C\#

* [ASP.NET Web APIs](https://dotnet.microsoft.com/en-us/apps/aspnet/apis): Build secure REST APIs on any platform with C#

### Miscellaneous

* [Dream Factory](https://github.com/dreamfactorysoftware/dreamfactory) ⭐ 1,778 | 🐛 65 | 🌐 Shell | 📅 2026-08-13: Turn any database into an API platform.

## API Client Development Tools

### General

* [OpenAPI Generator](https://github.com/openapitools/openapi-generator) ⭐ 26,670 | 🐛 5,706 | 🌐 Java | 📅 2026-08-14: A community fork of Swagger Codegen to automatically generate API clients, server stubs and documentation for REST APIs given an OpenAPI/Swagger spec.
* [Swagger CodeGen](https://github.com/swagger-api/swagger-codegen) ⭐ 17,778 | 🐛 3,447 | 🌐 Mustache | 📅 2026-08-04: Generate client libraries automatically from a Swagger-compliant server.
* [AutoRest](https://github.com/Azure/autorest) ⭐ 4,799 | 🐛 22 | 🌐 TypeSpec | 📅 2026-08-12: Generate client libraries for RESTful web services

### Ruby

* [faraday](https://github.com/lostisland/faraday) ⭐ 5,948 | 🐛 63 | 🌐 Ruby | 📅 2026-08-12: Simple, but flexible HTTP client library, with support for multiple backends.
* [rest-client](https://github.com/rest-client/rest-client) ⭐ 5,214 | 🐛 140 | 🌐 Ruby | 📅 2024-05-19: Simple HTTP and REST client for Ruby
* [nestful](https://github.com/maccman/nestful) ⭐ 505 | 🐛 11 | 🌐 Ruby | 📅 2021-08-30: Ruby HTTP/REST client.
* [blanket](https://github.com/inf0rmer/blanket) ⭐ 459 | 🐛 8 | 🌐 Ruby | 📅 2022-02-25: A Ruby API wrapper.
* [heroics](https://github.com/interagent/heroics) ⭐ 413 | 🐛 8 | 🌐 Ruby | 📅 2026-06-04: Ruby HTTP client for APIs represented with JSON schema.
* [Net::HTTP](https://apidock.com/ruby/Net/HTTP): An HTTP client API for Ruby.

### Java

* [Retrofit](https://square.github.io/retrofit/): A type-safe HTTP client for Android and Java.

### Javascript

* [Restangular](https://github.com/mgonto/restangular) ⭐ 7,792 | 🐛 253 | 🌐 JavaScript | 📅 2020-10-05: Restangular is an AngularJS service that simplifies common GET, POST, DELETE, and UPDATE requests with a minimum of client code

### .NET

* [WebAnchor](https://github.com/mattiasnordqvist/Web-Anchor) ⭐ 25 | 🐛 22 | 🌐 C# | 📅 2025-08-15: Web Anchor provides type-safe, testable and flexible access to web resources.
* [Refit](https://github.com/paulcbetts/refit) ⭐ 0 | 🐛 0 | 📅 2025-08-09: The automatic type-safe REST library for .NET Core, Xamarin and .NET

### .Dart

* [Frog](https://dartfrog.vgv.dev/docs/overview): Dart Frog is built on top of shelf and mason and is inspired by many tools including remix.run, next.js, and express.js.
* [Serverpod](https://github.com/serverpod/serverpod) ⭐ 3,242 | 🐛 496 | 🌐 Dart | 📅 2026-08-14: Serverpod is a next-generation app and web server, built for the Flutter community. It allows you to write your server-side code in Dart, automatically generate your APIs, and hook up your database with minimal effort. Serverpod is open-source, and you can host your server anywhere.

## API Documentation

* [Slate](https://github.com/lord/slate) ⚠️ Archived: Static site generated documentation for your API.
* [Swagger UI](https://github.com/swagger-api/swagger-ui) ⭐ 28,972 | 🐛 1,431 | 🌐 JavaScript | 📅 2026-08-13: Dynamically generate documentation from a Swagger-compliant API.
* [ReDoc](https://github.com/Rebilly/ReDoc) ⭐ 25,877 | 🐛 451 | 🌐 TypeScript | 📅 2026-08-11: OpenAPI/Swagger-generated API Reference Documentation.
* [Aglio](https://github.com/danielgtaylor/aglio) ⭐ 4,748 | 🐛 135 | 🌐 CoffeeScript | 📅 2019-05-13: An API Blueprint renderer with theme support that outputs static HTML.
* [Elements](https://github.com/stoplightio/elements) ⭐ 2,450 | 🐛 271 | 🌐 TypeScript | 📅 2026-08-12: Web Components-based API documentation for OpenAPI 3.x/2.x
* [prmd](https://github.com/interagent/prmd) ⭐ 2,089 | 🐛 75 | 🌐 Ruby | 📅 2025-02-06: JSON Schema tooling: scaffold, verify, and generate documentation from JSON Schema documents.
* [widdershins](https://github.com/Mermade/widdershins) ⭐ 1,581 | 🐛 89 | 🌐 JavaScript | 📅 2024-06-04: REST API documentation generator from OpenAPI 3.0 / Swagger 2.0 / AsyncAPI 1.x / Semoasa 0.1.0 definition
* [Docbox](https://github.com/tmcw/docbox) ⭐ 1,131 | 🐛 6 | 🌐 CSS | 📅 2020-04-21: REST API documentation generator, using Markdown.
* [DeveloperHub](https://developerhub.io/): Documentation tool to write, publish, review, analyse and collect feedback on personalised customer-facing API docs.
* [Apiary](https://apiary.io/): Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
* [Readme](https://readme.io/): API Documentation Hosting.
* [API Docs](https://api-docs.io/): Hosted public API documentation for OAS (Swagger) and RAML specs.

## API Clients

### Open Source

* [Hoppscotch](https://github.com/hoppscotch/hoppscotch) ⭐ 80,028 | 🐛 785 | 🌐 TypeScript | 📅 2026-08-05: API client for REST, GraphQL, Websocket, SSE, Socket.IO and MQTT
* [Hurl](https://github.com/Orange-OpenSource/hurl) ⭐ 19,144 | 🐛 205 | 🌐 Rust | 📅 2026-08-14: Hurl makes it easy to work with HTML content, REST / SOAP / GraphQL APIs, or any other XML / JSON based APIs.
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,696 | 🐛 20 | 🌐 Rust | 📅 2026-03-09: A feature-full TUI API client made in Rust. ATAC is free, open-source, offline and account-less.

### Hosted

* [JSON Generator](http://www.json-generator.com/): Generate and host mock JSON data.

### Desktop

* [Postman](https://www.getpostman.com): Desktop API testing tool.
* [Firecamp](https://firecamp.app): API Studio for WebSocket, Rest API and GraphQL.
* [HTTPie](https://httpie.org/): Command line HTTP client.
* [Paw](https://paw.cloud/): REST client for Mac.
* [Insomnia](https://insomnia.rest/): REST API client for Mac, Windows, and Linux.
* [httpy](https://github.com/knid/httpy) ⭐ 25 | 🐛 3 | 🌐 Python | 📅 2023-07-05: Programmable Command line HTTP client.

## API Debugging and Mocking

### Hosted

* [Beeceptor](https://beeceptor.com): An HTTP-proxy for rest APIs - inspect and build mock APIs.
* [MockBin](https://mockbin.com/): Generate mock HTTP endpoints.
* [httpbin](http://httpbin.org): Templated responses for testing various scenarios for HTTP requests.
* [Prism](https://github.com/stoplightio/prism) ⭐ 5,004 | 🐛 148 | 🌐 TypeScript | 📅 2026-08-13: a set of packages for API mocking and contract testing with OpenAPI v2 (formerly known as Swagger) and OpenAPI v3.x, including mock servers and a validation proxy.
* [MockingCloud](https://mockingcloud.com): Generate full mock REST APIs with just OpenAPI yaml/json spec files.
* [Svix Play](https://www.svix.com/play/): Easily inspect, test, and debug incoming webhooks.

### Desktop

* [Postman](https://www.getpostman.com/docs/postman/mock_servers/setting_up_mock): Desktop API client and mocking tool.
* [Json-Server](https://github.com/typicode/json-server) ⭐ 75,701 | 🐛 720 | 🌐 JavaScript | 📅 2026-03-23 Full fake REST API with zero coding.
* [Mockoon](https://mockoon.com): Desktop API mocking tool.

## API Design Guides

* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md) ⭐ 23,318 | 🐛 176 | 📅 2026-08-05
* [Heroku Platform HTTP API Design Guide](https://github.com/interagent/http-api-design) ⭐ 13,686 | 🐛 30 | 📅 2024-01-16
* [White House Web API Standards](https://github.com/whitehouse/api-standards) ⚠️ Archived
* [18F API Standards](https://github.com/18f/api-standards) ⚠️ Archived
* [Adidas-group API Design Guide](https://github.com/adidas-group/api-guidelines) ⭐ 404 | 🐛 1 | 📅 2025-09-19
* [Google API Design Guide](https://cloud.google.com/apis/design/)
* [Haufe API Style Guide](http://work.haufegroup.io/api-style-guide/)
* [The RESTed NARWHL](https://www.narwhl.com/)
* [Zalando REST API Guidelines](https://zalando.github.io/restful-api-guidelines/)
* [API Stylebook Design Guidelines](http://apistylebook.com/design/guidelines/)
* [API Stylebook Design Topics](http://apistylebook.com/design/topics/)
* [Azure API Design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## API Publishing

* [Mashape](https://www.mashape.com/): API Marketplace.

## API Gateways

* [Traefik](https://github.com/containous/traefik) ⭐ 64,468 | 🐛 892 | 🌐 Go | 📅 2026-08-13: Træfik (pronounced like traffic) is a modern HTTP reverse proxy and load balancer written in Go.
* [Zuul](https://github.com/Netflix/zuul) ⭐ 14,060 | 🐛 12 | 🌐 Java | 📅 2026-08-12: An edge service that provides dynamic routing, monitoring, resiliency, security, and more.
* [fabio](https://github.com/fabiolb/fabio) ⭐ 7,333 | 🐛 241 | 🌐 Go | 📅 2026-08-11: A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by [consul](https://www.consul.io) by eBay.
* [Oathkeeper](https://github.com/ory/oathkeeper) ⭐ 3,593 | 🐛 106 | 🌐 Go | 📅 2026-07-27: OIdentity & Access Proxy (IAP) that authorizes HTTP requests based on sets of rules. Integrates with ORY Hydra.
* [Vulcand](https://github.com/vulcand/vulcand) ⭐ 3,092 | 🐛 71 | 🌐 Go | 📅 2024-07-27: Programmatic load balancer backed by Etcd.
* [Strongloop](https://github.com/strongloop/microgateway) ⭐ 1,185 | 🐛 44 | 🌐 JavaScript | 📅 2019-11-05: nodejs based API Gateway
* [Apigee127](https://github.com/apigee-127/a127-documentation/wiki/What-is-Apigee-127) ⚠️ Archived: nodejs based API Gateway
* [AWS API Gateway](https://aws.amazon.com/api-gateway/): Traffic management, authorization and access control, monitoring, and API version management.
* [Ambassador API Gateway](https://www.getambassador.io/): Ambassador is a specialized control plane that translates Kubernetes annotations to Envoy configuration. All traffic is directly handled by the high-performance Envoy Proxy.
* [APIGrove](https://apigrove.github.io/apigrove/): API manager built in Java on top of Fuse ESB.
* [APISIX](https://apisix.apache.org/): Open Source and Cloud-Native API gateway, based on the Nginx library and etcd.
* [Pushpin](http://pushpin.org): Proxy for both request/response or streaming (long poll) of responses
* [Fusio](http://www.fusio-project.org/): PHP based open source API management platform
* [Camel](https://camel.apache.org/): Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
* [HAProxy](http://www.haproxy.org/): Reliable, high Performance TCP/HTTP load balancer.
* [OpenResty](https://openresty.org/): Fast web application server built on top of Nginx.
* [Tengine](http://tengine.taobao.org/): A distribution of Nginx with some advanced features.
* [Tyk](https://tyk.io/): Open-source, fast and scalable API gateway, portal and API management platform.
* [Kong](https://getkong.org/): An open-source management layer for APIs, delivering high performance and reliability.
* [Janus](https://github.com/hellofresh/janus): A lightweight API Gateway written in Go by [Hello Fresh](https://engineering.hellofresh.com).
* [Zuplo](https://zuplo.com/): OpenAPI-Powered API Management platform for API Development, Deployment, and Documentation. Add auth, rate-limiting, and monetization to your API in minutes.

## API Security

* [API Security checklist](https://github.com/shieldfy/API-Security-Checklist) ⭐ 23,300 | 🐛 2 | 📅 2026-07-21: Checklist of the most important security countermeasures when designing, testing, and releasing your API.
* [Ory Hydra](https://github.com/ory/hydra) ⭐ 17,476 | 🐛 93 | 🌐 Go | 📅 2026-07-29: OAuth2 server with OpenID Connect written in Go.
* [Online OpenAPI/Swagger File Security Audit](https://apisecurity.io/tools/audit/): Free online static analysis of API contract files. Upload the file and get the report.

## API Web Scanners

* [Cherrybomb](https://github.com/blst-security/cherrybomb) ⭐ 1,233 | 🐛 38 | 🌐 Rust | 📅 2024-10-25: Stop half-done API specifications! Cherrybomb is a CLI tool that helps you avoid undefined user behaviour by validating your API specifications.

## API Monitoring

* [Runscope](https://www.runscope.com/): API Performance Monitoring.
* [Ping-API](https://ping-api.com/): Automated API Testing.
* [Streamdal](https://streamdal.com): A tool to embed privacy controls in your application code to detect PII as it enters and leaves your systems, preventing it from reaching unintended APIs, databases, data streams, or pipelines.

## API Testing

* [Hurl](https://github.com/Orange-OpenSource/hurl) ⭐ 19,144 | 🐛 205 | 🌐 Rust | 📅 2026-08-14: Hurl makes it easy to test HTML content, REST / SOAP / GraphQL APIs, or any other XML / JSON based APIs.
* [OWASP Zaproxy](https://github.com/zaproxy/zaproxy) ⭐ 15,599 | 🐛 854 | 🌐 Java | 📅 2026-08-13: A tool to test your API for known security vulnerabilities, with a great CI integration.
* [Pyresttest](https://github.com/svanoort/pyresttest) ⭐ 1,165 | 🐛 132 | 🌐 Python | 📅 2021-06-10: YAML based REST testing and API microbenchmarking tool
* [RestQA](https://github.com/restqa/restqa) ⭐ 93 | 🐛 18 | 🌐 JavaScript | 📅 2024-09-13: Microservice API Testing tool focused on providing a great developer experience.
* [Assertible](https://assertible.com): Continuously test and monitor your APIs after deployments and across environments.
* [Optic CI](https://www.useoptic.com/docs/diff-openapi): Test for breaking API changes in CI Pipelines

## API Developer Portal

* [Tyk](https://tyk.io/features): API Developer Portal on top of API gateway, make your API gateway easier to be used by developers.
* [APIMATIC](https://apimatic.io/developer-experience-portal): Instantly build an API Portal with SDKs, Live Code Samples, Test Cases, API Transformation and language specific Docs & Reference - tailored for your API.
* [Optic Docs](https://www.useoptic.com): Share verified-accurate OpenAPI documentation with your consumers. With Optic they can subscribe to your API and get notified when it changes.
* [Zuplo](https://zuplo.com/): OpenAPI-Powered API Management platform for API Development, Deployment, and Documentation. Zuplo's Developer Portal integrates key-management, usage analytics, and monetization for free.

## JSON Format Standards

* [HAL](http://stateless.co/hal_specification.html)
* [JSONAPI](http://jsonapi.org/faq/)
* [JSON Schema](http://json-schema.org/)
* [Hydra](http://www.hydra-cg.com/)
* [Ion](https://github.com/ionwg/ion-doc) ⭐ 50 | 🐛 13 | 🌐 CSS | 📅 2018-05-29
* [JSON-LD](https://json-ld.org/)

## Learning Resources

* [REST in Practice](http://shop.oreilly.com/product/9780596805838.do)
* [Roy Fielding's dissertation on REST](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to Design a REST API](https://blog.octo.com/en/design-a-rest-api/)
* [Automated API Development](https://yos.io/2016/04/27/automated-api-development/)
* [Nordic APIs](http://nordicapis.com/)
* [Undisturbed REST](https://www.mulesoft.com/sites/default/files/resource-assets/ebook-UndisturbedREST_v1.pdf)
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate)
* [Irresistible APIs](https://www.manning.com/books/irresistible-apis)
* [How to build an API](https://apiary.io/how-to-build-api)
* [API University](https://www.programmableweb.com/api-university)
* [RESTful Web Services](http://shop.oreilly.com/product/9780596529260.do)
* [RESTful Web APIs](http://shop.oreilly.com/product/0636920028468.do)
* [The Ten Essentials for Good API Documentation](https://alistapart.com/article/the-ten-essentials-for-good-api-documentation)
* [APIsecurity.io weekly newsletter](https://apisecurity.io)
* [Testing Web APIs](https://www.manning.com/books/testing-web-apis)
* [The Design of Web APIs, Second Edition](https://www.manning.com/books/the-design-of-web-apis-second-edition)

## Blogs

* [API Evangelist](http://apievangelist.com/blog/)

## References

* [HTTP Status Codes Reference](https://httpstatuses.com/)

## Contributing

[Pull Requests](https://github.com/yosriady/api-development-tools/pulls) ⭐ 4,016 | 🐛 43 | 📅 2025-12-20 are most welcome!

Please write a brief one-sentence summary when adding a new resource.

## Thanks

**api-development-tools** © 2016+, Yos Riady. Released under the [MIT] License.<br>
Authored and maintained by Yos Riady with help from contributors ([list][contributors]).

> [yos.io](https://yos.io)  · 
> GitHub [@yosriady](https://github.com/yosriady)

[MIT]: https://mit-license.org/

[contributors]: https://github.com/yosriady/api-development-tools/contributors

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
