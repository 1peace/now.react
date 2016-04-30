```
$ npm install --save react react-dom babel-preset-react babel-loader babel-core
$ webpack main.js bundle.js --module-bind 'js=babel-loader'
```

> If you are using ES2015, you will want to also use the `babel-preset-es2015` package.
