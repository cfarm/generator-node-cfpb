# <%= props.name %> [![Build Status](https://secure.travis-ci.org/cfpb/<%= slugname %>.png?branch=master)](http://travis-ci.org/cfpb/<%= slugname %>)

> <%= props.description %>

## Installation

First install [node.js](http://nodejs.org/). Then:

```sh
npm install <%= slugname %> --save
```

## Usage

[Require](http://browserify.org/) the module and pass it a [`Position` object](https://developer.mozilla.org/en-US/docs/Web/API/Position):

```javascript
var <%= slugname %> = require('<%= slugname %>');
<%= slugname %>.awesome(); // "awesome"
```

## Contributing

Please read the [Contributing guidelines](CONTRIBUTING.md).

### Running Tests

We are using [nodeunit](https://github.com/caolan/nodeunit) to test. To run tests, first install nodeunit and any dependencies via npm:

```
npm install
```

Run tests with:

```
npm test
```