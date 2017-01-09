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

### Like it?

:star: this repo


### Found a bug?

Raise an issue!

