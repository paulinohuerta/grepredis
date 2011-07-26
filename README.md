# grepredis


grepredis is a awk script for searching patterns in lists and hashs of a server Redis.

# !NOTE!

The limitations are those of awk text processing

## About

## Requirements

* A running Redis server
* Gawk 

## Usage

All you need to do to get up and running after the requirements are installed is:

    $ gawk -f grepredis 'pattern' /dev/null
    

## Acknowledgments


