[![Build Status](https://travis-ci.com/cu-ecen-5013/auto-dependency-generation-example.svg?branch=master)](https://travis-ci.com/cu-ecen-5013/auto-dependency-generation-example)

# auto-dependency-generation-example
A project demonstrating Auto Dependencies functionality with GNU make, using the strategies and example code from [this article](http://make.mad-scientist.net/papers/advanced-auto-dependency-generation/)

This project provides a template set of source, header, and makefiles to demonstrate makefile dependencies in action.

This project is a part of a multi-part series of projects which show you the basics of automatic dependency generation for C projects.  See  also:
 * Autoconf and Automake automatic dependency generation: https://github.com/cu-ecen-5013/autoconf-automake-example
 * CMake example : https://github.com/cu-ecen-5013/cmake-example

## Testing
Run `make test` to invoke the [test.sh](test.sh) script.  This script touches header and source files and checks make output to ensure exactly expected build steps are being invoked.

## Contributing
Pull requests are welcome for any improvement suggestions.  Please use the issues tab to open.
