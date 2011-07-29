# Grepredis


Grepredis is a AWK script for searching patterns in lists and hashs of a server Redis.

# !NOTE!

The limitations are those of AWK text processing.

Commands executed by the script: SELECT, KEYS, TYPE, LLEN, LRANGE, HGETALL

## About

Given the simplicity Redis server protocol, type telnet, and the ability to access network services with short AWK scripts, it is easy to integrate server Redis access from system utilities.

## Requirements

* A running Redis server
* GNU AWK (release >= 3.1) 

## Usage

All you need to do to get up and running after the requirements are verified:

    $ gawk -f grepredis 'pattern' /dev/null
    

## License

Grepredis is covered by the MIT License. See LICENSE for more information.
