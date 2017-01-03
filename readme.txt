Project: crawler created by python
Author: renjie
date: 2016/12/31

Requirements:
  *python 3.4+
  *aiohttp

This is a web crawler, you give it a URL and it will craw that website by following href links in the HTML pages.

It doesn't do anything with the crawled pages, and the algorithm for finding links is intentionally naive -- these parts are easily modifie, and not of particular interes.

The point of this projet is to show off how to write a reasonably complex HTTP client application using the asynixo module. 

usage:

  python3 crawl.py -q xkcd.com
