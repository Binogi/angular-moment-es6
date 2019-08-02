# @binogi/angular-moment-es6

ES6 version of original [angular-moment](https://github.com/urish/angular-moment) package.

AngularJS directive and filters for [Moment.JS](http://www.momentjs.com).

## Usage

Install the angular-moment-es6 package

```sh
# with yarn
yarn add @binogi/es6-angular-moment

# with npm
npm install @binogi/es6-angular-moment --save
```

Add the module `angularMoment` as a dependency to your app module:

```js
import angularMoment from '@binogi/es6-angular-moment'

const myapp = angular.module('myapp', [angularMoment]);
```