
ember-ordered-set
==============================================================================

[![npm](https://img.shields.io/npm/v/@ember/ordered-set.svg)](https://www.npmjs.com/package/@ember/ordered-set)
[![Build Status](https://travis-ci.org/emberjs/ember-ordered-set.svg?branch=master)](https://travis-ci.org/emberjs/ember-ordered-set)

The `OrderedSet` class lets you store unique values of any type, whether
primitive values or object references. It is mostly similar to the native
[`Set`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
class introduced in ES2015.



Compatibility
------------------------------------------------------------------------------

* Ember.js v2.16 or above
* Ember CLI v2.13 or above
* Node.js v6 or above


Installation
------------------------------------------------------------------------------

```
ember install @ember/ordered-set
```


Usage
------------------------------------------------------------------------------

After installing you can import `OrderedSet` from `@ember/ordered-set`:

```js
import OrderedSet from '@ember/ordered-set';
```

The `OrderedSet` class has mostly the same API as the native [`Set`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
class with a few differences:

- The constructor does not take any arguments
- A static `create()` method exists for symmetry with `Ember.Object`
- A static `length` property does not exist on `OrderedSet`
- `OrderedSet` has an `isEmpty()` method
- There are no `entries()`, `keys()` and `values()` methods, but there is a
  `toArray()` method instead
- The `@@iterator` symbol is not defined
- `OrderedSet` has a `copy()` method


Contributing
------------------------------------------------------------------------------

See the [Contributing](CONTRIBUTING.md) guide for details.


License
------------------------------------------------------------------------------
ember-ordered-set is licensed under the [MIT License](LICENSE.md).

