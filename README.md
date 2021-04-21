# vue-demo

> learn

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```
vue水印功能

common中创建watermark.js文件，写入代码

页面中引入watermark，应用

``` vue
import { removeWatermark, setWaterMark } from '@/common/watermark'
  // 渲染水印
  mounted() {
    setWaterMark('liergouliergouliergouliergouliergou', '李二狗');
  },
  // 销毁水印
  // destroyed() {
  //     removeWatermark();
  // },

```