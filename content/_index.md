---
date: 2017-10-19T15:26:15Z
lastmod: 2019-10-26T15:26:15Z
publishdate: 2018-11-23T15:26:15Z

title: PHP web application framework
description: 
images:
---

<!-- # Hugo Techdoc Theme

## The Techdoc is a Hugo Theme for technical documentation. -->



# XPRSS 
## A fast, unopinionated, minimalist web framework for PHP.




### Features

- fast
- unopinionated
- minimalist

- simple architecture (gives you structure but doesn't get in your way)
- api that doesn't change (we may add to it and change stuff for security, but for the most part this is always* going to work)

- routing
- cookies?
- middleware base - add modular functionality (templating, cors, jwt, etc) w/ middleware!


<!-- * Modern, Simple layout
* Responsive web design
* Documentation menu (Select [Menu style](getting-started/screenshot/#menu-style))
* [Table Of Contents](sample/table-of-contents/) for the page (selective)
* [Theme color](getting-started/screenshot/#theme-color)
* [Edit link](getting-started/screenshot/#edit-link) to documentation repository
* [Custom Shortcodes](sample/custom-shortcodes/)
  * Code highlight with clipboard
  * Alert panel
  * Button
* [Search Shortcode](sample/search-shortcode/) powered by [Algolia](https://www.algolia.com/)
* Open Graph
* Analytics with Google Analytics, Google Tag Manager -->







### Requirements
- apache (min version) / NGINX (min version?)
- php 7 (or greater)




### Installation
```
composer require hxgf/xprss
```

### setup / quick start / getting started
- for apache
  - copy  htaccess
- for nginx
  - copy this code into your conf (or copy contents of nginx.conf file)
- copy contents of demo into index.php (to verify it's working and check out some basic stuff you can do)
- do any initial setup (add middleware, config vars, set up templating)
- the rest is up to you!
  - structure your application how you desire
  - organize it however you want (we recommend simple folders for css, images, templates, js, etc)








<!-- 
- expressjs docs structure (for ref)
    - home
    - getting started
        - installing
        - hello world
        - basic routing
        - static files
        - more examples
        - faq
    - guide
        - routing
        - using middleware
        - writing middleware
        - overriding the express api
        - using template engines
        - error handling
        - debugging
        - express behind proxies
        - moving to express 4/5
        - database integration
    - api reference
        - 5/4/3/2
    - advanced topics
        - template engines
        - process managers
        - security updates
        - security best practices
        - performance best practices
        - health checks and graceful shutdown
    - resources
        - community
        - glossary
        - template engines
        - middleware
        - utility modules
        - frameworks
        - companies using express
        - ope-source projects
        - additional learning
        - contributing to express
        - release change log -->