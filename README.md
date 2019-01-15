# ng-xlsx-style

Forked from https://github.com/protobi/js-xlsx/ - refer to original documentation there.
This project only aims to support generation in browser, not in a node env.

## Changes

* remove require statement for `cptable` to allow this to work in angular projects (and others I suppose)
* remove require statements for `fs` (only needed for node, not browser)
* remove require statement for `crypto` (not needed at this time)
* fix require statement for jszip