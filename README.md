# @binogi/angular-moment-es6

ES6 version of original [angular-moment](https://github.com/urish/angular-moment) package.

AngularJS directive and filters for [Moment.JS](http://www.momentjs.com).

## Usage

Install the angular-moment-es6 package

```sh
# with yarn
yarn add @binogi/angular-moment-es6

# with npm
npm install @binogi/angular-moment-es6 --save
```

Add the module `angularMoment` as a dependency to your app module:

```js
import angularMoment from '@binogi/angular-moment-es6'

const myapp = angular.module('myapp', [angularMoment]);
```