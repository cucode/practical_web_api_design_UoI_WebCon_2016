# [Practical Web API Design Workshop](http://webcon.illinois.edu/sessions.shtml)

[University of Illinois WebCon April 27th 2016](http://webcon.illinois.edu/)

Wes Cravens (@WesCravens), Marty Kane (@martinekane), Aaron Lee(@wwkeyboard) & John McCaffrey(@j_mccaffrey)

## Synopsis

Web based APIs have emerged as the defacto standard for powering our
applications across several clients.  We use our Web APIs to power our
mobile platform applications, our browser client applications,
automation systems, b2b exchanges and much more.  There is a surge of
business logic moving from behind closed curtains out into the World
Wide Web where it can be leveraged and consumed in unimaginable ways.
Some go as far as to suggest that the 'API Economy' is the new frontier
in the Information Age.

This workshop will outline the most practical strategies and
technologies that we should consider while designing and building our
APIs.  Know to what extent you should consider the original Fielding
constraints (RESTful design) and know when to make trade-offs.  You're
main goal should be to build a successful and consumer friendly API that
is still flexible and change tolerant.  We'll explore practical answers
to these difficult decisions.

### Topics

  + Overview of the Fielding Constraints
  + Modeling your problem domain
  + Hypermedia as the Expression of Application State (HATEOS)
  + What is a resource?  Good endpoint design
  + HTTP Verbs - The reality
  + Value flexibility and consumption over perfection. Why 'perfection' is unrealistic?


**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Required Tooling](#required-tooling)
  - [Infrastructure Tools](#infrastructure-tools)
  - [Workshop Tools](#workshop-tools)
- [Workshop agenda and timetable](#workshop-agenda-and-timetable)
- [Seating and assistance with Tool installation](#seating-and-assistance-with-tool-installation)
- [Greetings and Introduction to the Workshop (WC)](#greetings-and-introduction-to-the-workshop-wc)
- [Why HTTP APIs are Valuable & The Core Components of an API (JM)](#why-http-apis-are-valuable-&-the-core-components-of-an-api-jm)
  - [Exercise 1 - Explore Aspects of a Few Popular APIs](#exercise-1---explore-aspects-of-a-few-popular-apis)
- [The anatomy of an API Call and Demo of Postman (JM)](#the-anatomy-of-an-api-call-and-demo-of-postman-jm)
  - [Exercise 2 - Test and Explore APIs with Postman](#exercise-2---test-and-explore-apis-with-postman)
- [The Components of an HTTP API Domain (JM)](#the-components-of-an-http-api-domain-jm)
  - [Exercise 3 - Convert the Resources of your Domain into an API](#exercise-3---convert-the-resources-of-your-domain-into-an-api)
  - [Exercise 4 - Swap APIs with an other Group for them to Review](#exercise-4---swap-apis-with-an-other-group-for-them-to-review)
  - [Exercise 5 - Bring Groups Together to Discuss the APIs](#exercise-5---bring-groups-together-to-discuss-the-apis)
- [Documentation and the Open API Specification (MK)](#documentation-and-the-open-api-specification-mk)
  - [Exercise 6 - Specify, Serve and Explore your API](#exercise-6---specify-serve-and-explore-your-api)
- [Good Design: Avoild Perfection Paralysis and Malcontents (WC)](#good-design-avoild-perfection-paralysis-and-malcontents-wc)
- [Wrap up, Q&A](#wrap-up-q&a)
- [References](#references)
  - [Workshop Documentation](#workshop-documentation)
  - [Tools, Services and Specification](#tools-services-and-specification)
  - [Talks, Papers, Periodicals & Blogs](#talks-papers-periodicals-&-blogs)
  - [Books & Documentation](#books-&-documentation)
  - [Example & Refrence APIs](#example-&-refrence-apis)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Required Tooling

Our workshop is designed to leverage tools that you can use online with
a browser any time.  However we've all been to conferences before, so we
know that it's wise to not be 100% reliant on a functional internet
connection espectially if you're asking 60 people to download and
install tooling before hand.  So with that in mind we've also chosen
tools that can be used offline using simple local webservers that can
run on our laptops.

Installing these items before the workshop will help us all support each
other in the event that there are any network connection discrepancies
during our workshop.

### Infrastructure Tools

  + [Chrome](https://www.google.com/chrome/browser/desktop/index.html) Google's Browser
  + [Git](https://git-scm.com/downloads) Very popular version control system
  + [Node.js](https://nodejs.org/en/)

### Workshop Tools

  + [This repository](https://github.com/cucode/practical_web_api_design_UoI_WebCon_2016)
  + [Postman](http://www.getpostman.com/) We'll be using the Chrome plugin version.
  + [Gitter](https://gitter.im/cucode/practical_web_api_design_UoI_WebCon_2016) We'll use this for real time chat.
  + [Getting Started Guide]


## Workshop agenda and timetable

  +  8:45 -  9:00 Seating and assistance with Tool installation

  +  9:00 -  9:05 Greetings and Introduction to the Workshop

  +  9:05 -  9:20 Why HTTP APIs are Valuable & The Core Components of an API

  +  9:20 -  9:30 Exercise 1 - Explore Aspects of a Few Popular APIs

  +  9:30 -  9:40 The anatomy of an API Call and Demo of Postman

  +  9:40 - 10:00 Exercise 2 - Test and Explore APIs with Postman

  + 10:00 - 10:15 The Components of an HTTP API Domain

  + 10:15 - 10:35 Exercise 3 - Convert the Resources of your Domain into an API

  + 10:35 - 10:45 Break

  + 10:45 - 11:00 Exercise 4 - Swap APIs with an other Group for them to Review

  + 11:00 - 11:10 Exercise 5 - Bring Groups Together to Discuss the APIs

  + 11:10 - 11:15 Documentation and the Open API Specification

  + 11:15 - 11:35 Exercise 6 - Specify, Serve and Explore your API

  + 11:35 - 11:45 Good Design: Avoild Perfection Paralysis and Malcontents

  + 11:45 - 12:00 Wrap up, Q&A

## Seating and assistance with Tool installation

## Greetings and Introduction to the Workshop (WC)

## Why HTTP APIs are Valuable & The Core Components of an API (JM)

### Exercise 1 - Explore Aspects of a Few Popular APIs

## The anatomy of an API Call and Demo of Postman (JM)

### Exercise 2 - Test and Explore APIs with Postman

## The Components of an HTTP API Domain (JM)

### Exercise 3 - Convert the Resources of your Domain into an API

### Exercise 4 - Swap APIs with an other Group for them to Review

### Exercise 5 - Bring Groups Together to Discuss the APIs

## Documentation and the Open API Specification (MK)

### Exercise 6 - Specify, Serve and Explore your API

## Good Design: Avoild Perfection Paralysis and Malcontents (WC)

## Wrap up, Q&A

## References



### Workshop Documentation

 * [Workshop Slides](https://docs.google.com/presentation/d/1vAycalIQMX1a1j6GefYy11mcRCQujM5-jEx69aczziQ/edit?usp=sharing)

### Tools, Services and Specification 

  + [Open API Initiative](https://openapis.org/)
  + [Open API Specfication fka Swagger Specification](https://github.com/OAI/OpenAPI-Specification)
  + [Other Swagger Based Tools](http://swagger.io/)


  + [API Blueprint - Apiary](http://apiary.io/)

  + [Mashape](https://www.mashape.com/)

### Talks, Papers, Periodicals & Blogs

+ [API Developer Weekly](http://launchany.com/subscribe/)
A digest and review of recent publications in the API development space.

+ [ The API Evangelist](http://apievangelist.com/)

+ [Why REST is More Like Religion than Most Technologies](http://mikeschinkel.com/blog/why-rest-is-more-like-religion-than-most-technologies/)

+ [Heroku's API design guidelines](https://geemus.gitbooks.io/http-api-design/content/)

+ [The Map of A Tweet](http://www.scribd.com/doc/30146338/map-of-a-tweet)
A colorized visualization of the JSON representation of a tweet

+ [REST: I don't Think it Means What You Think it Does • Stefan Tilkov](https://www.youtube.com/watch?v=pspy1H6A3FM)
Common misconceptions on what REST means

+ [Design-first APIs in Practice](http://www.infoq.com/presentations/api-design-first?utm_source=infoqWeeklyNewsletter&utm_medium=WeeklyNL_EditorialContent_architecture-design&utm_campaign=12222015news)
A pretty good overview of leading the design of your API from a consumer
point of view with a particular emphasis on the Design-Thinking
approach.

+ [Do you really know why you prefer REST over RPC?](http://apihandyman.io/do-you-really-know-why-you-prefer-rest-over-rpc/)
A good post on RPC vs REST, especially the follow-up comments

+ [On Choosing a Hypermedia format for your API](http://sookocheff.com/posts/2014-03-11-on-choosing-a-hypermedia-format/)

+ [The Hypermedia Debate](http://www.foxycart.com/blog/the-hypermedia-debate#.VVyQAlVVhBc)

+ [API Changelog](https://www.apichangelog.com/)

### Books & Documentation

+ [IANA Media-Types](http://www.iana.org/assignments/media-types/media-types.xhtml)

+ [Hypermedia](http://en.wikipedia.org/wiki/Hypermedia)

+ [Hypertext Application Language (HAL)](http://stateless.co/hal_specification.html)

+ [Siren - Like HAL with relationships and HTTP query methods](https://github.com/kevinswiber/siren)

+ [JSON API](http://jsonapi.org)

+ [H-Factor](http://amundsen.com/hypermedia/hfactor/)

+ [Building Hypermedia APIs with HTML5 and Node Amundsen 2011](https://books.google.com/books?id=GzsT5r4XShsC)

+ [RESTful Web APIs - Richardson, Amundsen & Ruby 2013](https://books.google.com/books?id=ZXDGAAAAQBAJ)

+ [Architectural Styles and the Design of Network-based Software Architectures - Fielding 2000](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)

+ [JSON Schema](http://json-schema.org/)

+ [JSON-LD Specification](http://www.w3.org/TR/json-ld/)

+ [JSON-LD Homepage](http://json-ld.org/)

+ [JSON-RPC Homepage](http://json-rpc.org/)

### Example & Refrence APIs

+ [Example Siren Based API: Wurl Video Streaming Platform ](http://developers.wurl.com/pages/reference/entities/root)

+ [DigitalOcean API documentation](https://developers.digitalocean.com/documentation/v2/)
Not that the API is the best, but I really like the structure of the
documentation. It includes examples for multiple languages.

+ [GitHub API](https://developer.github.com/v3/)
The GitHub API is known for its good design and usability.

+ [Stripe API](https://stripe.com/docs/api)
The Stripe online payment processing API.  Introduced a new level of
developer friendliness with the disruptive introduction of its API.


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Practical Web API Design</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/cucode/practical_web_api_design_UoI_WebCon_2016" property="cc:attributionName" rel="cc:attributionURL">Wes Cravens, Marty Kane, Aaron Lee & John McCaffrey</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/cucode/practical_web_api_design_UoI_WebCon_2016" rel="dct:source">https://github.com/cucode/practical_web_api_design_UoI_WebCon_2016</a>.
