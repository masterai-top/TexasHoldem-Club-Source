[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# Texas Hold'em Poker Club Source Code - C++/Tars Lobby and Room Services

This repository focuses on Texas Hold'em poker club and lobby server components. Public files include C++/Tars Hall and GM services, room and player lifecycle logic, MySQL access, mall, sign-in, goods and service-fee interfaces, and selected Unity scene files.

> The public tree depends on an external XGame/Tars protocol and runtime environment. It is not a verified one-command complete client. Verify features, licensing, dependencies, and delivery scope against the actual files and acceptance results.

## Public Components

- `HallServer.*` and `HallServant.tars`: lobby services and contracts
- `GMServer.*`: management service entry point
- `roomlogic/`: sit-down, stand-up, offline, and game-start flows
- `DBOperator.*`: MySQL data access
- Mall, goods, sign-in, and service-fee protocols
- Selected login, lobby, and table Unity scenes

## Product Screens

Repository screenshots show the club lobby, join flow, member management, and table creation settings. They document product scope but do not imply that every runtime dependency is included.

| Club lobby | Club directory |
| --- | --- |
| ![Texas Holdem poker club lobby and tables](docs/assets/screenshots/01.jpg) | ![Poker club directory and activity data](docs/assets/screenshots/04.jpg) |
| Member management | Create a club table |
| ![Texas Holdem poker club member management](docs/assets/screenshots/05.jpg) | ![Texas Holdem poker club table creation settings](docs/assets/screenshots/13.jpg) |

See more interfaces on the [English project page](https://masterai-top.github.io/TexasHoldem-Club-Source/en/).

## Related Projects

- [Complete Texas Hold'em source solution](https://github.com/masterai-top/TexasHoldem-Poker-Complete-Solution)
- [Texas Hold'em points lobby](https://github.com/masterai-top/Texas-Hold-em-Points-Lobby)
- [Texas Hold'em tournament platform](https://github.com/masterai-top/Texas-Holdem-Poker-Tournament-Event-Platform)

Follow all applicable laws, platform rules, privacy, and minor-protection requirements.
