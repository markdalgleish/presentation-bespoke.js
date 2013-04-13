# DIY Presentations with Bespoke.js

[View the presentation online](http://markdalgleish.com/presentations/bespoke.js), or build it yourself from this repo if you're feeling nerdy.

This presentation was originally created for Web Directions ["What Do You Know"](http://www.webdirections.org/blog/what-do-you-know-melbourne-wrap-up/) in Melbourne, Australia on 4 April 2013.

### Build requirements

Assuming you already have [Node.js](http://nodejs.org/) installed, ensure you have [Grunt-cli](http://gruntjs.com/) installed globally:

```bash
$ npm install -g grunt-cli
```

Then, install the dependencies with [npm](https://npmjs.org/):

```bash
$ npm install
```

### Running the build

To generate all static content into the 'public' directory, run the Grunt build:

```bash
$ grunt
```

To run the build whenever files are changed, use the 'watch' task:

```bash
$ grunt watch
```

On Mac, you can host a simple Python server from the 'public' directory like so:

```bash
$ cd public && python -m SimpleHTTPServer 8080
```

## Questions?

Contact me on GitHub or Twitter: [@markdalgleish](http://twitter.com/markdalgleish)

## License

Copyright 2013, Mark Dalgleish  
This content is released under the MIT license  
http://markdalgleish.mit-license.org