# Today

A tiny, Apple-style to-do list built around one thing: making it feel *great* to finish a task.

- Spring-physics checkmark, confetti burst, synthesized chime and haptics on every completion
- Combo chimes climb the scale when you finish tasks back-to-back
- Occasional surprise "bloom" rewards, and a full celebration when the list is cleared
- Progress ring, undo, silver glass design
- One static file, no build, no dependencies. Tasks are saved in your browser (localStorage).

Shortcuts: `N` new reminder · `M` toggle sound · long-press the ring to toggle sound.

## Vegas (`/vegas`)

A swing-trade scanner that plays like a slot machine. Pull the lever and it does four things:

1. Scans today's top gainers and most-active stocks plus your watchlist (Alpha Vantage daily prices).
2. Scores each one on the 20-day MA breakout, 2x volume spike, RSI(14) in 30–70, MACD momentum and up-day volume.
3. Pulls headlines for the best setup and asks DeepSeek (via OpenRouter) for a 1–10 bullish read.
4. Lands the reels: **7-7-7** means high conviction, three 💎 is a solid setup, 🍒🍒🔔 is borderline, and a mismatch means no trade.

You get one pick with an entry zone, a target (+5–15%), a stop, risk/reward, a chart and a technicals checklist.

- Add a free [Alpha Vantage key](https://www.alphavantage.co/support/#api-key) in Settings. Free keys allow 25 calls a day, and prices are cached per day.
- An OpenRouter key is optional and enables the DeepSeek sentiment read. The model can be changed in Settings.
- Keys are stored only in your browser's localStorage. **Demo** runs the whole flow on synthetic prices without keys.
- Not financial advice.
