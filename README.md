# KaTeX Rails

A Rails engine that integrates KaTeX into the Asset Pipeline.

## Installing

Add this to your Gemfile:

    gem 'katex-rails'

## Using

To include the stylesheet, require or import the `katex/katex`. An example of using it with sprockets:

    /*
     *= require katex/katex
    */


To include the javascript, require the `katex/katex` in your JavaScript. An example of using it with sprockets:

    // require katex/katex

For information on how to use KaTeX please see: https://github.com/khan/katex

### Precompiling

All the fonts are automatically added to the precompile list. If you'd like to precompile katex.js and katex.css for separate inclusion, then just add the following to your application config.

    config.assets.precompile += ['katex/katex.css', 'katex/katex.js']

## License

KaTeX Rails is licensed under the MIT (LICENSE.txt) license.

Copyright (c) 2014 Fresh Codes LLC
