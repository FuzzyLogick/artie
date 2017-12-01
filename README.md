# artie.py is a python program that extracts articles from news sites.  

artie.py was written as a response to news sites that bombard the reader with autoplay videos, popups, and seizure-inducing flashing ads.  If you've said to yourself "All I want is to read this damn article... ", artie.py might be for you.  artie.py was NOT meant to be a text-based web browser, lynx is perfect for that.  Instead, artie.py is merely a simple tool to run on the CLI to display news articles, nothing more. Similiar to how cURL can be used to output the HTML of a web page. In my testing, artie.py is compatable with 90% of the news sites out there.  With that being said, artie.py may not work on some sites. 

This script depends on the module Newspaper to work:
pip3 install newspaper3k

newspaper is written by Lucas Ou-Yang and can be found at https://github.com/codelucas/newspaper.  

artie.py is named after the character Artie from The Adventures of Pete and Pete.

This Python script was written by James Russell.

Usage: ./artie.py http://news.com/2017/11/30/media/man-bites-dog-apology/index.html

This is version 1.0
