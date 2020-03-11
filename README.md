# webpackdemo
#https://www.webpackjs.com/guides/
webpack官网的demo

发现问题或者待跟踪
1.shimming  配置不生效，生成的bundle.js的大小没变  
new webpack.ProvidePlugin({
      //_: 'lodash'
      join: ['lodash', 'join']
    })
2.PWA
3.TypeScript  https://www.typescriptlang.org/docs/handbook/tsconfig-json.html
4.兼容：babel  https://babel.docschina.org/docs/en/usage
5.webpack.config.js resolve配置
6.thread-loader 可以将非常消耗资源的 loaders 转存到 worker pool 中。
7.node-sass
8.安全https://www.webpackjs.com/guides/csp/
9.跨域问题解决
10.public path
