# [`bots-go-framework`](https://github.com/bots-go-framework)

Golang framework & plugins to build multilingual bots for messengers (_Telegram, FB Messenger, Skype, Line, Kik, WeChat_)
hosted on AppEngine, Amazon, Azure, Heroku or standalone.

Have common logic shared across bots working on diffent platforms but do not loose messenger-specific features!

## Modules & Packages

- [`github.com/bots-go-framework/botsfw`](https://github.com/bots-go-framework/botsfw) - core package

### Adapters to specific messengers
| Platform | Module   |
|----------|----------|
| Telegram            | [`github.com/bots-go-framework/bots-fw-telegram`](github.com/bots-go-framework/bots-fw-telegram) |
| Facebook Messenger  | [`github.com/bots-go-framework/bots-fw-fbm`](github.com/bots-go-framework/bots-fw-viber) |
| Viber               | [`github.com/bots-go-framework/bots-fw-viber`](github.com/bots-go-framework/bots-fw-telegram) |

## Dependencies

- [`github.com/dal-go`](https://github.com/dal-go) - Database Abstraction Layer in GO language
