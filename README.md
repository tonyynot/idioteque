[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/tonyynot/idioteque/blob/master/LICENSE)

# Idioteque - A Minimal Theme for Jekyll
Idioteque is a clean, minimal and easy to use theme for Jekyll. It is responsively designed using [Bourbon](http://bourbon.io) and the Neat grid. Colors and fonts can be easily changed with the defined Sass variables found in ``_variables.scss.`` Compiling is handled by Gulp and the settings can be found in the gulpfile. The gulpfile.js is thanks to shakyShane's [Jekyll-Gulp-Browsersync](https://github.com/shakyShane/jekyll-gulp-sass-browser-sync) starter project which includes an out of the box installation of Jekyll with GulpJS, Sass compiling, AutoPrefixer & BrowserSync configurations.

## Installation
Fork and clone this repository, then cd into the directory  
```bash
$ cd idioteque
```

Run
```bash
$ npm install
$ gem install bundler
$ bundle install
```
Then run
```bash
$ gulp
```

## Gulp.js build automation
After running the gulp command, your site will automatically open in the browser window via Browsersync. Sass compiling is handled in Gulp and all changes made to HTML and Sass will trigger the browser to auto refresh.

* For gulp.js installation help, view the [readme](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md).

More detailed documentation is currently in the works. If you would like to use the theme prior to official release, please contact me. In the meantime, [this post](https://anthernet.com/blog/new-blog-design/) should serve as a guide on how customization works.

## User comments
Idioteque can generate user comments statically via github pull requests through [Staticman](https://staticman.net/). Please visit the site for installation instructions and configuration. In the staticman.yml file, the settings can be changed in the comments section. Disqus comments are enabled by default and can be disabled by commenting out the line ``{% include externals/disqus.html %}`` in ``_layouts/post.html``. Simply un-comment the line ``{% include comments.html %}`` to enable statically generated comments.

## [DEMO](http://anthonyramella.com)

## License
[MIT](https://github.com/tonyynot/idioteque/blob/master/LICENSE). Copyright &copy; [Anthony Ramella](http://tonyynot.me)
