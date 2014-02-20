*This repository is a mirror of the [component](http://component.io) module [kaerus-component/sda](http://github.com/kaerus-component/sda). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/kaerus-component-sda`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
sda
===

Self decrypting archive, ported from http://jgae.de/sda.htm

Example
=======
```javascript
var Sda = require('kaerus-component-sda');

var a = new Sda();

a.encrypt("something secret","passphrase"); // => '4IAHl5T2k4bgPq5s2QI'

a.decrypt('4IAHl5T2k4bgPq5s2QI',"passphrase") // => 'something secret'
```




