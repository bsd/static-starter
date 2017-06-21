# BSD Static Site Starter Kit

## Overview

The BSD Static Site Starter Kit (BSSSK or be-sssick) is an opinionated boilerplate for web development based on Google's [Web Starter Kit](https://developers.google.com/web/tools/starter-kit/). 

### Features

| Feature                                | Summary                                                                                                                                                                                                                                                     |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Responsive boilerplate | A minimal boilerplate with the [Bourbon Neat](http://neat.bourbon.io/docs/latest/) semantic grid framework installed. You're welcome to use this or not. Since it is a library of SASS mixins, it doesn't add any bulk to your code if you choose not to use it.                          |
| Sass support                           | Compile [Sass](http://sass-lang.com/) into CSS with ease, bringing support for variables, mixins and more. The latest version of [Bourbon](http://bourbon.io/docs/) is included to provide handy utility functions, while an autoprefixer is included as a CSS post processor. (Run `gulp serve` or `gulp` for production)                                                                                                      |
| Performance optimization               | Minify and concatenate JavaScript, CSS, HTML and images to help keep your pages lean. (Run `gulp` to create an optimised version of your project to `/dist`)                                                                                                |
| Code Linting               | JavaScript code linting is done using [ESLint](http://eslint.org) - a pluggable linter tool for identifying and reporting on patterns in JavaScript. Web Starter Kit uses ESLint with [eslint-config-google](https://github.com/google/eslint-config-google), which tries to follow the Google JavaScript style guide. Meanwhile, SASS is linted using [stylelint](https://github.com/stylelint/stylelint).                                                                                               |
| ES2015 via Babel 6.0                   | ES2015 support using [Babel](https://babeljs.io/). ES2015 source code and modules will be automatically transpiled to ES5 for wide browser support.  |
| PUG support                   | Write simplified, dynamic markup using the [Pug](https://pugjs.org) templating language. |
| SVG Sprites                   | Easily create and inline SVG sprites by dropping individual SVGs into the `app/images/_svg-sprite` directory. |
| Built-in HTTP Server                   | A built-in server for previewing your site locally while you develop and iterate                                                                                                                                                                            |
| Live Browser Reloading                 | Reload the browser in real-time anytime an edit is made without the need for an extension. (Run `gulp serve` and edit your files)                                                                                                                           |
| Cross-device Synchronization           | Synchronize clicks, scrolls, forms and live-reload across multiple devices as you edit your project. Powered by [BrowserSync](http://browsersync.io). (Run `gulp serve` and open up the IP provided on other devices on your network)                       |
| Offline support                     | Thanks to our baked in [Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) [pre-caching](https://github.com/bsd/static-starterkit/blob/master/gulpfile.babel.js#L226), sites deploying `dist` to a HTTPS domain will enjoy offline support. This is made possible by [sw-precache](https://github.com/GoogleChrome/sw-precache/).                                                                                                                                              |
| PageSpeed Insights                     | Web performance metrics showing how well your site performs on mobile and desktop (Run `gulp pagespeed`)                                                                                                                                                    |

## Quickstart

Clone this repository and build on what is included in the `app` directory.

Be sure to look over the [installation docs](docs/install.md) to verify your environment is prepared to run BSSSK.
Once you have verified that your system can run BSSSK, check out the [commands](docs/commands.md) available to get started.

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

* Chrome
* Edge
* Firefox
* Safari
* Opera
* Internet Explorer 10+

This is not to say that Web Starter Kit cannot be used in browsers older than those reflected, but merely that our focus will be on ensuring our layouts work great in the above.

## Troubleshooting

If you find yourself running into issues during installation or running the tools, open an [issue](https://github.com/bsd/static-starterkit/issues).

## Docs and Recipes

* [File Appendix](https://github.com/bsd/static-starterkit/blob/master/docs/file-appendix.md) - What do the different files here do?
* [Deployment guides](https://github.com/bsd/static-starterkit/blob/master/docs/deploy.md) - available for Firebase, Google App Engine and other services.
* [Gulp recipes](https://github.com/gulpjs/gulp/tree/master/docs/recipes) - the official Gulp recipes directory includes a comprehensive list of guides for different workflows you can add to your project.

## Inspiration

BSSSK is inspired by the Web Starter Kit which is inspired by [Mobile HTML5 Boilerplate](https://html5boilerplate.com/mobile/) and Yeoman's [generator-gulp-webapp](https://github.com/yeoman/generator-webapp).

## Contributing

Contributions, questions and comments are all welcome and encouraged. For code contributions to BSSSK, please see our [Contribution guide](CONTRIBUTING.md) before submitting a pull request.

## License

Apache 2.0  
Copyright 2017 Blue State Digital
