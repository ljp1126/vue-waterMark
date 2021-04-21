# vue-demo

> learn

## Build Setup

``` bash
git clone https://github.com/ljp1126/vue-waterMark.git
cd vue-waterMark
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

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