# Tutorials on Mocha, Blanket and Karma

See the tutorials at:

* [Using Mocha JS, Chai JS and Sinon JS to Test your Frontend JavaScript Code](http://blog.codeship.com/mocha-js-chai-sinon-frontend-javascript-code-testing-tutorial/)
by Nicolas Perriault.

* [Get your Frontend JavaScript Code Covered](https://nicolas.perriault.net/code/2013/get-your-frontend-javascript-code-covered/)
by Nicolas Perriault.

* [Karma configuration file](http://karma-runner.github.io/0.12/config/configuration-file.html)

* [Travis CI and Karma](http://karma-runner.github.io/0.12/plus/travis.html)


There are six branches:

      $ git branch -a
        async         # Example of asynchronous testing
        blanket       # Covering
        master        # Simple example
        sinon         # Example of mocking with sinon
        karma         # Example of how to use karma
        travis        # Example of how to use karma with travis

[![Build Status](https://travis-ci.org/crguezl/mocha-chai-sinon--example.svg?branch=travis)](https://travis-ci.org/crguezl/mocha-chai-sinon--example)

To install dependencies:

                        $ npm install -g mocha
                        $ mkdir vendor
                        $ mocha init vendor
                        $ npm run-script chai
                        $ npm run-script sinon

Contents  of `.travis.yml`:

                        language: node_js
                        node_js:
                          - "0.10"
                        before_script:
                          - export DISPLAY=:99.0
                          - sh -e /etc/init.d/xvfb start
                        branches:
                          only:
                            - travis
