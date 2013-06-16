# [AngularCordova](http://mgcrea.github.com/angular-cordova) [![Build Status](https://secure.travis-ci.org/mgcrea/angular-cordova.png?branch=master)](http://travis-ci.org/#!/mgcrea/angular-cordova)

AngularCordova is a set of modules that enables seamless integration of [Apache Cordova](https://cordova.apache.org) (also known as [Adobe PhoneGap](http://phonegap.com)) into your [AngularJS](http://angularjs.org) app.

+ Check the [documentation](http://mgcrea.github.com/angular-cordova) and [changelog](https://github.com/mgcrea/angular-cordova/wiki/Changelog).



## Quick start

+ Install the library with [Bower](http://bower.io):

>
``` bash
$ bower install angular-cordova
```

+ Inject the `cordova` module into your app module

>
``` javascript
angular.module('myApp', ['cordova']);
```



## Developers

Clone the repo, `git clone git://github.com/mgcrea/angular-cordova.git`.

AngularStrap is tested with `jasmine` running on both `karma` and `testem`

>
``` bash
$ npm install grunt-cli --global
$ npm install --dev
$ grunt test
```

You can build the latest version using `grunt`.

>
``` bash
$ grunt build
```


### Testing on real devices

Work is in progress with [node-ios-browser](https://github.com/mgcrea/node-ios-browser) to run end to end tests on the simulator.

+ [Testem](https://github.com/airportyh/testem)

Test are working with a custom suite `testem -f test/testem-cordova.json --browsers ios`.

Test are failing with the provided jasmine suite `testem -f test/testem.json --browsers ios`.

+ [Karma](https://github.com/karma-runner/karma)

Tests are failing with `karma start test/karma.conf.js --browsers ios-browser`.



## Contributing

Please submit all pull requests the against master branch. If your unit test contains JavaScript patches or features, you should include relevant unit tests. Thanks!



## Authors

**Olivier Louvignes**

+ http://olouv.com
+ http://github.com/mgcrea



## Copyright and license

    The MIT License

    Copyright (c) 2012 Olivier Louvignes

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.


