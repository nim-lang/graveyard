## Description

Packages from Nim stdlib that are no longer in use are kept here in case external packages still depend on it.

## Usage
To install pkg foo (where foo is a subdirectory of graveyard), use:
```
nimble install foo
```
eg:
```
nimble install xmldom
```

## Adding an obsolete package to graveyard
After adding source code of a package to graveyard, make sure to add it to nimble package repository as done in this [PR](https://github.com/nim-lang/packages/pull/885) for xmldom.


