# sloccount
Counts lines of code of HTML, CSS &amp; JS - Outputs them in a Jenkins compatible format

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![version](https://img.shields.io/npm/v/sloccount.svg?style=flat-square)](http://npm.im/sloccount)
[![downloads](https://img.shields.io/npm/dm/ssloccount.svg?style=flat-square)](http://npm-stat.com/charts.html?package=sloccount&from=2016-01-01)
[![MIT License](https://img.shields.io/npm/l/sloccount.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fasciidisco%2Fsloccount.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fasciidisco%2Fsloccount?ref=badge_shield)

[![Build Status](https://travis-ci.org/asciidisco/sloccount.svg?branch=master)](https://travis-ci.org/asciidisco/sloccount)
[![codecov coverage](https://img.shields.io/codecov/c/github/kentcdodds/starwars-names.svg?style=flat-square)](https://codecov.io/github/kentcdodds/starwars-names)
[![Dependency Status](https://david-dm.org/asciidisco/sloccount/master.svg)](https://david-dm.org/asciidisco/sloccount/master)
[![devDependency Status](https://david-dm.org/semantic-release/semantic-release/caribou/dev-status.svg)](https://david-dm.org/asciidisco/sloccount/master#info=devDependencies)

## Installation

This package is distributed via npm:

```
npm install -g sloccount
```

## Usage

```bash
> sloccount --help

---------------------------

Counts lines of code of HTML, CSS & JS - Outputs them in a Jenkins compatible format

Usage
  $ sloccount <src> <reportPath>

Options
  -c, --comments  Exclude comments
  -v, --verbose  Verbose output

    Examples
      $ sloccount *.js report.sc --comments
```

### output

```bash
Creating filelist for /Github/asciidisco/sloccount
Categorizing files.
Computing results.


57	js	/Github/asciidisco/sloccount	/Github/asciidisco/sloccount/index.js
14	jscm	/Github/asciidisco/sloccount	/Github/asciidisco/sloccount/index.js.cm
```

## Contribute

All PRs are welcome.
If you´re sending a PR, please sqash your changes, make sure you covered your code with (passing) unit tests & you should be good to go.
Always be inclusive, friendly & make sure you act up to the [Open Code of Conduct](http://todogroup.org/opencodeofconduct/), actions will be taken if you´re not.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fasciidisco%2Fsloccount.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fasciidisco%2Fsloccount?ref=badge_large)