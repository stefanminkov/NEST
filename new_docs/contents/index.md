---
template: index.jade
title: Introduction
menusection: concepts
menuitem: introduction
---

# Introduction

You've reached the documentation page for `Elasticsearch.Net` and `NEST`. Two .net clients to talk with Elasticsearch. So why two clients I hear you say?

`Elasticsearch.Net` is a very low level, dependency free, client that has no opinions how you build and represent your requests and responses. It has abstracted 
enough so that **all** the elasticsearch API endpoints are represented as methods but not too much to get in the way of how you want to build your json/request/response objects. It also comes with builtin, configurable/overridable, cluster failover retry mechanisms. Elasticsearch is elastic so why not your client?

`NEST` is a high level client that has the advantage of having mapped all the request and response objects, comes with a strongly typed query DSL that maps 1 to 1 with the elasitcsearch query dsl and takes advantage of specific .net features such as covariant results. NEST internally uses, and still exposes, the low level `Elasticsearch.Net` client

Please read the getting started guide for both.


## Who's using Nest
* [stackoverflow.com](http://www.stackoverflow.com) (and the rest of the stackexchange family).
* [7digital.com](http://www.7digital.com) (run NEST on mono).
* [rijksmuseum.nl](https://www.rijksmuseum.nl/en) (Elasticsearch is the only datastorage hit for each page).
* [Kiln](http://www.fogcreek.com/kiln/) FogCreek's version control & code review tooling. 
  They are so pleased with Elasticsearch that [they made a video about how pleased they are!](http://blog.fogcreek.com/kiln-powered-by-elasticsearch/)


## Other resources

[@joelabrahamsson](http://twitter.com/joelabrahamsson) wrote a great [intro into elasticsearch on .NET](http://joelabrahamsson.com/entry/extending-aspnet-mvc-music-store-with-elasticsearch)
using NEST. 

Also checkout the [searchbox.io guys](https://searchbox.io/) rocking NEST [on AppHarbor](http://blog.appharbor.com/2012/06/19/searchbox-elasticsearch-is-now-an-add-on) 
with their [demo project](https://github.com/searchbox-io/.net-sample)

## Questions, bugs, comments, requests

All of these are more then welcome on the github issues pages! I try to to at least reply within the same day.

I also monitor question tagged with ['nest' on stackoverflow](http://stackoverflow.com/questions/tagged/nest) or 
['elasticsearch-net' on stackoverflow](http://stackoverflow.com/questions/tagged/elasticsearch-net)


## License

This software is licensed under the Apache 2 license, quoted below.

    Copyright (c) 2014 Elasticsearch <http://www.elasticsearch.org>

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


