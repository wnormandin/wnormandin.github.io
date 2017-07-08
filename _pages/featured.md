---
layout: page
title: Featured
permalink: /featured/
---
[PokeyDispatch](https://github.com/wnormandin/pokeydispatch){:target='_blank'} - PokeyDispatch is a multifaceted SSH client/server which uses Python 3 and paramiko.  The basic client allows running remote commands across a list of servers, and will soon support a fully interactive mode.  Using --server, an SSH server can be set up which accepts a connection from a client instance (on, say, a Windows PC w/o SSH) and then functions as a reverse shell.

[PokeyScan](https://github.com/wnormandin/pokeyscan){:target='_blank'} - PokeyScan is a simple, multithreaded port scanner  which provides some flexibility via command line arguments.

[PokeyProxy](https://github.com/wnormandin/pokeyproxy){:target='_blank'} - PokeyProxy is a basic TCP proxy.

[PokeyCrawl](https://github.com/wnormandin/pokeycrawl){:target='_blank'} - PokeyCrawl began as a simple, non-threaded crawler which was invoked using bash scripting to achieve multithreading. I decided to adapt this idea to a 100% Python solution which is much more fully-featured with a command-line utility for ease of use.  The alpha version of this is available on [PyPi](https://pypi.python.org/pypi?:action=display&name=pokeycrawl&version=0.1.1a5){:target='_blank'}.

[pokeysniff](https://github.com/wnormandin/pokeysniff){:target='_blank'} - Pokeysniff is a bare-bones packet sniffer available for download via my personal script repository at [https://scripts.pokeybill.us/pokeysniff.py](https://scripts.pokeybill.us/pokeysniff.py){:target='_blank'}.

[dedupe.py](https://github.com/wnormandin/pokeytools/blob/master/lib/dedupe.py){:target='_blank'} - `dedupe.py` is a utility within PokeyTools which uses various fuzzy matching algorithms (Levenshtein, Jaro, Jaro-Winkler, and Hamming distances, along with other ratios) to create a composite score according to a global `PARAM` model.  This matching can be used for search functions, data deduplication, data linkage, and many other purposes.

[PokeyBots](https://github.com/wnormandin/social_media_bots){:target='_blank'} - PokeyBots contains an implementation of a Twython Twitter bot which uses Twython, along with an IRC bot (PokeyBot) using sockets.

[PokeyAPI](https://github.com/wnormandin/pokeyapi){:target='_blank'} - PokeyAPI is a basic RESTful interface with user registration and authentication functionality built in Flask.  Basic GeoIP searches, website crawling and indexing, and other activites are available with registration.

[PokeyTools](https://github.com/wnormandin/pokeydispatch){:target='_blank'} - Written with a Gtk 3.0 GUI, PokeyTools provides convenient access to DNS, Whois, SSL, and other web protocol lookups.  It also contains functionality allowing the creation, deduplication, and searching of a predefined library, such as e-mail replies, code snippets or scripts, licensing information, and etc.
