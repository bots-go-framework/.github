# 🤖 [`bots-go-framework`](https://github.com/bots-go-framework)

Golang framework & plugins to build multilingual bots for messengers (_Telegram, FB Messenger, Skype, Line, Kik, WeChat_)
hosted on AppEngine, Amazon, Azure, Heroku or standalone.

Have common logic shared across bots working on diffent platforms but do not loose messenger-specific features!

## 📦 Modules & Packages

- 🤖 [`github.com/bots-go-framework/bots-fw`](https://github.com/bots-go-framework/bots-fw) - core package

### 🔌 Adapters to specific messengers
You would need to use this if you want to implement UI/features specific to some bot platform.

| Platform | Module   |
|----------|----------|
| Telegram            | [`github.com/bots-go-framework/bots-fw-telegram`](https://github.com/bots-go-framework/bots-fw-telegram) |
| Facebook Messenger  | [`github.com/bots-go-framework/bots-fw-fbm`](https://github.com/bots-go-framework/bots-fw-fbm) |
| Viber               | [`github.com/bots-go-framework/bots-fw-viber`](https://github.com/bots-go-framework/bots-fw-viber) |

### 🔛 Bot API clients
This bot API clients can be used directly without Bots Go Framework.

| Platform | Module   |
|----------|----------|
| Telegram            | [`github.com/bots-go-framework/bots-api-telegram`](https://github.com/bots-go-framework/bots-api-telegram) |
| Facebook Messenger  | [`github.com/bots-go-framework/bots-api-fbm`](https://github.com/bots-go-framework/bots-api-fbm) |
| Viber               | [`github.com/bots-go-framework/bots-api-viber`](https://github.com/bots-go-framework/bots-api-viber) |

## 🙏 Dependencies

- [`github.com/dal-go`](https://github.com/dal-go) - Database Abstraction Layer in GO language

# 🔥 Used by
Submit a PR for adding a link here if you use Bots Go Framework in your open source project.
## 🎲 Games
- ⚫⚪ [**Reversi** game](https://github.com/prizarena/reversi) - open source game.
- ✖️⭕ [**Bidding Tic-Tac-Toe**](https://github.com/prizarena/bidding-tictactoe) - open source game.
- 📃✂️ [**Rock-Paper-Scissors**](https://github.com/prizarena/rock-paper-scissors) - open source game.
