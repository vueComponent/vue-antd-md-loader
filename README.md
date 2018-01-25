# vue-antd-md-loader

md-loader based on [vue-markdown-loader](https://github.com/QingWei-Li/vue-markdown-loader)

> Convert Markdown file to Vue Component using markdown-it.

## Example

[ant-design-vue](https://github.com/vueComponent/ant-design)

## Installation

```bash
# For Vue2
npm i vue-antd-md-loader -D
```

## Feature
- Hot reload
- Write vue script
- Code highlight


## Usage
[Documentation: Using loaders](https://webpack.js.org/concepts/loaders/)

`webpack.config.js` file:

```javascript
module.exports = {
  module: {
    rules: [
      {
        test: /\.md$/,
        loader: 'vue-antd-md-loader'
      }
    ]
  }
};
```

## License
WTFPL

