
[![pinyin-pro Logo](https://i.ibb.co/26fJ5vF/pinyin-logo.png)](https://github.com/zh-lx/pinyin-pro)

```javascript
  import { pinyin } from 'pinyin'
  
  pinyin('汉语拼音'); // 'hàn yǔ pīn yīn'
```
> [源 github](https://github.com/zh-lx/pinyin-pro)


 



[![vizzu Logo](https://github.com/vizzuhq/vizzu-lib-doc/raw/main/docs/readme/infinite-60.gif)](https://github.com/vizzuhq/vizzu-lib)

```javascript
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



[![popmotion Logo](https://user-images.githubusercontent.com/7850794/90245722-80926e80-de33-11ea-9c39-ea6c5b344217.png)](https://github.com/Popmotion/popmotion)

```javascript
import { animate } from "popmotion"

animate({
  from: 0, 
  to: 100,
  onUpdate: latest => console.log(latest)
})
```
> [源 github](https://github.com/Popmotion/popmotion)  
> [源 文档](https://popmotion.io/)

