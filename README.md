# Haxe Formatter

[![Build Status](https://travis-ci.org/HaxeCheckstyle/haxe-formatter.svg?branch=master)](https://travis-ci.org/HaxeCheckstyle/haxe-formatter)
[![Codecov](https://img.shields.io/codecov/c/github/HaxeCheckstyle/haxe-formatter.svg)](https://codecov.io/github/HaxeCheckstyle/haxe-formatter?branch=master)

**use at your own risk**

Formatter based on tokentree library

**make a backup of your files**


## Features
- Indentation
- Whitespace
- Wrapping
- EmptyLines
  - abstract
  - enum abstract
  - class
  - extern class
  - interface
- SameLine
  - if
  - loops
  - try / catch
  - objects / anonymous types
- LineEnds
- `hxformat.json` config file
- supports `// @formatter:off` and `// @formatter:on` to preserve hand crafted format of code sections
- unittests
  - format self
  - easy testcase definition through .hxtest

## ToDo
- Configuration
  - more options
  - load (save)
- better wrapping
  - arrays
  - objects / anonymous types
- empty lines in
  - enum
  - typedef

## TBD
- code modification e.g.
  - import grouping and sort
  - modifier sort
