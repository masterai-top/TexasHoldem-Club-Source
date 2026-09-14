[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# 德州撲克俱樂部原始碼（德州私局） - C++/Tars 大廳、房間與會員服務

本倉庫聚焦德州撲克俱樂部原始碼與大廳伺服器元件。公開內容包括 C++/Tars Hall 與 GM 服務、房間及玩家生命週期、MySQL 資料存取、商城、簽到、商品與服務費介面，以及部分 Unity 場景檔案。

> 公開目錄依賴外部 XGame/Tars 協議及執行環境，並非已驗證的一鍵部署完整用戶端。功能與交付範圍應以實際檔案和驗收結果為準。

## 公開模組

- `HallServer.*` 與 `HallServant.tars`：大廳服務及介面
- `GMServer.*`：管理服務入口
- `roomlogic/`：入桌、離桌、掉線及開局流程
- `DBOperator.*`：MySQL 資料存取
- 商城、商品、簽到及服務費協議
- 登入、大廳及牌桌 Unity 場景檔案




## ✨ 核心功能 | Core Features

| 模块 | 功能说明 |
| :--- | :--- |
| 🏆 **金币大厅** | 完整的经济系统，金币充值/消费/奖励 |
| 🎮 **多种玩法** | 经典德州 + 短牌 + SNG竞赛 |
| 🏅 **多锦标赛** | 多种德州锦标赛模式 |
| 👥 **社交系统** | 俱乐部 + 朋友局 |
| 🎁 **运营系统** | 签到、商城、道具系统 |

## 🎯 功能清单 | Feature List
✅ 金币大厅 ✅ 德州玩法 ✅ 短牌玩法
✅ SNG竞赛 ✅ 多锦标赛 ✅ 俱乐部系统
✅ 朋友局 ✅ 签到系统 ✅ 商城系统
✅ 道具系统 ✅ 充值系统 ✅ 战绩统计


## 🚀 技术架构 | Tech Stack

- **服务端**：C++ (稳定高效)
- **客户端**：Unity / Cocos (支持iOS/Android)
- **数据库**：MySQL + Redis
- **通信**：私有加密协议


## 產品介面

實際截圖展示俱樂部大廳、加入流程、會員管理及建立牌局設定。畫面用於說明產品範圍，不代表全部執行依賴均已包含在儲存庫內。

| 俱樂部大廳 | 俱樂部列表 |
| --- | --- |
| ![德州撲克俱樂部原始碼大廳與牌桌](docs/assets/screenshots/01.jpg) | ![德州撲克俱樂部列表與活躍度](docs/assets/screenshots/04.jpg) |
| 會員管理 | 建立牌局 |
| ![德州撲克俱樂部會員管理](docs/assets/screenshots/05.jpg) | ![德州撲克俱樂部建立牌局設定](docs/assets/screenshots/13.jpg) |

更多實際畫面：[繁體中文專案頁面](https://masterai-top.github.io/TexasHoldem-Club-Source/zh-tw/)。

## 相關專案

- [德州撲克完整解決方案](https://github.com/masterai-top/TexasHoldem-Poker-Complete-Solution)
- [德州撲克積分大廳](https://github.com/masterai-top/Texas-Hold-em-Points-Lobby)
- [德州撲克賽事平台](https://github.com/masterai-top/Texas-Holdem-Poker-Tournament-Event-Platform)

請遵守所在地法律、平台規則、隱私及未成年人保護要求。
