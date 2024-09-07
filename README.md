# EagleEye
Data-driven AI agent that analyzes forex &amp; crypto markets for high probability trade decisions
# Asian Range and Kill Zones Indicator

This repository contains the **Asian Range and Kill Zones Indicator**, designed for Forex and Crypto trading on platforms like TradingView. This tool allows traders to visualize important market sessions such as the Asia, London, and New York sessions, along with their respective opening and closing ranges. It provides a visual representation of price ranges and deviations that can be crucial for determining entry and exit points in various trading strategies.

## Features

- **Asia Range**: Visualizes the high and low of the Asian trading session, along with optional deviation levels for extended analysis.
- **London Open & Close**: Displays the opening and closing range of the London session to help traders identify potential volatility during these periods.
- **New York Open & Close**: Highlights the range during the New York session, which is known for its increased market activity and liquidity.
- **Customization**: Colors, session times, and deviation levels can be customized to fit your specific trading needs.

## Sessions Covered

1. **Asia Session**:
   - Default Time: 19:00 - 00:01 (TradingView server time)
   - Displays the range for the Asia session, including optional deviation lines.
   
2. **London Open**:
   - Default Time: 02:00 - 06:00
   - Displays the high and low of the London Open range.

3. **London Close**:
   - Default Time: 10:00 - 13:00
   - Shows the closing range of the London session, marking potential areas of support and resistance.

4. **New York Open**:
   - Default Time: 07:00 - 10:00
   - Highlights the range during the New York Open, one of the most volatile sessions.

5. **New York Close**:
   - Default Time: 14:00 - 16:00
   - Displays the New York session close, optional for deeper market analysis.

## Future Development

This indicator is an ongoing project. While the current version provides a robust visualization of the Asian, London, and New York sessions, further enhancements are planned. These include potential improvements in accuracy, additional session-based strategies, and more customizable features. Stay tuned for updates, and feel free to contribute or suggest improvements through pull requests or issues.

## Installation & Setup

### Step 1: Add the Indicator to TradingView

1. Open TradingView and go to your chart.
2. Click on **Indicators** at the top of the chart and search for **Pine Script Editor**.
3. Copy and paste the code from this repository into the Pine Script Editor.
4. Click **Add to Chart** to apply the indicator to your chart.
5. Customize the settings such as session times, colors, and deviation levels to match your trading strategy.

### Step 2: Customize the Indicator

- **Max Timeframe to Display**: Adjust the maximum timeframe (in minutes) that you want the indicator to display on your chart. Default is 60 minutes.
- **Asia Session**: Enable or disable the Asia session box. Adjust the colors and the number of deviations.
- **London Session**: Enable or disable the London Open and Close boxes. Customize the colors for better visibility.
- **New York Session**: Toggle the New York Open and Close sessions. Modify the colors according to your preference.

## Parameters

- **Asia Deviations**: Number of deviation levels for the Asia range.
- **Timeframes**: The indicator is designed to work on intraday timeframes for accurate session visualization.
- **Colors**: All session boxes and lines are customizable to suit different visual preferences.

## How It Works

The indicator identifies the high and low prices during each session and draws a box to highlight the price range. For the Asia session, optional deviation levels can be drawn above and below the range to indicate potential breakout zones. The London and New York session boxes help traders identify key trading periods with increased market activity.

Each session is clearly marked with different colors, and traders can enable or disable specific sessions according to their trading style. The indicator works best on shorter timeframes (intraday) to capture session-specific price movements.

## License

This project is licensed under the **Mozilla Public License 2.0**. You can find the full license [here](https://mozilla.org/MPL/2.0/).

---

## Disclaimer

Trading is inherently risky, and this indicator is intended for educational purposes only. Please ensure you understand the risks involved before trading real money in the Forex or Crypto markets. Past performance is not indicative of future results.

## Author

- **rjgtrader** (Original Developer)
- GitHub Repository: [Gandara369/EagleEye](https://github.com/Gandara369/EagleEye)

---

For any inquiries or contributions, feel free to open an issue or pull request.
