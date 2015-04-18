# README for my Jekyll
This is a Readme file for my Jekyll installation.

I will note down some issues useful for running this thing.

## Hosted Build failure
I can't understand why Github keeps failing in building my blog. 
Following [this guide](https://github.com/jekyll/jekyll/issues/731) I will try to build my blog locally and then commit/push the whole thing.

## Build locally
Here is the guide to Jekyll: [http://jekyllrb.com/](http://jekyllrb.com/).

This is also helpful to work with GitHub: [https://help.github.com/articles/using-jekyll-with-pages/](https://help.github.com/articles/using-jekyll-with-pages/).

1. Move in the directory (./Github/pepato.github.io)
1. Build the site:
`` jekyll build --watch``
2. Run the server:
`` jekyll serve --detach``

You should find your site generated in ``localhost:4000`` and automatically updated.

Basically, all the build options are listed [here](http://jekyllrb.com/docs/usage/).

## How to hide a post
To make a post invisible and unavailable, just add ``published: false`` in the YAML Front Matter.
