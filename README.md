
# 传送门
 (现只支持高二，其他可能会报错，也可能导致网站奔溃)
### [点击我进行超时空传送](http://49.234.205.220:81/login.html)
## 预览
#### 由于有许多涉嫌个人隐私的部分，只展示部分
 ![电脑端](https://cdn.jsdelivr.net/gh/JiangNoah/ImgHosting/img/20200330151532.png)
 ![手机端](https://cdn.jsdelivr.net/gh/JiangNoah/ImgHosting/img/20200330151311.png)
 
 ---
## 2020年3月30日
 + 修复小量BUG
 + 完成各部分衔接
 + 完成时间轴部分
 + 对于未完成部分启用支持系统
 + 完成预期目标
---
## 2020年3月29日
 + 修复大量BUG
  + 代码不规范/概念混淆导致函数用错
  + HASMAP和LIST不同之处没注意
  + 修复登录机制重大问题
  + 修复GUID获取问题
  + 修复图表大小问题
  + ... 
 + 优化数据与数据之间关联与关系
 + 利用后端渲染完成图表部分
 + 利用AJAX完成品行和寄言部分
  + 加入一言
 + 剩余:各个单页连接，时间轴，关于
---
## 2020年3月28日
 + 再次完善cookies机制
   + 问题还是很多
   + 现实中很难遇到，但一旦遇到就很棘手，未雨绸缪，当然也稍稍降低了效率
 + 修整小方舟
 + 重写个人信息获取部分
   + 增加性别，学号
 + 完成学业，品德，运动部分后端，预计明天可完成预期目标
 + 学习PJAX，可能会运用在YGDH
 + 决定采取后端渲染和前端AJAX配合使用
---
## 2020年3月27日
 + 修复B2A小单页
 + 修整小方舟
---
## 2020年3月26日
 + 完善login的自动填写ID
 + 完善cookies获取机制
 + 完成个人信息获取部分
 + 完善develop.html
---

## 2020年3月25日
 + 成功利用local实现自动填写id
 + 完成大部分index的信息获取
---
## 2020年3月24日
 + 今天训练了一下AJAX不过没啥进步，做了一个B2A的小网页
 + 新增想法:利用local设置id方便下次自动登录
---
## 2020年3月23日晚
 + 针对今天遇到的大问题，最终确定原因为被安全限制（主要是origin和refer，虽然可以修改，但无法在网页实现，只能由服务端实现），所以决定就此放弃，改为自行登录
 + 这个可能早就在预料之中，不过今天还误以为可以实现，导致希望扑空，难免失落
---
## 2020年3月23日
 + 今天可能是最困难的一天了，同样的方式post却始终无法实现，每次都是200 failed！
    + 最痛苦的抓包精力莫过于此，期待早日解决
 + 完善了登录cookies获取机制，避免获取不到和二次获取的情况
 + 
---
## 2020年3月22日
  + 第一次使用JS开发
    + 基本完美利用JQ完成理想效果
	+ 使用AJAX完成前后端交互，处理json
  + 基本完成登录系统的开发，速度足够
    + 今日最大困难皆因“登录”与“登陆”
---
## 2020年3月21日
  - 今天正式进入后端开发
  - 登录系统正在开发中
  - 学习网页DOM解析部分
    * 优点不顺手，总体来说没有像json处理一样方便，而且只能取元素，不能置元素，对于网页也只能解析
---
## 2020年3月20日
  + 增加block空行块的自适应
  + 新建LOGIN.HTML
	+ 上滑登录动画
	+ 细节动效
	+ 契合主页切换
---
## 2020年3月19日
 + 完善侧边栏按钮
	+ 全屏按钮JStoggle控制
	+ 上滑按钮JQ显示隐藏及判断
	+ 移动端隐藏
	+ CSS完善多侧边栏样式
 + 完善表格
  + padding边框显示
  + 去除大多数边框border仅保留border-bottom
---
*更久的记录已丢失*

---

## 技术栈
 + CSS选择器
 + 抓包DEBUGGER
 + JSON处理
 + EPL\ESP
 + HTML/CSS/JS:响应式布局
 + JQUERY
 + AJAX
 + 各种前端JS,CSS库:mdui,bootstrap
 + 数据库处理:MYsql,SQLlite
 + CDN加速
 + 后端渲染
 + ECHARTS图表
 + 爬虫\HTML网页DOM解析
 + NPM\GIT
 + 。。。还有更多

## 缺陷
 + 有些多余处理（未雨绸缪之用）降低些许效率
 + 因跨域安全问题，未完成翼生涯部分自动登录
 + 许多衔接部分还有欠缺
 + 没有使用一些高效率的库:VUE(下阶段学习这个)
## 寄言
   终于等到机会说这番话了，经过了一个月零零总总的时间煎熬的开发，现如今鄞高导航1.0基本完成。这些时间里，前端开发占大部分，但后端开发也占据一些时间。
 我原以为后端会快一点，但没成想被BUG缠身，幸好没有深陷泥淖之中。随着代码量的增加，这维护起来也是犹如牵一发而动全身的困难。好了，废话不多说。
   先说说原由，大部分原因是基于我想学习大前端开发，所以拿这个项目边学便练。刚才是主要原因，再说说直接原因:原来鄞高的网站使用国内非常”成熟“的thinkPHP开发，缺少移动端自适应/响应式布局。
 有些地方看着也挺费劲的。还有个间接原因是[这个](https://www.bilibili.com/video/av89187884)。总之，趁这次居家学习的空隙，我独自完成了这个项目一期（都是泪）。
   说说开发经历：原本都是停留在脑海中的想法，在一个合适的时机，天时地利人和，于是凭空而出。吼吼吼！这段时间里是一边鸽一边写，像只泥鳅在泥地里翻腾，终于游出泥地，然后**。
 如果之后还有勇气的话，我会用VUE重构这些网页😂。
   补充:这个鄞高导航是一个开源项目，如果有任何意见和疑问，可以QQ我:1677568218.

## 附赠一份脑图
 ![脑图](https://cdn.jsdelivr.net/gh/JiangNoah/ImgHosting/img/20200330151224.png)
