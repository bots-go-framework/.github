# 🤖 [`bots-go-framework`](https://github.com/bots-go-framework)

Golang framework & plugins to build multilingual bots for messengers (_Telegram, FB Messenger, Skype, Line, Kik, WeChat_)
hosted on AppEngine, Amazon, Azure, Heroku or standalone.

Have common logic shared across bots working on diffent platforms but do not loose messenger-specific features!

## 📦 Modules & Packages

- [`github.com/bots-go-framework/botsfw`](https://github.com/bots-go-framework/botsfw) - core package

### 🔌 Adapters to specific messengers
You would want to use this if you want to implement UI specific to target bot platform.

| Platform | Module   |
|----------|----------|
| Telegram            | [`github.com/bots-go-framework/bots-fw-telegram`](github.com/bots-go-framework/bots-fw-telegram) |
| Facebook Messenger  | [`github.com/bots-go-framework/bots-fw-fbm`](github.com/bots-go-framework/bots-fw-viber) |
| Viber               | [`github.com/bots-go-framework/bots-fw-viber`](github.com/bots-go-framework/bots-fw-telegram) |

### 🔛 Bot API clients
This bot API clients can be used directly without Bots Go Framework.

| Platform | Module   |
|----------|----------|
| Telegram            | [`github.com/bots-go-framework/bots-api-telegram`](github.com/bots-go-framework/bots-api-telegram) |
| Facebook Messenger  | [`github.com/bots-go-framework/bots-api-fbm`](github.com/bots-go-framework/bots-api-viber) |
| Viber               | [`github.com/bots-go-framework/bots-api-viber`](github.com/bots-go-framework/bots-api-telegram) |

## 🙏 Dependencies

- [`github.com/dal-go`](https://github.com/dal-go) - Database Abstraction Layer in GO language

# 🔥 Used by

- ⚫⚪ [**Reversi** game](https://github.com/prizarena/reversi) - open source game. (*Telegram: [@ReversiGameBot](https://t.me/ReversiGameBot)*)
- ✖️⭕ [**Bidding Tic-Tac-Toe**](https://github.com/prizarena/bidding-tictactoe) - open source game. (*Telegram: [@BiddingTicTacToeBot](https://t.me/BiddingTicTacToeBot)*)
- 📃✂️ [**Rock-Paper-Scissors**](https://github.com/prizarena/rock-paper-scissors) - open source game. (*Telegram: [@playRockPaperScissorsBot](https://t.me/playRockPaperScissorsBot)*)

Submit a PR for adding a link here if you use Dalgo in your open source project.
