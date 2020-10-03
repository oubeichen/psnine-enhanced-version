## Require
- Node
- npm
- Git

![psnine](https://img.shields.io/badge/-PSNINE-black?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAMAAAAp4XiDAAAAMFBMVEVHcEw0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNs0mNuEOyNSAAAAD3RSTlMAQMAQ4PCApCBQcDBg0JD74B98AAABN0lEQVRIx+2WQRaDIAxECSACWLn/bdsCIkNQ2XXT2bTyHEx+glGIv4STU3KNRccp6dNh4qTM4VDLrGVRxbLGaa3ZQSVQulVJl5JFlh3cLdNyk/xe2IXz4DqYLhZ4mWtHd4/SLY/QQwKmWmGcmUfHb4O1mu8BIPGw4Hg1TEvySQGWoBcItgxndmsbhtJd6baukIKnt525W4anygNECVc1UD8uVbRNbumZNl6UmkagHeRJfX0BdM5NXgA+ZKESpiJ9tRFftZEvue2cS6cKOrGk/IOLTLUcaXuZHrZDq3FB2IonOBCHIy8Bs1Zzo1MxVH+m8fQ+nFeCQM3MWwEsWsy8e8Di7meA5Bb5MDYCt4SnUbP3lv1xOuWuOi3j5kJ5tPiZKahbi54anNRaaG7YElFKQBHR/9PjN3oD6fkt9WKF9rgAAAAASUVORK5CYII=&link=https://www.psnine.com/)
![install](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/swsoyee/swsoyee/master/public/data.json&label=installs&query=$.psnine_enhance_install[0]&color=orange&style=flat-square)
![Last commit](https://img.shields.io/github/last-commit/swsoyee/psnine-enhanced-version.svg?style=flat-square)
![license](https://img.shields.io/github/license/swsoyee/psnine-enhanced-version.svg?style=flat-square)

- `git clone https://github.com/SettingDust/webpack-tampermonkey.git`
- `npm i`
- `npm run dev`
- Copy the content of `./test/header.js` to the TamperMonkey script editor.
- Open a webpage.

## Features

-   Test without `Ctrl+V`
-   Build a public version easily.

- 🌙 增加`黑夜模式`主题选择<sup>4</sup>。
- ⚙️ `自动黑夜模式`<sup>2</sup>。
- 👮 红色高亮特定`用户ID`（默认高亮管理员）<sup>1</sup>。
- 🚫 增加`黑名单`和`屏蔽词过滤`功能，屏蔽不想看到的一切发言。
- ⏬ 增加`回到底部`按钮，快速跳转**回复框**或者**翻页**处。
- 🈲 `刮刮条文字`鼠标悬浮显示。
- ✅ 每日打开页面即可**自动签到**。
- 🤼‍♂️ [`约战`](https://psnine.com/battle)页面可以选择不显示发起用户头像。
- 🔧 点击P9页面的右上角`我的` ➡ `插件设置` 可进行插件具体设置<sup>1</sup>。

- [webpack-tampermonkey](https://github.com/momocow/webpack-tampermonkey)

## Example
- [biliplus-material](https://github.com/SettingDust/biliplus-material)
- [RSSHelper](https://github.com/BangumiSystem/RSSHelper)

- 🗣 增加蓝色`楼主`标识，更易区分`楼主`与`回帖者`<sup>1</sup>。
- 🖼 鼠标悬浮预览`-插图-`内容，无需点击打开查看图片。
- 💬 帖子中被`@用户`的发言内容显示于同层，内容过长则截取部分内容，鼠标悬浮即可完整查看。
- 🏗 增加回帖`楼层数`信息。
- 🈵 创建机因时实时**显示字数**，无字数被截后需重新修改的担忧。
- 📝 发表主题帖时`BBCode`转换结果**实时预览**（仅支持部分），所见即所得。
- 🙋‍♂️ [`问答`](https://psnine.com/qa)中根据解决状态使用**图标**表示以便快速识别。
- 🔍 鼠标**悬浮头像**显示用户**个人主页**主要信息。
- 🏆 攻略贴中显示自己的奖杯获得情况。

---
<img src="https://raw.githubusercontent.com/swsoyee/psnine-enhanced-version/master/screenshots/foreignCurrency.png" width="250" align="right" style="max-width: 50%">

### 💸 数折查看强化

- 📉 [`数折`](https://psnine.com/dd/HP9000-CUSA08392_00-ASIAPLACEHOLDER1)中增加`价格走势图`，快速了解**走势**和**史低**。
- 💱 [`数折`](https://psnine.com/dd)和`活动`页面增加人民币价格换算，无需自己进行价格换算。
- 🈹 根据**降价幅度**变更游戏标题颜色`💚<20%` `💛<50%` `🧡<80%` `💖>80%`，快速区分最大优惠。
- 🈹 [`数折`](https://psnine.com/dd)和`活动`页面增加`只看史低`功能按键~~不花任何一分冤枉钱~~。

---
<img src="https://raw.githubusercontent.com/swsoyee/psnine-enhanced-version/master/screenshots/trophySummary.png" width="300" align="right" style="max-width: 50%">

### 🏆 奖杯信息强化

- 📈 [`游戏`](https://psnine.com/psngame/15295)界面**奖杯类型比例**，**获得时间**等汇总图表。
- 🔖 [`游戏`](https://psnine.com/psngame)界面降低**无白金**的游戏图标可适度，方便区分有无白金。
- 🗃 `奖杯`界面增加`奖杯汇总列表`，无需滚屏迅速识别**未获得奖杯**和**Tips**有无。
- ↪ 进入**游戏页**默认`跳转`到自己主页下的该游戏页面<sup>1</sup>。
- ⚙️ **游戏页**增加`获得时间`排序<sup>2</sup>。
- 📝 `奖杯心得`页面输入框可缩放大小<sup>1</sup>。
- 🈚 `奖杯`界面增加`尚未获得`奖杯筛选按钮。
- 💯 `测评评分`界面增加`均分`信息<sup>2</sup>。
- 📈 [`奖杯心得`](https://psnine.com/trophy/12518001)界面增加**根据顶数排序**功能<sup>3</sup>。

---

## 💻 可用平台
||Chrome|FireFox|Edge|Maxthon|QQ浏览器|360浏览器|
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| | <img src="https://raw.githubusercontent.com/swsoyee/psnine-night-mode-CSS/master/icon/chrome-512.png" width="64px"></img>| <img src="https://raw.githubusercontent.com/swsoyee/psnine-night-mode-CSS/master/icon/512px-Firefox_Logo%2C_2017.svg.png" width="58px"></img> | <img src="https://raw.githubusercontent.com/swsoyee/psnine-night-mode-CSS/master/icon/edge.png" width="64px"></img>|<div align="center"> <img src="https://raw.githubusercontent.com/swsoyee/psnine-night-mode-CSS/master/icon/Maxthon.png" width="58px"></img></div> |<div align="center"> <img src="https://raw.githubusercontent.com/swsoyee/psnine-night-mode-CSS/master/icon/qq.jpg" width="64px"></img></div> |  <div align="center"><img src="https://raw.githubusercontent.com/swsoyee/psnine-night-mode-CSS/master/icon/360 Security Browser.png" width="60px"></img></div>
|<div align="center">Tampermonkey</div>|<div align="center">🉑</div>|<div align="center">🉑</div>|<div align="center">🉑</div>||<div align="center">🉑</div>|<div align="center">🉑</div>|
|<div align="center">Violentmonkey</div>|<div align="center">🉑</div>|<div align="center">🉑</div>||<div align="center">🉑</div>||<div align="center">🉑</div>|

若启用了脚本后无明显效果请确认**浏览器**和**插件**都处于最新版状态。如无法成功使用请到[`提issue`](https://github.com/swsoyee/psnine-night-mode-CSS/issues/new)报告。

## 📥 安装地址

详情参照[`Greasy Fork`](https://greasyfork.org/zh-CN/scripts/375985-psn%E4%B8%AD%E6%96%87%E7%BD%91%E5%8A%9F%E8%83%BD%E5%A2%9E%E5%BC%BA)。

## ❕ 附注

1. 功能由[`@mordom0404`](https://psnine.com/psnid/mordom0404)提供。
2. 功能由[`@Nathaniel_Wu`](https://github.com/Nathaniel-Wu)提供。
3. 功能由[`@JayusTree`](https://github.com/Jiangyu-Wang)提供。
4. 如果使用插件内的**黑夜模式**时存在瞬时白转黑的情况，建议关闭插件中的**黑夜模式**，使用`Stylus`或者`Stylish`扩展安装[`CSS`](https://userstyles.org/styles/167244/p9)版`黑夜模式`，或者在[`Greasy Fork`](https://greasyfork.org/zh-CN/scripts/376181-p9%E5%A4%9C%E9%97%B4%E6%A8%A1%E5%BC%8F)上安装独立插件版**黑夜模式**。

## 👥 项目贡献者

<a href="https://github.com/swsoyee/psnine-enhanced-version/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=swsoyee/psnine-enhanced-version" />
</a>

Made with [contributors-img](https://contributors-img.web.app).

## 🗣 交流反馈

<img src="https://raw.githubusercontent.com/swsoyee/psnine-enhanced-version/master/screenshots/qqGroup.JPG" width="35%" />

## 🌙夜间模式CSS版

<details>
<summary>点击查看详情</summary>

[![Install with Stylish](https://img.shields.io/badge/Install%20with-Stylish-00adad.svg)](https://userstyles.org/styles/167244/p9)

---
<img src="https://raw.githubusercontent.com/swsoyee/psnine-enhanced-version/master/screenshots/homepage.png" width="420" align="right" style="max-width: 50%">

本CSS样式为[`P9`](https://psnine.com/)的夜间模式，为了方便夜间使用而编写的。
由于自己日常使用界面有限，可能并不是所有元素都进行了合适的更改，如有发现希望得到各位的反馈以便后期更新。

⭐全站启用护眼黑色调显示
⭐支持帖子的隐藏文字[musk]鼠标划过显示(可选)

### 更新记录

- v1.9 🐞修复样式细节
- v1.8 🐞修复已知问题
- v1.7 ➕新增多项配色
- v1.6 🐞修复奖杯tips页面文字颜色过淡的问题
- v1.5 🐞修复直接安装js版本时无法使用的问题
- v1.4 🐞修复主题帖中的表格背景色
- v1.3 🐞修复直接安装js版本时无法使用的问题
- v1.2 🐞修复d7vg.com下的使用问题
- v1.1 🐞修改奖杯底色，部分页面的高亮颜色
- v1.0 👑发布

</details>
