# ChatGPT Trading Academy

A modern, interactive stock trading simulator and educational platform built with React, Vite, and Tailwind CSS.

## 🎓 Features

### Educational Content
- **3 Core Lessons**: What Is a Stock?, Bull vs Bear Markets, Risk Management
- **Real-World Examples**: Practical trading scenarios
- **Interactive Learning**: Click through lessons with live examples

### Trading Simulator
- **Live Price Simulation**: Realistic stock price movements updating every 2.5 seconds
- **Buy/Sell Functionality**: Execute trades with your $10,000 starting capital
- **Portfolio Tracking**: Real-time balance, shares held, and portfolio value

### Advanced Features
- **Trade History**: Complete log of all transactions with timestamps
- **Performance Metrics**: 
  - Total Return (dollars)
  - Return Percentage (%)
  - Total Trades (count)
  - Current Position Status
- **Price Chart**: Visual representation of price movements over time
- **Reset Functionality**: Practice different trading strategies from scratch

## 📦 Tech Stack

- **Frontend**: React 18.2.0
- **Build Tool**: Vite 5.0
- **Styling**: Tailwind CSS 3.3
- **Runtime**: Node.js / npm

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Yypcodes1/chatgpt-trading-academy-.git
cd chatgpt-trading-academy-
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

The app will open at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The optimized build will be created in the `dist/` directory.

## 📁 Project Structure

```
chatgpt-trading-academy-/
├── src/
│   ├── components/
│   │   └── TradingLearningApp.jsx    # Main component
│   ├── App.jsx                       # App wrapper
│   ├── main.jsx                      # Entry point
│   └── index.css                     # Tailwind styles
├── index.html                        # HTML template
├── package.json                      # Dependencies
├── vite.config.js                    # Vite config
├── tailwind.config.js                # Tailwind config
├── postcss.config.js                 # PostCSS config
└── README.md                         # Documentation
```

## 🎮 How to Use

1. **Select a Lesson**: Click on any lesson in the left sidebar to read educational content
2. **Monitor Price**: Watch the real-time price chart update every 2.5 seconds
3. **Execute Trades**:
   - Click **Buy** to purchase shares at current price
   - Click **Sell** to sell shares at current price
4. **Track Performance**: View your metrics in the Performance panel
5. **Review History**: Check your trade log to review past transactions
6. **Reset & Practice**: Click **Reset** to start a new trading session

## 📊 Trading Tips (Simulated)

- Start with small positions to learn
- Practice risk management
- Track your performance metrics
- Review your trade history
- Try different strategies

## ⚠️ Disclaimer

**This simulator is for educational purposes only.**

- This is NOT real trading
- No real money is involved
- Past simulator performance doesn't predict real-world results
- Real trading involves significant financial risk
- Always research thoroughly and manage risk carefully
- Never invest money you can't afford to lose

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

### Contribution Areas
- Bug fixes
- Feature enhancements
- Documentation improvements
- UI/UX improvements
- Performance optimizations

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Description of the bug
- Steps to reproduce
- Expected vs actual behavior
- Screenshot (if applicable)

## 💡 Feature Requests

Have an idea? Open an issue with:
- Clear description of the feature
- Use cases
- Expected behavior

## 📝 License

This project is open source. See LICENSE file for details.

## 👨‍💻 Author

**Yypcodes1** - Trading Academy Creator

## 🙏 Acknowledgments

- Built with React and Vite
- Styled with Tailwind CSS
- Educational trading concepts

## 📞 Support

For questions or support:
- Open an issue on GitHub
- Check existing documentation
- Review the code comments

---

**Happy Trading! 📈💹**

Remember: The goal of this simulator is to learn trading concepts and strategies in a risk-free environment.
