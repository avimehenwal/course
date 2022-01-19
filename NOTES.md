## webpack

* good to have seperate environment files
* can use other dev server like `express` but you can use default webpack devserver too
* webpack `outputs` to memory unless saved to a directory/file.
* multiple loaders in webpack are processed on bottoms up, right to left direction

```js
use: ["babel-loader", "eslint-loader"]
```

1. `eslint-loader`
2. `babel-loader`


## Linting Tools

* avoid/skip running certain annoying rules

## Redux

* React context, not global, have to import to consume it
  * built into React
* How do we connect components to redux store?
  * how do we wire up redux to react components?