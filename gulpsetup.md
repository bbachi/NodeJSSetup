
# Getting Started

THis is the build tool for the NodeJS project. we can run all kinds of tasks zipping, compiling, transpiling etc..

#### Install the `gulp` command

```sh
npm install --global gulp-cli
```

#### Install `gulp` in your devDependencies

Run this command in your project directory:

```sh
npm install --save-dev gulp
```

#### Create a `gulpfile`

Create a file called `gulpfile.js` in your project root with these contents:

```js
var gulp = require('gulp');

gulp.task('default', function() {
  // place code for your default task here
});
```

#### Test it out

Run the gulp command in your project directory:

```sh
gulp
```

Voila! The default task will run and do nothing

To run multiple tasks, you can use `gulp <task> <othertask>`.
