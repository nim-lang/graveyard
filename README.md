## Description

This repo contains *non-deprecated* modules that have been removed from the Nim stdlib. These modules have been removed because they have been either deemed broken or not popular enough to warrant an inclusion in the stdlib.

Stdlib modules which have been deprecated do not belong here as they should no longer be used in new code. You may note that some packages in this repo depend on deprecated modules, for example ``scgi``, you may wish to not write new code using these packages.

## Usage
To install pkg foo (where foo is a subdirectory of graveyard), use:
```
nimble install foo
```
eg:
```
nimble install xmldom
```

Some packages may not be published on Nimble yet, you can install them via:

```
nimble install https://github.com/nim-lang/graveyard?subdir=xmldom
```

Change the ``subdir`` parameter to your desired package.

## Adding an obsolete package to graveyard

After adding source code of a package to graveyard, make sure to add it to nimble package repository as done in this [PR](https://github.com/nim-lang/packages/pull/885) for xmldom.


