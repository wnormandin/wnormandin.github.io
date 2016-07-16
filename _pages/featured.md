---
layout: page
title: Featured
permalink: /featured/
---
[PokeyCrawl] (https://github.com/wnormandin/pokeycrawl){:target='_blank'} - PokeyCrawl began as a simple, non-threaded crawler which was invoked using bash scripting to achieve multithreading. I decided to adapt this idea to a 100% Python solution which is much more fully-featured with a command-line utility for ease of use.  The alpha version of this is available on [PyPi](https://pypi.python.org/pypi?:action=display&name=pokeycrawl&version=0.1.1a5){:target='_blank'}.

[PokeyTools](https://github.com/wnormandin/pokeytools){:target='_blank'} - Written with a Gtk 3.0 GUI, PokeyTools provides convenient access to DNS, Whois, SSL, and other web protocol lookups.  It also contains functionality allowing the creation, deduplication, and searching of a predefined library, such as e-mail replies, code snippets or scripts, licensing information, and etc.

[dedupe.py](https://github.com/wnormandin/pokeytools/blob/master/lib/dedupe.py){:target='_blank'} - `dedupe.py` is a utility within PokeyTools which uses various fuzzy matching algorithms (Levenshtein, Jaro, Jaro-Winkler, and Hamming distances, along with other ratios) to create a composite score according to a global `PARAM` model.  This matching can be used for search functions, data deduplication, data linkage, and many other purposes.

[Pokeyworks](https://github.com/wnormandin/pokeyworks){:target='_blank'} - Pokeyworks is a collection of classes and functions most of my personal projects use in some capacity.  Included are a generic curses menu class, convenient JSON/YAML/Base64 encoding and conversion of configuration dictionaries, limited word pluralization, console ASCII color wrappers, and several other convenience classes and functions.

[PokeyBots](https://github.com/wnormandin/social_media_bots){:target='_blank'} - PokeyBots contains an implementation of a Twython Twitter bot, along with an IRC bot (PokeyBot) which uses `socket`.
