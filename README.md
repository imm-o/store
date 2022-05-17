
+ pinyin-pro 
```js
  import { pinyin } from 'pinyin'
  pinyin('汉语拼音'); // 'hàn yǔ pīn yīn'
```
> [源 github](https://github.com/zh-lx/pinyin-pro)


<hr style="border: 0;border-top: 1px dashed #a2a9b6;" />


<p align="center">
  <a href="https://github.com/vizzuhq/vizzu-lib">
    <img src="https://github.com/vizzuhq/vizzu-lib-doc/raw/main/docs/readme/infinite-60.gif" alt="Vizzu" />
  </a>
  <p align="center"><b>Vizzu</b> - Library for animated data visualizations and data stories.</p>
</p> 

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
