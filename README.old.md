# sku-react

[Create React App](https://create-react-app.dev/docs/adding-typescript) Adding TypeScript  
`yarn create react-app sku-react --template typescript`

## deploy

react-cli npm run build build資料夾

Deploy gh-pages
`$ yarn add gh-pages -D`

package.json

```js
"homepage": "https://jacobhsu.github.io/sku-react"

"scripts": {
  //...
  "predeploy": "yarn build",
  "deploy": "gh-pages -d build"
}
```

`$ yarn deploy`
