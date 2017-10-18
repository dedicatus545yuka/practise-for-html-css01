# practise-for-html-css01
还是魅族官网的一些练习，写是写好了，但是还是加些注释再传上来吧（html,css ）
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>页面主体练习</title>
    <link rel="stylesheet" href="魅族页面主体练习.css">
</head>
<body>
<!-- 设置两个容器，一个做上广告位，一个放下商品内容 -->
<div class="wrap1">
    <!-- 设置一个容器来做水平居中的作用 -->
    <div class="wrap1-1">
        <!-- 设置a标签实现广告的跳转功能 -->
        <a href="#" class="dgg"></a>
    </div>
</div>
<div class="wrap2">
    <div class="wrap2-2">
        <!-- 把内容分成两部分，一个头表，一个十方格 -->
        <div class="tt">
            <!-- 在头表中我都用p标签来罗列文本内容 -->
            <p class="p1">手机</p>
            <p class="p2">
                <a  class="p2-link" href="#">
                    热销机型
                </a>
            </p>
            <p class="p3">
                <a href="#" class="p3-link">
                    更多>
                </a>
            </p>
        </div>
        <div class="sfg">
            <!-- 在十方格这个容器中我用无序列表ul来罗列10个商品 -->
            <ul class="">
                <li class="">
                    <a class="gz-link" href="#">
                    <img src="http://a3.qpic.cn/psb?/V118JuTr3rHMrA/occM6UJ2iIoeAr9UR27NyAJ0ZrG4GCytaKeIHm0q48A!/b/dPIAAAAAAAAA&bo=9ABSAQAAAAARB5c!&rf=viewer_4">
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a3.qpic.cn/psb?/V118JuTr3rHMrA/8PtY3vt9*wmXdpov6ul7a6aFylOchbTH*hRhNTeYyhE!/b/dPIAAAAAAAAA&bo=tAC0AAAAAAADByI!&rf=viewer_4">
                        <!-- 在图片下方加入一些文本内容 -->
                        <h4 class="">魅蓝 Note6 騷紅限定套装</h4>
                        <h6 class="">购机享6期免息</h6>
                        <h3 class="">￥1699</h3>
                        <!-- 设置一个右上图标 -->
                        <div class="ystb"><p class="p4">新品</p></div>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/iIR*24EZoHT09J3uc*U1J3FOULQ4ryjK12VIwh0kPXo!/m/dFsBAAAAAAAA&bo=tAC0AAAAAAADByI!&rf=photolist">
                        <h4 class="">魅蓝 6</h4>
                        <h6 class="">八核CPU+AI智能加速</h6>
                        <h3 class="">
                            ￥699
                            <span class="qi">起</span>
                        </h3>
                        <div class="ystb"><p class="p4">新品</p></div>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/ZF0IVHjaGaSw5BDp4RJxyRg.CsXIITxB43.zUno.B4o!/m/dPMAAAAAAAAA&bo=tAC0AAAAAAARBzA!&rf=photolist">
                        <h4 class="">魅族 PRO 7 Plus</h4>
                        <h6 class="">赠价值300元大礼券 12期免息</h6>
                        <h3 class="">
                            ￥3200
                            <span class="qi">起</span>
                            <span class="yjia">￥3580</span>
                        </h3>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/YNZN2ZtfGwUsLrHQdy69e25k54t.IzxzM6b2Rko8acQ!/m/dPMAAAAAAAAA&bo=tAC0AAAAAAADByI!&rf=photolist">
                        <h4 class="">魅蓝 X</h4>
                        <h6 class="">直降300元 强劲电芯</h6>
                        <h3 class="">
                            ￥1199
                            <span class="yjia">￥1499</span>
                        </h3>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/WODh5LjSgVB380m6DIcuidHbFoQ*eMxBKyzUQ6CIw6I!/m/dPMAAAAAAAAA&bo=tAC0AAAAAAARBzA!&rf=photolist">
                        <h4 class="">魅蓝 Note5</h4>
                        <h6 class="">限时特惠50元</h6>
                        <h3 class="">
                            ￥1049
                            <span class="qi">起</span>
                            <span class="yjia">￥1099</span>
                        </h3>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/2i93k.aeRzlhciCaJA2rGGlUAcXPdOsfsa*BMjKcwi8!/m/dPMAAAAAAAAA&bo=tAC0AAAAAAADByI!&rf=photolist">
                        <h4 class="">魅蓝 E</h4>
                        <h6 class="">视觉盛宴</h6>
                        <h3 class="">
                            ￥999
                        </h3>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/0XJ3hBlQoOALulHdI0yYu4Wop78dsTPSSor6*aYpNeM!/m/dPMAAAAAAAAA&bo=tAC0AAAAAAARBzA!&rf=photolist">
                        <h4 class="">魅蓝 E2</h4>
                        <h6 class="">限时特惠100元</h6>
                        <h3 class="">
                            ￥1199
                            <span class="qi">起</span>
                            <span class="yjia">￥1299</span>
                        </h3>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a3.qpic.cn/psb?/V118JuTr3rHMrA/CZZ4HPOkZHe7nI6fSqK7SaUixg45xegCK.GrhcOCJ*g!/m/dPIAAAAAAAAA&bo=tAC0AAAAAAADByI!&rf=photolist">
                        <h4 class="">魅蓝 5s</h4>
                        <h6 class="">礼盒版限时特惠</h6>
                        <h3 class="">
                            ￥799
                            <span class="qi">起</span>
                        </h3>
                    </a>
                </li>
                <li class="">
                    <a class="gz-link" href="#">
                        <img class="im" src="http://a4.qpic.cn/psb?/V118JuTr3rHMrA/jbLNbGmsN3fGZvf9exqLKv.EF0J.XoFkiK0SWIzLyPM!/m/dPMAAAAAAAAA&bo=tAC0AAAAAAARBzA!&rf=photolist">
                        <h4 class="">魅族PRO 6s</h4>
                        <h6 class="">购机享3期免息</h6>
                        <h3 class="">
                            ￥2299
                        </h3>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</div>
</body>
</html>
```

`魅族页面主体练习.CSS`

```CSS
body {
    margin: 0px;
    /* 去除浏览器默认的8像素外边距 */
}
a {
    text-decoration: none;
    /* 去除所有a标签带来的下划线 */
}
.wrap1,.wrap2{
    width: 1423px;
    /* 给两最外面的容器设置定宽 */
}
.wrap1-1,.wrap2-2 {
    width: 1240px;
    padding: 25px 0;
    /* 给中容器设置内边距拉开两个盒子的距离 */
    margin:0 auto;
}
.dgg {
    display: block;
    width: 1240px;
    height: 120px;
    /* 给a标签设置盒子属性并且设置宽度高度以适应图片 */
    background-image: url("http://a4.qpic.cn/psb?/V118JuTr3rHMrA/R1*1jwZqMBKF.8Riu8T.eVTy9Q4VIJFkmvCnSHiKK04!/m/dPMAAAAAAAAA&bo=2AR4AAAAAAARB5Q!&rf=photolist");
    background-repeat: no-repeat;
    /* 给a标签嵌入背景图片，平铺方式不重复*/
}
.wrap2 {
    background-color: #f5f5f5;
}
.tt {
    height: 32px;

}
p {
    margin: 0px;
    text-align: center;
    /* 给所有p标签重置基本的样式 */
}
.p1,.p2 {
    float: left;
    /* 开启浮动让元素脱离文档流实现水平排列 */
}
.p1{
    font-size: 24px;
    color: #333;
}
.p2 {
    padding:11px 0 2px;
    margin-left: 30px;
    /* 设置偏移量控制元素的位置 */
    border-bottom: 2px solid #00c3f5;
    /* 给下边框设置样式 */

}
.p2-link {
    color: #00c3f5;
    /* 给字体设置颜色 */
}
.p3 {
    float: right;
    padding:11px 0 0;
    /* 给元素设置右浮动让其居右 */
}
.p3-link {
    color: #333;
}
.p3-link:hover {
    color: #00c3f5;
    /* 给元素设置伪类鼠标指向时颜色变为蓝色 */
}
.sfg {
    margin-top: 25px;
    /* 设置偏移量让其与头表拉开距离 */
}
ul {
    padding: 0px;
    margin: 0px;
    list-style: none;
    /* 覆盖浏览器默认的样式 */
    overflow: hidden;
    /* 解决高度塌陷的问题 */
    width: 1250px;
    /* 通过设置定宽来解决列表项排列的问题 */
}
li {
    float: left;
    width: 244px;
    height: 338px;
    /* 给列表项设置基本样式*/
    margin-right: 5px;
    margin-bottom: 5px;
    /* 给每个项之间设置一段间隔 */
}
.gz-link {
    display: inline-block;
    width: 244px;
    height: 338px;
    background-color: #fff;
    text-align: center;
    /* 给a标签设置基本样式 */
    position: relative;
    /* 开启定位让子元素可以通过定位来设置偏移量 */
}
.im {
    margin-top: 40px;
}
h4,h6,h3 {
    margin: 0;
    padding: 0;
    list-style: none;
    font-weight: 400;
    /* 给文本内容设置基本样式，覆盖浏览器预设的样式 */
}
h4 {
    font-size: 14px;
    color: #555757;
    margin-top: 40px;
}
h6 {
    font-size: 12px;
    color: #999;
    margin-top: 2px;
}
h3 {
    padding-right: 2px;
    margin: 0 4px;
    font-size: 14px;
    color: #e02b41;
}
.qi {
    font-size: 12px;
}
.yjia {
    margin: 0;
    color: #b2b2b2;
    font-size: 12px;
    text-decoration: line-through;
    /* 文本样式为中间贯通线 */
    padding-right: 2px;
}
.ystb {
    width: 40px;
    height: 40px;
    color: #fff;
    background-color: #00c3f5;
    border-radius: 50%;
    /* 打磨盒子的边角 */
    font-size: 12px;
    position: absolute;
    top: 16px;
    right: 16px;
}
.p4 {
    margin-top: 12px;
}
```
### 惯例的还是附上一张效果图  

！[效果图](http://a4.qpic.cn/psb?/V118JuTr3rHMrA/UUuNPe8Pdn5zVETUwTP5SvIRmxGkZAL9ox8ZSoNpeH4!/m/dPMAAAAAAAAA&bo=sQOAAgAAAAADBxI!&rf=photolist)



