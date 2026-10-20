# LiveCasino — 赌场视讯系统（Casino Live Video System）

一套完整的**真人视讯（Live Casino）系统解决方案**，本项目**全开源**。

系统覆盖从流媒体采集传输、荷官端路单录入与结果辨识、玩家端 UI 交互、多玩法游戏引擎，到后台管理（现金 / 信用 / API）的完整链路，适用于持牌合法赌场及游戏运营商的视讯业务场景。

---

## 一、系统功能

### 1. 赌场视讯系统（多语言 / 多币种）
- 支持 20+ 种国际语言切换（中 / 英 / 日 / 韩 / 泰 / 越 / 印尼 / 马来 / 菲 / 缅 / 印地 / 孟加拉 / 乌尔都 / 泰卢固 / 阿拉伯 / 波斯 / 土耳其 / 法 / 西 / 葡 / 俄等）
- 多币种钱包体系（演示环境以 USDT 记账），币别与汇率可配置
- 游客试玩 / 正式账号双模式，滑块拼图 + 图形验证码安全校验

### 2. 现场路单端 + 辨识（荷官端）
- 荷官专用操作端：开牌结果录入、路单自动生成与同步
- 牌面结果智能辨识，实时推送至所有用户端路单（Roadmap）
- 珠盘路 / 大路 / 大眼仔 / 小路 / 蟑螂路等多路单视图

### 3. 视讯流媒体码流（流媒体架构）
- 低延迟直播流媒体分发架构，支持多桌台并发流
- 桌台视频流 + 游戏数据流分离传输，自适应码率
- 支持桌面端与移动端全平台播放

### 4. 用户端 UI 交互（前端）
- 大厅桌台列表（缩略视频 + 实时路单预览）
- 游戏桌界面：投注区、筹码选择、投注确认 / 取消 / 重下
- 多桌投注模式（多台同屏同时下注）
- 公告中心（公告 + 站内信）、投注记录、充值提现、返水结算、好友转账
- 用户功能栏：游戏规则、语言、声音、全屏、精简模式、投注区域位置、密码管理、意见提交
- 深色奢华主题，响应式布局（桌面 / 平板 / 手机）

### 5. 游戏玩法种类
- **百家乐（Baccarat）**：庄 / 闲 / 和 / 庄对 / 闲对 / 幸运 6，支持免水（No Commission）模式
- **龙虎（Dragon Tiger）**
- **牛牛（Niuniu）**
- 极速桌台与多国语言桌台（如韩国极速桌）可按需扩展

### 6. 后台管理与功能（现金 / 信用 / API）
- 后台管理系统：会员管理、桌台管理、荷官管理、赔率与限红配置
- **现金模式**与**信用模式**双账务体系
- **开放 API**：第三方平台可快速接入（对接文档随源码提供）
- 财务报表、投注流水、返水结算、公告发布、权限分级

---

## 二、前端演示

> 截图中品牌 LOGO 已按合规要求打码处理。
> **需要演示网址请 Telegram 联系**：https://t.me/cnwen123

### 演示 1（桌面端）

| 登录页 | 游戏大厅 |
|---|---|
| ![登录页](screenshots/demo1/01-login.png) | ![大厅](screenshots/demo1/02-lobby.png) |

| 龙虎大厅 | 牛牛大厅 |
|---|---|
| ![龙虎](screenshots/demo1/03-dragon-tiger.png) | ![牛牛](screenshots/demo1/04-niuniu.png) |

| 游戏桌（投注界面） | 多桌投注 |
|---|---|
| ![游戏桌](screenshots/demo1/05-game-table.png) | ![多桌](screenshots/demo1/06-multi-table.png) |

| 公告中心 | 站内信 |
|---|---|
| ![公告](screenshots/demo1/07-announcement.png) | ![站内信](screenshots/demo1/08-inbox.png) |

| 用户功能菜单 | 游戏规则 |
|---|---|
| ![菜单](screenshots/demo1/09-user-menu.png) | ![规则](screenshots/demo1/10-game-rules.png) |

#### 演示 1 · 手机竖屏

| 登录页 | 游戏大厅 |
|---|---|
| ![手机登录](screenshots/demo1/mobile/01-mobile-login.png) | ![手机大厅](screenshots/demo1/mobile/02-mobile-lobby.png) |

| 游戏桌（投注界面） | 用户功能菜单 |
|---|---|
| ![手机游戏桌](screenshots/demo1/mobile/03-mobile-game-table.png) | ![手机菜单](screenshots/demo1/mobile/04-mobile-user-menu.png) |

| 公告中心 | |
|---|---|
| ![手机公告](screenshots/demo1/mobile/05-mobile-announcement.png) | |

### 演示 2（桌面端）

| 登录页 | 游戏大厅 |
|---|---|
| ![登录页](screenshots/demo2/01-login.png) | ![大厅](screenshots/demo2/02-lobby.png) |

| 龙虎大厅 | 牛牛大厅 |
|---|---|
| ![龙虎](screenshots/demo2/03-dragon-tiger.png) | ![牛牛](screenshots/demo2/04-niuniu.png) |

| 游戏桌（投注界面） | 用户功能菜单 |
|---|---|
| ![游戏桌](screenshots/demo2/05-game-table.png) | ![菜单](screenshots/demo2/06-user-menu.png) |

| 公告中心 | 充值提现 |
|---|---|
| ![公告](screenshots/demo2/07-announcement.png) | ![钱包](screenshots/demo2/08-wallet.png) |

#### 演示 2 · 手机竖屏

| 登录页 | 游戏大厅 |
|---|---|
| ![手机登录](screenshots/demo2/mobile/01-mobile-login.png) | ![手机大厅](screenshots/demo2/mobile/02-mobile-lobby.png) |

| 游戏桌（投注界面） | 用户功能菜单 |
|---|---|
| ![手机游戏桌](screenshots/demo2/mobile/03-mobile-game-table.png) | ![手机菜单](screenshots/demo2/mobile/04-mobile-user-menu.png) |

| 公告中心 | |
|---|---|
| ![手机公告](screenshots/demo2/mobile/05-mobile-announcement.png) | |

---

## 三、合法合规声明（重要）

1. **合法运营区域**：本系统仅供已取得合法博彩牌照及经营资质的地区与机构使用，例如澳门（中国特别行政区）、菲律宾（PAGCOR 许可）、马耳他（MGA 许可）、库拉索、英国（UKGC 许可）、美国内华达州 / 新泽西州等博彩合法许可区域，以及其他当地法律明确允许在线博彩业务的国家与地区。
2. **禁止非法使用**：**本系统不得用于任何违法活动，不得部署或服务于不符合当地法律法规的地区。** 任何个人或组织在使用、部署、二次开发本系统前，必须自行确认所在司法管辖区的法律规定，并自行取得所需牌照与许可。
3. 本项目开源代码仅用于技术研究、学习与交流目的。因使用方违反当地法律所产生的任何法律责任，均由使用方自行承担，与本项目作者无关。
4. 如您所在地区法律不允许在线博彩业务，请立即停止浏览、下载、部署或使用本系统。

---

## 四、获取完整源代码

本仓库提供系统介绍与前端界面演示。如需获取本项目**全部完整源代码**（流媒体服务、荷官端、用户端、后台管理、API 文档等全套工程），请联系：

- **Telegram**：https://t.me/cnwen123

---

## 五、许可证

本项目代码以开源形式发布，详见 [LICENSE](LICENSE)。使用即表示您已阅读并同意上述《合法合规声明》的全部条款。
