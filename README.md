# Jekyll GitHub Pages

Jekyll GitHub Pages with Bower Dependencies generated by Gulp

* Injects Sass and JavaScript using [Wiredep](https://github.com/taptapship/wiredep)
* Sass [Autoprefixing](https://autoprefixer.github.io/) and compilation
* JavaScript concatenation
* [BrowserSync](https://www.browsersync.io/) server
* CSS & JavaScript compression for production
* Working with [Foundation for Sites](http://foundation.zurb.com/sites.html) and [FontAwesome](http://fontawesome.io/)
* Easily add other Frameworks such as [Bootstrap](http://getbootstrap.com/)

## Required

* [Ruby](https://www.ruby-lang.org/) - `$ brew install ruby`
* [Bundler](http://bundler.io/) - `$ gem install bundler`
* [NodeJS](http://nodejs.org/) - Download and use installer
* [Bower](https://bower.io/) - `$ npm install -g bower`
* [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp`

## Installation

```
git clone https://github.com/samwilsonme/jekyll-github-pages.git
cd jekyll-github-pages
bundle install
npm install
bower install
```

## Development

Run `$ gulp`

## Production

Run `$ gulp --production`

### Frameworks

#### [Bootstrap](http://getbootstrap.com/)

```
bower install --save bootstrap
```

#### [Foundation for Sites](http://foundation.zurb.com/sites.html)

```
bower install --save foundation-sites
```

Include foundation in `main.scss` (http://foundation.zurb.com/sites/docs/sass.html)

```
@include foundation-everything;
```

### Thanks

Thanks to [fredericpfisterer](https://github.com/fredericpfisterer/) for the gulpfile of [Jekyll-Gulp](https://github.com/fredericpfisterer/Jekyll-Gulp)
