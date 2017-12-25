# Node BACstack Device

A BACnet device simulator using [Node BACstack](https://github.com/fh1ch/node-bacstack).

[![](https://travis-ci.org/fh1ch/node-bacstack-device.svg?branch=master)](https://travis-ci.org/fh1ch/node-bacstack-device)
[![](https://coveralls.io/repos/fh1ch/node-bacstack-device/badge.svg?branch=master)](https://coveralls.io/r/fh1ch/node-bacstack-device?branch=master)
[![](https://codeclimate.com/github/fh1ch/node-bacstack-device/badges/gpa.svg)](https://codeclimate.com/github/fh1ch/node-bacstack-device)
[![](https://david-dm.org/fh1ch/node-bacstack-device/status.svg)](https://david-dm.org/fh1ch/node-bacstack-device)

> **Note:** This is an early prototype and shall not be considered as stable.
> Use it with caution and at your own risk!

## Usage

Start Node BACstack Device by using:

``` sh
git clone https://github.com/fh1ch/node-bacstack-device.git

cd node-bacstack-device
npm i

npm start
```

## Contributing

Any help is appreciated, from creating issues, to contributing documentation,
fixing issues and adding new features.

Please follow the best-practice contribution guidelines as mentioned below when
submitting any changes.

### Conventional Changelog

This module has a changelog which is automatically generated based on Git commit
messages. This mechanism requires that all commit messages comply with the
[Conventional Changelog](https://github.com/bcoe/conventional-changelog-standard/blob/master/convention.md).
You can check if your commit messages complies with those guidelines by using:

``` sh
npm run changelog
```

### Code Style

This module uses the [Google JavaScript Code-Style](https://google.github.io/styleguide/javascriptguide.xml)
and enforces it using [JSCS](http://jscs.info/) as additional linter beneath
[JSHint](http://jshint.com/). You can test if your changes comply with the code
style by executing:

``` sh
npm run lint
```

### Testing and Coverage

Testing is done using [Mocha](https://mochajs.org/).

The test-coverage is calculated using [Istanbul](https://istanbul.js.org/).
Running the tests and calculating the coverage can be done locally by executing:

``` sh
npm run test
```

It is expected that new features or fixes do not negatively impact the test
results or the coverage.

## License

[The MIT License](http://opensource.org/licenses/MIT)

Copyright (c) 2017 Fabio Huser <fabio@fh1.ch>
