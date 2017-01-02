# swarm-numberformat

Format large numbers in several human-readable ways. Designed for incremental games like [swarmsim](https://swarmsim.github.io).

     numberformat.format(1e6)
     // => "1 million"

[See it in action](https://jsbin.com/zadepad/edit?html,output).

[![Travis build status](http://img.shields.io/travis/erosson/swarm-numberformat.svg?style=flat)](https://travis-ci.org/erosson/swarm-numberformat)
[![Dependency Status](https://david-dm.org/erosson/swarm-numberformat.svg)](https://david-dm.org/erosson/swarm-numberformat)
[![devDependency Status](https://david-dm.org/erosson/swarm-numberformat/dev-status.svg)](https://david-dm.org/erosson/swarm-numberformat#info=devDependencies)

## Getting started

    <script src="//cdn.rawgit.com/erosson/swarm-numberformat/master/dist/main.js"></script>

or

    npm install --save swarm-numberformat

    const numberformat = require('swarm-numberformat')

TODO: better documentation. For now, see its features in [the demo](https://jsbin.com/zadepad/edit?html,output).

## Related work

Based on swarmsim's bignum:
* https://github.com/swarmsim/swarm/blob/master/app/scripts/filters/bignum.coffee
* https://github.com/swarmsim/swarm/blob/master/test/spec/filters/bignum.coffee

Project template: https://github.com/babel/generator-babel-boilerplate
