# css-inherit
css-inherit is a command-line version of [rework-inherit](https://github.com/reworkcss/rework-inherit/).

## Install
``` sh
$ npm install -g michaelrhodes/css-inherit
```

### Usage
#### cli
``` sh
# basic
$ cat some.css | css-inherit > build.css

# multiple files
$ css-combine some.css | css-inherit > build.css

# multiple files w/myth
$ css-combine some.css | css-inherit | myth > build.css

# multple files w/myth w/minification
$ css-combine some.css | css-inherit | myth | cleancss > build.css
```

### License
[MIT](http://opensource.org/licenses/MIT)
