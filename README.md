
[![pinyin-pro Logo](https://i.ibb.co/26fJ5vF/pinyin-logo.png)](https://github.com/zh-lx/pinyin-pro)

```js
  import { pinyin } from 'pinyin'
  pinyin('汉语拼音'); // 'hàn yǔ pīn yīn'
```
> [源 github](https://github.com/zh-lx/pinyin-pro)


 



[![vizzu Logo](https://github.com/vizzuhq/vizzu-lib-doc/raw/main/docs/readme/infinite-60.gif)](https://github.com/vizzuhq/vizzu-lib)

```js
import Vizzu from 'vizzu.min.js'
const data = {
  series: [
    { name: 'Foo', values: ['Alice', 'Bob', 'Ted'] },
    { name: 'Bar', values: [15, 32, 12] },
    { name: 'Baz', values: [5, 3, 2] }
  ]
};
let chart = new Vizzu('myVizzu', { data });
chart.animate({ x: 'Foo', y: 'Bar' });
chart.animate({
  color: 'Foo',
  x: 'Baz', 
  geometry: 'circle' 
})
```
> [源 github](https://github.com/vizzuhq/vizzu-lib)  
> [源 文档](https://lib.vizzuhq.com/latest/)
