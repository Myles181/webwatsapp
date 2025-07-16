# 🤖 BIG TENNET WhatsApp Bot

A feature-rich WhatsApp bot built with Baileys library that includes utility commands, entertainment features, view-once media unlocking, sticker creation, and ChatGPT integration.

## ✨ Features

### 🔧 Utility Commands
- `!ping` – Check if bot is alive
- `!time` – Get current local time
- `!datediff` – Days between two dates (e.g., `!datediff 2024-01-01 2025-01-01`)
- `!timein <Region/City>` – Current time in any location (uses WorldTimeAPI)
- `!shorten <url>` – Shorten long links (TinyURL)
- `!tempmail` – Generate temporary email address (1SecMail)
- `!color <hex>` – Get color details from hex code (TheColorAPI)
- `!password <length>` – Generate random password

### 🌤 Weather & Info
- `!weather <city>` – Current weather (wttr.in)
- `!define <word>` – Dictionary lookup
- `!country <name>` – Country info (capital, population, currency, etc.)

### 💬 Fun & Motivation
- `!motivate` – Daily motivational quote (ZenQuotes)
- `!joke` – Random joke (Official Joke API)
- `!quote` – Inspirational quote (Type.fit)
- `!trivia` – Random trivia question (OpenTDB)
- `!fact` – Fun fact (Useless Facts API)
- `!wordday` – Random word of the day

### 📈 Crypto
- `!crypto <coin>` – Get price of BTC, ETH, etc. (CoinGecko)

### 🗳️ Poll & Voting
- `!poll <question>` – Create a simple poll
- `!vote <1-4>` – Vote on latest poll

### 🎨 Media Features
- **View-Once Unlocking**: Automatically unlocks and reposts view-once media
- **Sticker Creation**: Reply to any image/video with `!sticker` to convert it
- **Manual Unlock**: Use `!vv` command to manually unlock replied media



## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd whatsapp-bot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure API keys** (optional)
   
   Most features work with free public APIs. No configuration needed!

4. **Run the bot**
   ```bash
   node bot.js
   ```

5. **Scan QR code** with your WhatsApp to connect

## 🔑 API Key Setup

### Free Public APIs
All features use free public APIs - no configuration needed!

### Optional APIs
- **Weather API**: For enhanced weather data (optional)
- **Other APIs**: Most features work with free public APIs

## 📱 Usage Examples

### Basic Commands
```
!ping          - Check if bot is working
!help          - Show help menu
!list          - List all available commands
!time          - Get current time
```

### Utility Commands
```
!datediff 2024-01-01 2025-01-01
!timein London
!shorten https://www.google.com
!tempmail
!color #FF0000
!password 16
```

### Information Commands
```
!weather Lagos
!country Nigeria
!define programming
!crypto bitcoin
```

### Entertainment Commands
```
!motivate
!joke
!quote
!trivia
!fact
!wordday
```

### Media Commands
```
!sticker       - Reply to image/video with this command
!vv            - Manually unlock replied view-once media
```



## 🛠️ Configuration

### Bot Settings
Edit `config.js` to customize:
- Bot name and version
- Response parameters

### Commands
- All commands work in private chats
- Group-only commands are restricted to groups
- View-once unlocking works automatically

## 🔧 Troubleshooting

### Common Issues
1. **Bot not responding**: Check if QR code is scanned
2. **Commands not working**: Ensure message starts with `!`
3. **Media not downloading**: Check internet connection

### Debug Commands
```
!debug         - Get debug information
!test          - Test bot functionality
```

## 📝 Notes

- The bot automatically unlocks view-once media
- Sticker conversion works with images and videos
- All APIs used are free/public
- Bot works in both private chats and groups

## 🤝 Contributing

Feel free to contribute by:
- Adding new commands
- Improving existing features
- Fixing bugs
- Adding documentation

## 📄 License

Created by BIG TENNET

## 🔗 Links

- **Instagram**: @bigtennet
- **TikTok**: @therealbigtennet
- **Website**: https://tennetteam.com

---

**Enjoy using BIG TENNET WhatsApp Bot! 🚀** 