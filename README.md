ProjectTox-Website
==================

Source code for the Tox.im website

Building the site
=================

Building the site requires Python 3 and the pystache library.  
In the main directory, run ``python3 buildsite.py``.  
The site will be in the new ``site/`` directory.

Translations
============

As well as new translations, improvement of translations we already have is welcome too. Just copy ``index.en.json`` to ``index.??.json``, where ``??`` is your language's [ISO 639 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).  

Language file metadata
----------------------

The JSON files used by buildsite.py have some special names which are used by the script to build the bar of languages in the footer. The names are:

``_language``: The (native) name of your language. Example: *Français*  
``_ind``: A number specifying where your language should be placed relative to other languages. Example: *1*  
``_comment``: A comment about the language file. Optional.  
``_author``: The creator(s) of the file.
##hope you liked it!
