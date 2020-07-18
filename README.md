## 百度贴吧移动端提取的默认表情包

[![](https://data.jsdelivr.com/v1/package/gh/microlong666/tieba_mobile_emotions/badge)](https://www.jsdelivr.com/package/gh/microlong666/tieba_mobile_emotions)

对应百度贴吧 app 版本号 11.6.8.2 ( 2020.7.13 更新)

### 表情包使用

#### 1、保存为图片直接使用

#### 2、使用 jsDelivr CDN 服务

格式：

`https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/image_emoticon(或接上数字2到124).png`

示例：

`https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/image_emoticon.png`

`https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/image_emoticon25.png`

可以直接得到

![1](https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/image_emoticon.png)

![2](https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/image_emoticon25.png)

#### 3、引入 Valine 等评论工具

开始前请先查阅 [Valine 的官方文档](https://valine.js.org/emoji.html)

其他评论系统请参阅其相关文档。

1. 设置 emojiCDN 为

``` js
emojiCDN: 'https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/',
//注意链接最后的/也要带上！！！
```

2. 配置表情 title 和图片映射

``` js
emojiMaps: {
    "tieba1":"image_emoticon.png",
    "tieba2":"image_emoticon2.png",
    "tieba3":"image_emoticon3.png",
    "tieba4":"image_emoticon4.png",
    "tieba5":"image_emoticon5.png",
    "tieba6":"image_emoticon6.png",
    "tieba7":"image_emoticon7.png",
    "tieba8":"image_emoticon8.png",
    "tieba9":"image_emoticon9.png",
    "tieba10":"image_emoticon10.png",
    "tieba11":"image_emoticon11.png",
    "tieba12":"image_emoticon12.png",
    "tieba13":"image_emoticon13.png",
    "tieba14":"image_emoticon14.png",
    "tieba15":"image_emoticon15.png",
    "tieba16":"image_emoticon16.png",
    "tieba17":"image_emoticon17.png",
    "tieba18":"image_emoticon18.png",
    "tieba19":"image_emoticon19.png",
    "tieba20":"image_emoticon20.png",
    "tieba21":"image_emoticon21.png",
    "tieba22":"image_emoticon22.png",
    "tieba23":"image_emoticon23.png",
    "tieba24":"image_emoticon24.png",
    "tieba25":"image_emoticon25.png",
    "tieba26":"image_emoticon26.png",
    "tieba27":"image_emoticon27.png",
    "tieba28":"image_emoticon28.png",
    "tieba29":"image_emoticon29.png",
    "tieba30":"image_emoticon30.png",
    "tieba31":"image_emoticon31.png",
    "tieba32":"image_emoticon32.png",
    "tieba33":"image_emoticon33.png",
    "tieba34":"image_emoticon34.png",
    "tieba35":"image_emoticon35.png",
    "tieba36":"image_emoticon36.png",
    "tieba37":"image_emoticon37.png",
    "tieba38":"image_emoticon38.png",
    "tieba39":"image_emoticon39.png",
    "tieba40":"image_emoticon40.png",
    "tieba41":"image_emoticon41.png",
    "tieba42":"image_emoticon42.png",
    "tieba43":"image_emoticon43.png",
    "tieba44":"image_emoticon44.png",
    "tieba45":"image_emoticon45.png",
    "tieba46":"image_emoticon46.png",
    "tieba47":"image_emoticon47.png",
    "tieba48":"image_emoticon48.png",
    "tieba49":"image_emoticon49.png",
    "tieba50":"image_emoticon50.png",
    "tieba51":"image_emoticon51.png",
    "tieba52":"image_emoticon52.png",
    "tieba53":"image_emoticon53.png",
    "tieba54":"image_emoticon54.png",
    "tieba55":"image_emoticon55.png",
    "tieba56":"image_emoticon56.png",
    "tieba57":"image_emoticon57.png",
    "tieba58":"image_emoticon58.png",
    "tieba59":"image_emoticon59.png",
    "tieba60":"image_emoticon60.png",
    "tieba61":"image_emoticon61.png",
    "tieba62":"image_emoticon62.png",
    "tieba63":"image_emoticon63.png",
    "tieba64":"image_emoticon64.png",
    "tieba65":"image_emoticon65.png",
    "tieba66":"image_emoticon66.png",
    "tieba67":"image_emoticon67.png",
    "tieba68":"image_emoticon68.png",
    "tieba69":"image_emoticon69.png",
    "tieba70":"image_emoticon70.png",
    "tieba71":"image_emoticon71.png",
    "tieba72":"image_emoticon72.png",
    "tieba73":"image_emoticon73.png",
    "tieba74":"image_emoticon74.png",
    "tieba75":"image_emoticon75.png",
    "tieba76":"image_emoticon76.png",
    "tieba77":"image_emoticon77.png",
    "tieba78":"image_emoticon78.png",
    "tieba79":"image_emoticon79.png",
    "tieba80":"image_emoticon80.png",
    "tieba81":"image_emoticon81.png",
    "tieba82":"image_emoticon82.png",
    "tieba83":"image_emoticon83.png",
    "tieba84":"image_emoticon84.png",
    "tieba85":"image_emoticon85.png",
    "tieba86":"image_emoticon86.png",
    "tieba87":"image_emoticon87.png",
    "tieba88":"image_emoticon88.png",
    "tieba89":"image_emoticon89.png",
    "tieba90":"image_emoticon90.png",
    "tieba91":"image_emoticon91.png",
    "tieba92":"image_emoticon92.png",
    "tieba93":"image_emoticon93.png",
    "tieba94":"image_emoticon94.png",
    "tieba95":"image_emoticon95.png",
    "tieba96":"image_emoticon96.png",
    "tieba97":"image_emoticon97.png",
    "tieba98":"image_emoticon98.png",
    "tieba99":"image_emoticon99.png",
    "tieba100":"image_emoticon100.png",
    "tieba101":"image_emoticon101.png",
    "tieba102":"image_emoticon102.png",
    "tieba103":"image_emoticon103.png",
    "tieba104":"image_emoticon104.png",
    "tieba105":"image_emoticon105.png",
    "tieba106":"image_emoticon106.png",
    "tieba107":"image_emoticon107.png",
    "tieba108":"image_emoticon108.png",
    "tieba109":"image_emoticon109.png",
    "tieba110":"image_emoticon110.png",
    "tieba111":"image_emoticon111.png",
    "tieba112":"image_emoticon112.png",
    "tieba113":"image_emoticon113.png",
    "tieba114":"image_emoticon114.png",
    "tieba115":"image_emoticon115.png",
    "tieba116":"image_emoticon116.png",
    "tieba117":"image_emoticon117.png",
    "tieba118":"image_emoticon118.png",
    "tieba119":"image_emoticon119.png",
    "tieba120":"image_emoticon120.png",
    "tieba121":"image_emoticon121.png",
    "tieba122":"image_emoticon122.png",
    "tieba123":"image_emoticon123.png",
    "tieba124":"image_emoticon124.png"
} 
```

> json、 toml、 yaml 均支持，请参照相应语法作出修改，支持与其他表情包叠加混用

JSON 格式如下

``` json
{
  "emojiCDN": "https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/",
  "emojiMaps": {
    "tieba1": "image_emoticon.png",
    "tieba2": "image_emoticon2.png",
    //...
  }
}
```

YAML 格式如下（注意缩进）

``` yaml
emojiCDN: https://cdn.jsdelivr.net/gh/microlong666/tieba_mobile_emotions/
emojiMaps:
  tieba1: image_emoticon.png
  tieba2: image_emoticon2.png
  #...
```

### 使用须知

本表情包**仅供学习交流与个人非营利性使用**，若使用本表情包产生版权纠纷本人概不负责

如有侵权请联系本人删除