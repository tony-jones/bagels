# bagels

[![license][license-image]][license-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][dependencyci-image]][dependencyci-url]

> Blog, portfolio, and weekly design collective magazine by Tony Jones

## Prerequisites

To install this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll -v 3.6.2`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [Firebase CLI](https://github.com/firebase/firebase-tools).

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**Development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc.

```shell
$ npm run start
```

**Deploy mode**

You can easily deploy your site build with the command
```shell
$ npm run deploy
```

## Tests

If you want to run the tests on your local machine please install `gem install html-proofer`. And then run the tests using
```shell
$ htmlproofer ./_site
```

[license-image]: https://img.shields.io/badge/license-ISC-blue.svg
[license-url]: https://github.com/tony-jones/bagels/blob/develop/LICENSE
[travis-image]: https://travis-ci.org/tony-jones/bagels.svg?branch=develop
[travis-url]: https://travis-ci.org/tony-jones/bagels
[dependencyci-image]: https://dependencyci.com/github/tony-jones/bagels/badge?style=flat
[dependencyci-url]: https://dependencyci.com/github/tony-jones/bagels
