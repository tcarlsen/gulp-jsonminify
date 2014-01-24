# gulp-jsonminify

Minifies blocks of JSON-like content into valid JSON by removing all whitespace and comments, using [JSON.minify](https://github.com/fkei/JSON.minify).

## Usage

```javascript
var jsonminify = require('gulp-jsonminify');

gulp.task('minify', function () {
    gulp.src(['path/to/files/*.json'])
        .pipe(jsonminify())
        .pipe(gulp.dest('dist'));
});
```

## LICENSE

(MIT License)