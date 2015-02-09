# Tutorial on Mocha at Codeship

See the tutorial at:

* [Using Mocha JS, Chai JS and Sinon JS to Test your Frontend JavaScript Code](http://blog.codeship.com/mocha-js-chai-sinon-frontend-javascript-code-testing-tutorial/)

There are three branches:

      $ git branch -a
        async         # Example of asynchronous testing
      * master        # Simple example
        sinon         # Example of mocking with sinon

To install dependencies:

                        $ npm install -g mocha
                        $ mkdir vendor
                        $ mocha init vendor
                        $ npm run-script chai
                        $ npm run-script sinon
