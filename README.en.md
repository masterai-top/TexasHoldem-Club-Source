[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# Texas Hold'em Poker Club Source Code

Source components and product UI references for a Texas Hold'em poker club, private table and friends-game experience. The public repository includes C++/Tars Hall and GM services, room/player lifecycle logic, Tars MySQL access, mall/goods/sign-in protocols, service-fee interfaces, and selected Unity login, lobby and gameplay scenes.

> Scope: code-verified modules and screenshot-demonstrated product behavior are identified separately. External XGame/Tars protocols and runtime dependencies are required; this is not a verified one-click commercial client.

## Product journey

1. **Discover clubs** by online users, total members, average pot and activity; filter tables by Hold'em, AOF, 6+ Short Deck, seats and availability.
2. **Create or join** a club by club ID/name. The interface shows a maximum of five joined clubs.
3. **Manage members** with online status, application approval/rejection, records and billing entries.
4. **Review operations** through daily/monthly accounting, insurance records and level, wealth and activity rankings.
5. **Create a table** with Hold'em, AOF or 6+ Short Deck, 60–240 minute duration, 2/6/9 seats, speed, blinds, service fee and insurance settings.

## Real product screens

| Club lobby and tables | Filters and game modes |
| --- | --- |
| ![Texas Holdem poker club lobby source code](docs/assets/screenshots/01.jpg) | ![Holdem AOF short deck and seat filters](docs/assets/screenshots/02.jpg) |
| Membership review | Private table setup |
| ![Poker club membership approval workflow](docs/assets/screenshots/06.jpg) | ![Texas Holdem private table configuration](docs/assets/screenshots/13.jpg) |
| Club accounting | Club rankings |
| ![Daily and monthly poker club accounting](docs/assets/screenshots/07.jpg) | ![Poker club level wealth and activity rankings](docs/assets/screenshots/10.jpg) |

[Open the full English product page](https://masterai-top.github.io/TexasHoldem-Club-Source/en/)

## Code-verified components

| Area | Main files | Verifiable scope |
| --- | --- | --- |
| Hall and account | `HallServer.*`, `HallServant.tars` | Hall entry, gateway state, profiles, wealth/experience, tasks, rewards, messages and mail |
| Room lifecycle | `roomlogic/`, `timeoutlogic/` | Sit down, stand up, offline, game start, user mapping and action timeout |
| GM service | `GMServer.*`, `GMServantImp.h` | GM service entry and request handling |
| Data access | `DBOperator.*` | Tars MySQL access component |
| Mall and goods | `MallProto.tars`, `GoodsManagerProto.tars` | Platform/region settings, purchase, dispatch, use, exchange and count operations |
| Sign-in | `SignInProto.tars` | Sign-in details, cumulative sign-in and new-user rewards |
| Client material | `Production/*.unity`, `apps.json` | Selected login/lobby/gameplay scenes and multi-platform version configuration; not a complete Unity project |

## Suitable evaluation paths

- Poker club, friends table and private table product evaluation
- C++/Tars hall, room, account and timeout architecture study
- Membership review, club accounting, rankings and table-setup UX reference
- Mall, inventory, sign-in, mail and service-fee integration

## Contact

- Telegram: [@xuzongbin001](https://t.me/xuzongbin001)
- Email: [masterai918@gmail.com](mailto:masterai918@gmail.com)

Follow applicable laws, platform rules, privacy and minor-protection requirements. Do not use this project for illegal gambling.
