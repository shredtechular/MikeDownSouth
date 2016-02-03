# [MikeDownSouth](http://thewaysnrubthinks.github.io/MikeDownSouth/) Source Code

This is the source code of MikeDownSouth, a personal blog built using [Jekyll](http://jekyllrb.com) and utilizing [GitHub Pages](https://pages.github.com/) to publish and host the site.

Current Build Status is: [![Build Status](https://secure.travis-ci.org/TheWaySnrubThinks/MikeDownSouth.png?branch=gh-pages)](http://travis-ci.org/TheWaySnrubThinks/MikeDownSouth)

## Local Development

1. Install dependencies `bundle install`
2. Run Jekyll server to preview in development mode `jekyll serve`.  To regenerate the site automatically use the watcher option `-w`.
3. The site's configuration file builds the site to `_site/MikeDownSouth/` directory within the project.  View the generated site by going to [http://localhost:4000/MikeDownSouth/](http://localhost:4000/MikeDownSouth/)

## Site Structure

#### _data 
Directory contains a yml file with a list of comments.

#### _includes 
Contains several partials that are common to several generated pages.

#### _layouts 
Contains the templates that are used to generate the commonality of the pages (default is the main one that all the pages use.

#### _pages 
Contains all non-blog post pages  broken up into sub-folders. Used mostly for setting up the different categories, monthly archives, author, and tag pages, but does also contain the about page. The homepage is in the root (index.html) as that is where it needed to be for pagination to work on the main page.

#### _posts
Contains all of the individual blog entries.  In order to customize the "extract" of the blog that is shown on archives pages, it is possilbe to add this html comment `<!--more-->` to mark where the "extract" should end.  Otherwise, the "extract" will show the first paragraph by default.

#### css 
Contains the css for the project.

#### images 
Contains all the image files broken out by month
