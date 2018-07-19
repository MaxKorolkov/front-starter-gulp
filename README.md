# front-starter-gulp

This kit is a starter pack for frontend works. :octocat:

It includes:
- Scaffolding project
- Customized gulp file
- SASS with authoprefixer
- Concatenation and minification for CSS and JS files
- Include your CSS and JS library
- Compression images
- Dist for production

### Commands
`gulp` - gulp watch

`gulp build` - build for production

### Libs
All libs adds from `node_modules` and writes in tasks `gulpfile.js`

#### CSS Example
```javascript
gulp.task('css-libs', ['sass'], function () {
  return gulp.src([
    'node_modules/magnific-popup/dist/magnific-popup.css'
  ]) 
  ...
});
```

#### JS Example
```javascript
gulp.task('scripts', function () {
  return gulp.src([ 
    'node_modules/jquery/dist/jquery.min.js', 
    'node_modules/magnific-popup/dist/jquery.magnific-popup.min.js'
  ])
    ...
});
```
