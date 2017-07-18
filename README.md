# jekyll-bootstrap-sass

This is a boilerplate project for Jekyll, which is bundled with bootstrap-sass.

Using this project will give you:

* Default template for static blogging with [Jekyll](http://jekyllrb.com/ "Jekyll").
* Bootstrap framework via [bootstrap-sass](https://github.com/twbs/bootstrap-sass/ "Twitter Bootstrap") 3.3.5
* Sensible website defaults from [html5boilerplate](https://html5boilerplate.com/ "HTML5 Boilerplate") 5.2.0
* [Modernizr](http://modernizr.com/ "Modernizr") 2.8.3
* [jQuery](https://jquery.com/ "jQuery") 1.11.3
* Google Analytics code snippet


## Prerequisites

You will need to have [Jekyll](http://jekyllrb.com/ "Jekyll") installed to utilise this project.

## How to run locally

1. Clone this repository: git clone https://github.com/irmbrady/jekyll-bootstrap-sass.git
2. Go into the directory: cd jekyll-bootstrap-sass
3. Run Jekyll: jekyll serve
4. Open your browser and navigate to: http://localhost:4000

## Development

Add custom Bootstrap variables to `/_sass/bootstrap/_bootstrap-custom-variables.scss`.

Any custom SCSS partials should be added to the `_sass` folder, as they will be compiled by Jekyll when serving. These partials must be imported in `/stylesheets/main.scss`.

Update your Google Analytics tracker ID in `/_layouts/defaults.html`.

## Deployment

You can deploy your static blog for free using GitHub pages:

* [http://jekyllrb.com/docs/github-pages/](http://jekyllrb.com/docs/github-pages/ "GitHub Pages")
* [https://help.github.com/articles/using-jekyll-with-pages](https://help.github.com/articles/using-jekyll-with-pages "Using Jekyll with Pages")

More deployment methods are explained in the Jekyll documentation:

* [http://jekyllrb.com/docs/deployment-methods/](http://jekyllrb.com/docs/deployment-methods/ "Deployment methods")
