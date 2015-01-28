# Tutorial on Mocha at Codeship

See the tutorial at:

* [Using Mocha JS, Chai JS and Sinon JS to Test your Frontend JavaScript Code](http://blog.codeship.com/mocha-js-chai-sinon-frontend-javascript-code-testing-tutorial/)

                        $ npm install -g mocha
                        $ mkdir vendor
                        $ mocha init vendor

Include the chai browser build in your testing suite.

                <script src="vendor/chai.js" type="text/javascript"></script>


Use the chai.js file [from the root of the github project](https://github.com/chaijs/chai/blob/master/chai.js).
