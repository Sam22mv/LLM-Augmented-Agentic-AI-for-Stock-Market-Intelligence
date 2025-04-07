# LLM-Augmented-Agentic-AI-for-Stock-Market-Intelligence

This project is an **LLM-Augmented-Agentic-AI-for-Stock-Market-Intelligence** powered by `autogen` and OpenAI’s `gpt-4o`, designed to **analyze stock market data**, **retrieve news headlines**, and **generate detailed financial reports**—all without requiring an API key for stock or news data.

## Features

- Accepts user-defined stock tickers (e.g., `AAPL`, `MSFT`, `TSLA`)
- Retrieves and visualizes:
  - Current stock prices
  - 6-month performance trends
  - Normalized price plots
  - Key financial ratios: P/E, Forward P/E, Dividends, Price-to-Book, Debt/Equity, ROE
- Gathers the latest 10+ news headlines per stock (via Bing/Google scraping)
- Analyzes:
  - Correlation between stocks
  - Fundamental metrics and risk
  - Connection between financial ratios and news events
  - Future scenarios and investment perspectives
-  Produces a polished **Markdown financial report** with visualizations and tables
-  Undergoes multiple rounds of peer review (Critic + Reviewer agents)
-  Automatically saves the final report to a `.md` file

## Agents Involved
- Financial_assistant: Collects and analyzes stock metrics and prices
- Researcher: Retrieves stock-related news headlines
- Writer: Crafts the detailed financial report
- Critic + Reviewers: Provide multi-dimensional feedback
- Exporter: Saves the final Markdown report
