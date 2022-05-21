
<!-- [![pinyin-pro Logo](https://i.ibb.co/26fJ5vF/pinyin-logo.png)](https://github.com/zh-lx/pinyin-pro) -->
### pinyin

**中文转拼音**

```javascript
  const { pinyin } = require('pinyin.min.js') 
  
  pinyin('汉语拼音'); // 'hàn yǔ pīn yīn'
```
> [源 github](https://github.com/zh-lx/pinyin-pro)



---



<!-- [![vizzu Logo](https://github.com/vizzuhq/vizzu-lib-doc/raw/main/docs/readme/infinite-60.gif)](https://github.com/vizzuhq/vizzu-lib) --> 

### vizzu  

**Library for animated data visualizations and data stories.** 

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

### popmotion  

**Animator’s JavaScript toolbox.**


```javascript
const { animate } = require("popmotion.min.js")

animate({
  from: 0, 
  to: 100,
  onUpdate: latest => console.log(latest)
})
```
> [源 github](https://github.com/Popmotion/popmotion)  
> [源 文档](https://popmotion.io/)



---



### calendar  

**公历年月日转农历数据 返回json**


```js
  const calendar = require('calendar.min.js') 

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



### valine

**Simple comment system base on [LeanCloud](https://www.leancloud.cn/).**

```js
  const Valine = require('valine.min.js)
  new Valine({
    el: '#vcomments',
    appId: 'Your appId',
    appKey: 'Your appKey'
  })
```
> [源 github](https://github.com/xCss/Valine)  
> [源 文档](https://valine.js.org/)

