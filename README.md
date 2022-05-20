
<!-- [![pinyin-pro Logo](https://i.ibb.co/26fJ5vF/pinyin-logo.png)](https://github.com/zh-lx/pinyin-pro) -->
<img src="https://i.ibb.co/26fJ5vF/pinyin-logo.png" height="80" width="200" alt="pinyin" />

```javascript
  import { pinyin } from 'pinyin.min.js'
  
  pinyin('汉语拼音'); // 'hàn yǔ pīn yīn'
```
> [源 github](https://github.com/zh-lx/pinyin-pro)


---



<!-- [![vizzu Logo](https://github.com/vizzuhq/vizzu-lib-doc/raw/main/docs/readme/infinite-60.gif)](https://github.com/vizzuhq/vizzu-lib) -->
<img src="https://github.com/vizzuhq/vizzu-lib-doc/raw/main/docs/readme/infinite-60.gif" alt="vizzu" />

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




---



<!-- [![popmotion Logo](https://user-images.githubusercontent.com/7850794/90245722-80926e80-de33-11ea-9c39-ea6c5b344217.png)](https://github.com/Popmotion/popmotion) -->
<img src="https://user-images.githubusercontent.com/7850794/90245722-80926e80-de33-11ea-9c39-ea6c5b344217.png" height="52" width="243" alt="popmotion" />

```javascript
import { animate } from "popmotion.min.js"

animate({
  from: 0, 
  to: 100,
  onUpdate: latest => console.log(latest)
})
```
> [源 github](https://github.com/Popmotion/popmotion)  
> [源 文档](https://popmotion.io/)


### calendar  

**公历年月日转农历数据 返回json**


```js
  import calendar from 'calendar.min.js'

  calendar.solar2lunar(1987,9,10);
  // { Animal: "兔", IDayCn: "初十", IMonthCn: "九月",ncWeek: "星期日" astro: "天蝎座", 
  // gzDay: "甲寅", gzMonth: "庚戌", gzYear: "丁卯",...}

  var lunar = calendar.solar2lunar();
  var 阳历 = lunar.cYear + '年' +lunar.cMonth +  '月' + lunar.cDay +'日（'+lunar.astro+')'
  var 农历 = lunar.lYear + '年' +lunar.IMonthCn+lunar.IDayCn+'，'+
  lunar.gzYear+'年'+lunar.gzMonth+'月'+lunar.gzDay+'日（'+lunar.Animal+'年）'

  // 阳历：2022年5月21日（双子座）
  // 农历：2022年四月廿一，壬寅年乙巳月甲戌日（虎年）
```
> [源 github](https://github.com/jjonline/calendar.js)  
> [源 文档](https://blog.jjonline.cn/userInterFace/173.html)



---