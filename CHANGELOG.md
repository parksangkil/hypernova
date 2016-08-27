# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [2.0.0] - YYYY-MM-DD

### Changed

- `toScript` function signature changed. It now expects an object of data attributes to value.

  ```js
  // before
  toScript('foo', 'bar', { hello: 'world' })

  // now
  toScript({ foo: 'bar' }, { hello: 'world' })
  ```

- `fromScript` function signature changed.

  ```js
  // before
  fromScript('foo', 'bar')

  // now
  fromScript({ foo: 'bar' })
  ```

## [1.1.0] - 2016-06-15

### Changed

- Documentation fixes.
- Allows non-errors to be rejected from Promises in getComponent.
- Sets worker count to 1 when cpu count is 1.
- Makes the endpoint configurable.
- Exports worker functions so you can customize your own worker.

## [1.0.0] - 2016-06-06

Initial Release
