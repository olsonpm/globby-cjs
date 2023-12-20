## What is this

A simple cjs wrapper to the [globby](https://github.com/sindresorhus/globby) module

## Why make a wrapper ?

Since version 12 of globby, the module [only supports esm import](https://github.com/sindresorhus/globby/commit/5c32b4ab94aee6ee8696508e9cd1ee4bb4f4cdfc).
In order to continue using this module conveniently I decided to wrap it in [fix-esm](https://www.npmjs.com/package/fix-esm).

## Why declare globby as a peer dependency ?

Doing this allows you to decide the version of globby in your project.
