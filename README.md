<h2 align="center">Installation</h2>

```sh
npm i -D link-loader
```

<h2 align="center">Usage</h2>

```js
```js
{
  test: /\.html$/,
  loader: 'file-loader?name=[path][name].[ext]!extract-loader!link-loader'
}
``````

in index.html use this as 

```html
<link rel="import" href="my-html-file.html">
```

<h2 align="center">Advantages over html-loader</h2>

1. Link import support
2. You can write es6 inside html
3. Uses [parse5](https://github.com/inikulin/parse5) which parses HTML the way the latest version of your browser does. Does not use any regex to parse html.

### Like it?

:star: this repo


### Found a bug?

Raise an issue!

