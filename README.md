# Vindicci

Vindicci is an AI-powered asset evaluation system designed to systematically identify promising investment opportunities through an innovative, tournament-style A/B screening method. It combines **TradingView** for market data, **Rivet** for workflow management, and **GPT** for intelligent asset analysis.

---

## 🚀 Features

- **AI Tournament System**: Assets compete in successive rounds, evaluated by GPT-based AI agents.
- **Robust Analysis**: Leverages multiple evaluating agents to determine a consensus-driven best choice.
- **Easy Integration**: Uses standard CSV exports from TradingView.
- **Fully Customizable**: Adapt the tournament to any screening criteria or asset category.

---

## 📥 Getting Started

### Step 1: Create and Export a Screener

- Head to [TradingView Screener](https://www.tradingview.com/screener/) and create your asset list.
- Export the screener data as a CSV file. *(Note: Requires at least a free trial TradingView account.)*

### Step 2: Download Vindicci

- Clone or download the repository from [GitHub](https://github.com/Geep5/Vindicci).

### Step 3: Install & Configure Rivet

- Install Rivet from [Rivet's official site](https://rivet.ironcladapp.com/).
- Add your OpenAI API key in Rivet settings.
- Load the Vindicci project in Rivet and point it to your TradingView CSV file.

### Step 4: Run the Tournament

- Start the Rivet workflow. Rivet runs multiple rounds of asset comparisons, each evaluated by multiple GPT instances.
- A winner is chosen each round based on majority vote, ultimately producing a final "champion" asset.

---

## 🎥 Demo Video

Watch this short YouTube walkthrough for a clear demonstration of Vindicci:

[![Watch Vindicci Demo](https://img.youtube.com/vi/mGBrwXTK7oc/0.jpg)](https://youtu.be/mGBrwXTK7oc)


---

## 📝 License

Released under the [Vindicci Tournament License](LICENSE.md).

---

## 📣 About

Created by **Grant Farwell**. Inspired by tournament methodologies from [Matcherino](https://matcherino.com), Vindicci aims to provide an open, transparent, and powerful AI-based solution for asset evaluation.

Your feedback and contributions are highly encouraged! Feel free to contribute, provide suggestions, or reach out for help.

Happy investing and innovating! 🚀

- Grant