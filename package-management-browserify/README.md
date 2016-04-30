```
$ npm install --save react react-dom babelify babel-preset-react
$ browserify -t [ babelify ] main.js -o bundle.js
```

> If you are using ES2015, you will want to also use the `babel-preset-es2015` package.
