# Changelog

All notable changes to this project will be documented in this file.

## [0.12.5] - 2023-08-25

This is the first version of jzon which continues the unmaintained
json v0.12.4.

### Features
- Implement `IntoIterator` for `Object`
* Add `as_object()` and `as_array()` methods

### Bug Fixes
* Avoid zero initialization in `Short`

### Refactor
* Update lifetimes of `read_complex_string`
* Fix a few typos

### Documentation
- Rename to jzon
- Add this changelog

### CI
- Add Github workflows
