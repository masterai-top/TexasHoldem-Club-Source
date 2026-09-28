[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# 德州扑克俱乐部源码：私人局、会员与牌桌大厅

面向德州扑克俱乐部、熟人局和私人牌局场景的源码与产品界面参考。仓库公开内容包含 C++/Tars Hall 与 GM 服务、房间和玩家生命周期、Tars MySQL 数据访问、商城/商品/签到协议、服务费相关接口，以及部分 Unity 登录、大厅与牌桌场景。

> 范围说明：以下内容严格区分代码可验证模块和截图展示功能。仓库仍依赖外部 XGame/Tars 协议与运行环境，不应理解为无需配置即可上线的完整商业客户端。

## 产品流程

1. **发现俱乐部**：查看在线人数、总人数、平均底池和活跃度，按德州、AOF、6+ Short Deck、座位数及空满桌筛选。
2. **创建或加入**：通过俱乐部 ID/名称申请加入，也可创建自己的俱乐部；界面显示最多加入 5 个俱乐部。
3. **会员管理**：查看成员和在线状态，审核或拒绝加入申请，进入战绩与账单入口。
4. **运营查看**：按日/月查看俱乐部账务及保险记录，并通过等级、财富、活跃度排行榜观察成员表现。
5. **创建牌桌**：配置德州、AOF 或 6+ Short Deck，设置 60–240 分钟、2/6/9 人、速度、盲注、服务费和保险选项。

## 真实产品界面

| 俱乐部大厅与牌桌 | 筛选与玩法 |
| --- | --- |
| ![德州扑克俱乐部源码大厅和牌桌入口](docs/assets/screenshots/01.jpg) | ![德州扑克、AOF、短牌和座位筛选](docs/assets/screenshots/02.jpg) |
| 会员审核 | 创建私人牌桌 |
| ![德州扑克俱乐部会员加入审核](docs/assets/screenshots/06.jpg) | ![德州扑克私人局牌桌设置](docs/assets/screenshots/13.jpg) |
| 俱乐部账单 | 俱乐部排行榜 |
| ![德州扑克俱乐部日月账单和保险记录](docs/assets/screenshots/07.jpg) | ![德州扑克俱乐部等级财富活跃排行榜](docs/assets/screenshots/10.jpg) |

[查看完整图文产品页](https://masterai-top.github.io/TexasHoldem-Club-Source/zh-cn/)

## 代码可验证模块

| 模块 | 主要文件 | 可验证内容 |
| --- | --- | --- |
| 大厅与账户 | `HallServer.*`、`HallServant.tars` | 大厅入口、网关状态同步、用户资料、财富/经验、任务奖励、系统消息和邮件 |
| 房间流程 | `roomlogic/`、`timeoutlogic/` | 入桌、离桌、掉线、开局、用户映射和操作超时 |
| GM 服务 | `GMServer.*`、`GMServantImp.h` | GM 服务入口和请求处理 |
| 数据访问 | `DBOperator.*` | Tars MySQL 数据访问组件 |
| 商城与商品 | `MallProto.tars`、`GoodsManagerProto.tars` | 平台/区域设置、商品购买、发放、使用、兑换和数量查询 |
| 签到奖励 | `SignInProto.tars` | 签到详情、累计签到和新用户奖励接口 |
| 客户端素材 | `Production/*.unity`、`apps.json` | 部分登录/大厅/牌桌场景及 iOS、Android、Windows 版本配置；不是完整 Unity 工程 |

## 适合的二次开发方向

- 德州扑克俱乐部、好友局、熟人局与私人牌局产品评估
- C++/Tars 大厅、房间、账户和超时流程研究
- 会员审核、俱乐部账单、排行榜与牌桌配置交互参考
- 商城、商品、签到、邮件与服务费接口整合

## 部署前检查

- 补齐外部 XGame/Tars 协议、依赖库、数据库结构和部署配置。
- 对照交付清单验证服务端、客户端、美术资源及管理后台范围。
- 在测试环境完成账号、牌桌、断线、超时、账务和权限回归测试。
- 遵守所在地法律、平台规则、隐私及未成年人保护要求；不得用于非法赌博。

## 联系方式

- Telegram：[@xuzongbin001](https://t.me/xuzongbin001)
- Email：[masterai918@gmail.com](mailto:masterai918@gmail.com)

