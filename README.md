# React-Mobx Demonstration
## Tech used
- [x] React v15
- [x] Mobx v2.5
- [x] Mobx-react
- [x] React-router v4
- [x] mobx-react-router v4
- [x] antd v2
- [x] react-scripts
- [x] [create-react-app](https://github.com/facebookincubator/create-react-app)
- ……
 
## How to run
- Install: `npm install(yarn)`
- Run: `npm start` Then open [http://localhost:3000](http://localhost:3000/) to see the app.
- Build: `npm run build`


## How to use Mobx（Decorators）

> I use the `creat-react-app` to creat my app.

You can add the `transform-decorators-legacy` yourself in `node_modules/react-scripts/config/babel.dev.js` and `babel.prod.js`,like this:

- add this code into `presets`:

```
require.resolve('babel-preset-stage-1'),
require.resolve('babel-preset-es2015')
```
- add this code into `plugins` first line:
```
require.resolve('babel-plugin-transform-decorators-legacy'),
```
