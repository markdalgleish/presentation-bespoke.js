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

`$ grunt` to generate all static content into the 'public' directory.

`$ grunt server` to generate all static content and fire up a Connect server at [http://localhost:8000](http://localhost:8000).

`$ grunt dev` to fire up a Connect server at [http://localhost:8000](http://localhost:8000) and recompile whenever files are changed.

## Questions?

Contact me on GitHub or Twitter: [@markdalgleish](http://twitter.com/markdalgleish)

## License

Copyright 2013, Mark Dalgleish  
This content is released under the MIT license  
http://markdalgleish.mit-license.org