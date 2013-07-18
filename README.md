SMARTY-Markdown
===============

A function plugin for the SMARTY Template engine that processes and formats text that uses Markdown.
There is nothing fancy going on here and this is honestly something most people could implement on their own in a few minutes. However, after searching I was not able to find a decent plugin for the SMARTY engine so I wrote one using the wonderful [PHP Markdown Library by Michel Fortin](http://michelf.ca/projects/php-markdown/). His entire library is included (along with with its respective license) and can be used to further extend this plugin, or even create a more robust suite of formatting plugins surrounding Markdown for the SMARTY Template Engine.

Given the extremely basic nature of this plugin, I would not expect to see frequent updates, unless of course SMARTY itself changes and the plugin needs to change, otherwise feel free to fork or look at other forks (if/when they come into existence) if you want or need more robust functionality than simply turning Markdown formatted text into HTML formatted text for your templates.

Install
===============

Simply copy the contents of the plugins folder into your own plugins folder.

Usage
===============

{markdown text="**I'm Bold**"}
