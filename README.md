# Event sourcing in practice

These are the slides we use for our talk "Event Sourcing in practice". We are scheduled to give this talk at:
- [Java User Group Frankfurt, December 18th 2013](https://sites.google.com/site/jugffm/home/18-12-2013-why-care-about-big-data)
- [Frankfurter Entwicklertag, February 19th 2014](http://www.entwicklertag.de/frankfurt/2014/session/event-sourcing-der-praxis)
- [Developer Week Nürnberg, July 15th](http://www.developer-week.de/Programm/Veranstaltung/%28event%29/14192)

Slide content is subject to change as we keep on learning :).

## Pre-built slides

Slides are automatically built and published using Travis CI. You may find the latest version in the `gh-pages` branch or at [the associated Github Page for this repository](http://xpepper.github.io/event-sourcing-in-practice/index.html)

[![Build Status](https://travis-ci.org/xpepper/event-sourcing-in-practice.png?branch=master)](https://travis-ci.org/xpepper/event-sourcing-in-practice)

## Building the slides from scratch

- Install Python
- Install pip
- Create a virtualenv 
  `pip install virtualenvwrapper && mkvirtualenv event-sourcing` (Recommended but optional)
- Run `pip install -r requirements.txt`
- Start the [Cactus](https://github.com/koenbok/cactus) server `cactus serve`

## Markdown

- Slides are created using markdown. The [Markdown Extra](http://michelf.ca/projects/php-markdown/extra/) syntax elements are enabled.
