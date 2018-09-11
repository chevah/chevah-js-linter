# Chevah JS Linter - a fork of Closure Linter
# Closure Linter - a style checker for ES5 JavaScript

Since **closure linter is deprecated** I have forked it in an attempt to delay
the migration to Java based tool and be able to continue to use Python.

It has the same command names as Closure Linter.

## Installation

To install the application, run `python ./setup.py install`

After installing, you get two helper applications installed into `/usr/local/bin`:

* `gjslint.py` - runs the linter and checks for errors
* `fixjsstyle.py` - DEPRECATED and not updated


## Testing

Using setuptools `python setup.py test`

Using virtualenv (see setup.py for dependecies)
`python closure_linter/full_test.py`

You can also run a single test (might need to udpate the test to initialize
the flags) `python closure_linter/fixjsstyle_test.py`

Or run a single functional tests
`python closure_linter/full_test.py ends_with_block.js`
