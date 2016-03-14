# Tutorial on Mocha at Codeship


See the tutorials at:

* [Using Mocha JS, Chai JS and Sinon JS to Test your Frontend JavaScript Code](http://blog.codeship.com/mocha-js-chai-sinon-frontend-javascript-code-testing-tutorial/)

* [Get your Frontend JavaScript Code Covered](https://nicolas.perriault.net/code/2013/get-your-frontend-javascript-code-covered/)

by Nicolas Perriault.


There are four branches:

      $ git branch -a
        async         # Example of asynchronous testing
        blanket       # Covering
      * master        # Simple example
        sinon         # Example of mocking with sinon

To install dependencies:

                        $ npm install -g mocha
                        $ mkdir vendor
                        $ mocha init vendor
                        $ npm run-script chai
                        $ npm run-script sinon
## BlanketJS

* [blanketjs](http://blanketjs.org/)

* The only file you need is [blanket.js](https://raw.github.com/alex-seville/blanket/master/dist/qunit/blanket.min.js). Download the library and reference it in your test runner.

```javascript
<script src="blanket.js"></script>
```
* Add a `data-cover` attribute to the script reference of each file you want covered

```javascript
<script src="my-library.js" data-cover></script>
```

