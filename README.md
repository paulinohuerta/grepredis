# grepredis


grepredis is a awk script for searching patterns in lists and hashs of a server Redis.

A free hosted version of the application lives at [http://swinger.quirkey.com](http://swinger.quirkey.com)

# !NOTE!

The limitaciones son la propias de awk

## About

This was created as a Demo for my talk at jQuery Conf 2009 about Sammy.js, however, its usefulness might outlast my talk. We'll see.

## Requirements

* A running Redis server
* Gawk 

## Usage

All you need to do to get up and running after the requirements are installed is:

    $ gawk -f grepredis 'pattern' /dev/null
    
It should print out instructions of where you can view it.


Once that is set up you can just do:

    $ couchapp push


## Acknowledgments

Swinger was greatly inspired by Pat Nakajima's [Slidedown](http://github.com/nakajima/slidedown). 

### Technologies/Projects used

* [Sammy.js](http://code.quirkey.com/sammy) for frontend controller/routing
* [CouchApp](http://github.com/couchapp/couchapp) for hosting the app in CouchDB
* [Aristo CSS](http://github.com/maccman/aristo/tree/master) for base buttons/styles
* [Showdown](http://attacklab.net/showdown/) for Markdown
* [Prettify](http://code.google.com/p/google-code-prettify/) for Code higlighting
