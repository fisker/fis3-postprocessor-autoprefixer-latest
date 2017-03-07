# fis3-postprocessor-autoprefixer-latest 

latest version autoprefixer for fis3..

[![npm](https://img.shields.io/npm/v/fis3-postprocessor-autoprefixer-latest.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-autoprefixer-latest) 
[![npm](https://img.shields.io/npm/dt/fis3-postprocessor-autoprefixer-latest.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-autoprefixer-latest) 
[![npm](https://img.shields.io/npm/dm/fis3-postprocessor-autoprefixer-latest.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-autoprefixer-latest)


## usage

    $ npm i -g fis3-postprocessor-autoprefixer-latest

```
// fis-conf.js

fis.match('*.{css,less,scss}', {
  preprocessor: fis.plugin('autoprefixer-latest', {
    browsers: ['last 2 versions']
  })
})
```

[more options](https://github.com/postcss/autoprefixer)

## links
fis3: [http://fis.baidu.com/](http://fis.baidu.com/)
autoprefixer: [https://github.com/postcss/autoprefixer](https://github.com/postcss/autoprefixer)
