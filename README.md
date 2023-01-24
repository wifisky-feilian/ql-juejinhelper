<h1 align="center">稀土掘金助手-青龙版</h1>

<p align="center">使用青龙面板实现签到、抽奖、沾喜气、消除Bug、海底掘金游戏、自动化工作流。</p>

## 开始使用

> 青龙面板版本号 > v2.14.7

1、在青龙面板添加订阅

```shell
ql repo https://ghproxy.com/https://github.com/wifisky-feilian/ql-juejinhelper.git "juejin_|juejinCookies" "juejinCookies" "^juejin[^_]"
```

2、在面板菜单-依赖管理-NodeJs 添加依赖 `juejin-helper|fast-astar`

3、在环境变量中添加Cookie

青龙面板，添加环境变量`JJ_COOKIE`，支持添加多个Cookie，同时添加多条`JJ_COOKIE`即可

3、默认使用青龙自带的通知，请自行配置即可

## 问题

### 如何获取Cookie

掘金网站Cookie, 打开浏览器，登录 [掘金](https://juejin.cn/), 打开控制台DevTools(快捷键F12) -> Network，复制 cookie, **掘金Cookie有效期约1个月需定期更新.**

DevTools截图:
<img width="1156" alt="getcookie" src="https://github.com/leochen-g/juejin-helper/raw/main/resources/getcookie.png">

### 如何授权海底掘金游戏

运行自动化后通知订阅人 `玩家未授权, 请前往掘金授权!`, 说明您是新玩家从始至终未进行海底掘金游戏, 需要先进行游戏授权.

授权步骤: 登陆 [掘金](https://juejin.cn/) -> 每日签到 -> 海底掘金挑战赛(点击进入游戏, 点击授权, 最好再随意玩一局). 后续就可以由掘金助手自动处理.

或点击👇这个海报帮您直达海底掘金挑战赛

[![海底掘金挑战赛](https://user-images.githubusercontent.com/24502299/151397151-0d69998a-2310-4a32-945f-c8e0035ed65d.png)](https://juejin.cn/game/haidijuejin/)

## 特别声明

**1. 本仓库发布的脚本及其中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。**

**2. 本人对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害。**

**3. 间接使用脚本的任何用户，建立 VPS 或在某些行为违反国家/地区法律或相关法规的情况下进行传播，本人对于由此引起的任何隐私泄漏或其他后果概不负责。**

**4. 请勿将本仓库的任何内容用于商业或非法目的，否则后果自负。**

**5. 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明、所有权证明，我们将在收到认证文件后删除相关脚本。**

**6. 任何以任何方式查看此项目的人或直接或间接使用该项目的任何脚本的使用者都应仔细阅读此声明。本人保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或 Script 项目的规则，则视为您已接受此免责声明。**

**7. 您必须在下载任何内容后的 24 小时内从您的存储设备中完全删除下载的内容。**

**8. 您使用或者复制了本仓库和本人制作的任何脚本，则视为 `已接受` 此声明，请仔细阅读，谢谢！**

**9. 本仓库脚本和打包的插件仅用于学习和测试，也请在完成之前，仔细阅读特别声明，完成后，删除脚本和插件，谢谢！**
