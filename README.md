#Learning to automate tasks with Gulp

### Requirements

- Install Node
	- on OSX install [home brew](http://brew.sh/) and type `brew install node`
	- on Windows install [chocolatey](https://chocolatey.org/)
    - Read here for some [tips on Windows](http://jpapa.me/winnode)
    - open command prompt as administrator
        - type `choco install nodejs`
        - type `choco install nodejs.install`
- On OSX you can alleviate the need to run as sudo by [following these instructions](http://jpapa.me/nomoresudo). I highly recommend this step on OSX
- Open terminal
- Type `npm install -g node-inspector bower gulp`

## Quick Start
clone this repo and run the content locally
```bash
$ npm install
$ bower install
$ npm start
```

## Creating gulpfile.js

create a new file called gulpfile.js and add your first gulp task:

```js
var gulp = require('gulp');

gulp.task('hello-world', function() {
	console.log('My First Task running...');
});
```
