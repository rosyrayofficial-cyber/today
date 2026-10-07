# Today

A tiny, Apple-style to-do list built around one thing: making it feel *great* to finish a task.

- Spring-physics checkmark, confetti burst, synthesized chime and haptics on every completion
- Combo chimes climb the scale when you finish tasks back-to-back
- Occasional surprise "bloom" rewards, and a full celebration when the list is cleared
- Progress ring, undo, silver glass design
- One static file, no build, no dependencies. Tasks are saved in your browser (localStorage).

Shortcuts: `N` new reminder · `M` toggle sound · long-press the ring to toggle sound.

## Vegas (`/vegas`)

A 3-month swing-trade scanner dressed as a red-and-gold fortune slot machine. It hunts for **market leaders breaking out of a base**, the pattern behind most +40–50% runs, and lands on one pick with a full playbook.

**How it thinks**
1. **Market regime:** SPY against its 10, 30 and 40-week MAs. In a correction, confidence is cut and capped.
2. **Trend template:** eight checks in the style of Minervini (stacked, rising 10/30/40-week MAs; 30%+ above the 52-week low; within 25% of the high; beating SPY).
3. **Relative strength:** weighted 3/6/9/12-month performance against SPY, plus whether the RS line is at a new high.
4. **Setup:** base, pivot, depth, tightness and breakout volume. It never chases more than 5% past the pivot.
5. **Fuel:** weekly volatility, accumulation, and EPS and revenue growth, margins and analyst upside (Alpha Vantage `OVERVIEW`).
6. **House odds:** backtests the stock's own weekly history. How often did a similar setup hit +40% before −10% within 13 weeks?
7. **AI read:** DeepSeek (via OpenRouter) writes a 90-day thesis with catalysts, bull/base/bear scenarios, a hype check and invalidation, and sees how past picks did.
8. **The play:** stop 7–10% below entry; sell a third at +20% (stop to break-even), a third at +40%, and the rest at +50% or on a weekly close below the 10-week MA; exit at week 6 if it isn't up 10%; 13-week horizon. Position size comes from your bankroll and the risk-per-bet setting.

The **track record** replays every pick against the playbook on weekly bars and feeds the results back to the AI.

**The show:** 5×3 reels (WILD dragons, SCATTER lanterns, BONUS envelopes), a pagoda cabinet with chasing bulbs, a lever, anticipation reels, MEGA and BIG WIN screens with coin fountains, fireworks and confetti, screen shake, and synthesized sound (gong, bells, coin clinks, a spin ratchet and an optional koto music loop).

**Setup:** add a free [Alpha Vantage key](https://www.alphavantage.co/support/#api-key) in Settings. The free plan allows 25 calls a day; a first spin uses about 15, and data is cached. An OpenRouter key is optional and enables the DeepSeek read. Keys stay in your browser's localStorage. **Demo spin** plays the whole thing on synthetic data.

Not financial advice. +40–50% in 3 months is a tail outcome; the system relies on small losses and big winners.
