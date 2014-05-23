# Deprecated! 

**The movieclub site has been migrated to Django and integrated with the rest of the [BDE websites](https://github.com/eurecombde/bde_website), found at [bde.eurecom.fr](https://bde.eurecom.fr). This project is no longer maintained.**


movieclub [![Build Status](https://travis-ci.org/eurecombde/movieclub.png?branch=master)](https://travis-ci.org/eurecombde/movieclub)
=========

Webpage for the movie club at Eurecom. The site is located at [bde.eurecom.fr](http://bde.eurecom.fr).

Add new movie to the program by adding it to the top of the `_data/screenings.yml` file, follow the
same format as the others.

To write a new blog post, add a new file in `_posts` in the format
`{year}-{month}-{date}-{post-slug}.markdown`, and write it in markdown. If you want to use any
images, add them to the `images` directory.

Running locally
---------------

If you want to run it locally to see how it will look before pushing online, read on.

First, you need to install jekyll (or ruby and ruby devkit first, if you haven't already).

    $ gem install jekyll
    $ gem install wdm # If you want to have watch functionality (you probably do!)

Start the server:

    $ jekyll serve --watch

Open `localhost:4000` in your browser and browser around. The site will be automatically rebuilt if
you do any changes, simply reload your browser, no need to restart jekyll.
