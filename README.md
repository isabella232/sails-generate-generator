# [<img title="sails.io.js - Generate Generator for Sails" src="http://i.imgur.com/5Pe84Ph.png" width="100px" alt="icon of a lightning bolt inside of a gear - the logo for the sails generate generator"/>](https://github.com/balderdashy/sails-generate-generator) Sails Generate Generator

# generator generator

A Sails generator for Sails generators.  [Buffalo buffalo Buffalo buffalo buffalo buffalo Buffalo buffalo!](http://en.wikipedia.org/wiki/Buffalo_buffalo_Buffalo_buffalo_buffalo_buffalo_Buffalo_buffalo)


### Installation

Already included in Sails.


### Usage

##### On the command line

```sh
$ sails generate generator foo
```

##### In a node script

```javascript
var generate = require('sails-generate');
var scope = {};
generate(require('sails-generate-generator'), scope, function (err, output) {
  if (err) throw err;

  // Log output for your enjoyment:
  console.log(output);
});
```

### Development

To get started quickly and see this generator in action, run the `bin/index.js` script:

```sh
$ git clone YOUR_FORK_OF_THIS_REPO sails-generate-generator-fork
$ cd sails-generate-generator-fork
$ npm install
$ node ./bin
```

`bin/index.js` is a simple script, bundled only for convenience, that runs the generator with hard-coded scope variables.  Please feel free to modify that file however you like!  Also see `CONTRIBUTING.md` for more information on overriding/enhancing generators.



### Questions?

See `FAQ.md`.



### More Resources

- [Stackoverflow](http://stackoverflow.com/questions/tagged/sails.js)
- [#sailsjs on Freenode](http://webchat.freenode.net/) (IRC channel)
- [Twitter](https://twitter.com/sailsjs)
- [Professional/enterprise](https://github.com/balderdashy/sails-docs/blob/master/FAQ.md#are-there-professional-support-options)
- [Tutorials](https://github.com/balderdashy/sails-docs/blob/master/FAQ.md#where-do-i-get-help)
- <a href="http://sailsjs.org" target="_blank" title="Node.js framework for building realtime APIs."><img src="https://github-camo.global.ssl.fastly.net/9e49073459ed4e0e2687b80eaf515d87b0da4a6b/687474703a2f2f62616c64657264617368792e6769746875622e696f2f7361696c732f696d616765732f6c6f676f2e706e67" width=60 alt="Sails.js logo (small)"/></a>



### License

**[MIT](./LICENSE)**
&copy; 2014
[Mike McNeil](http://michaelmcneil.com), [Balderdash](http://balderdash.co) & contributors

------------------------------------------

As for [Sails](http://sailsjs.org)?  It's free and open-source under the [MIT License](http://sails.mit-license.org/).
