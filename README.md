# Chess Analysis Board

A single-page chess analysis board: Stockfish engine lines, evaluation bar, suggestion and threat arrows, move feedback, opening explorer, bots and board/piece themes. For studying games, reviewing your own play and practising against bots.

## Put it online with GitHub Pages

1. Sign in at github.com and create a **New repository** (for example `chess-analysis`). Make it **Public**.
2. Click **Add file → Upload files**, drag in `index.html`, `.nojekyll` and `README.md`, then **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then **Save**.
4. Wait about a minute. Your site will be at `https://YOUR-USERNAME.github.io/chess-analysis/`.

## Notes

- Stockfish loads from a public CDN, so visitors need an internet connection for full-strength analysis. Without it, a weaker built-in engine is used.
- Settings and themes are saved in each visitor's own browser.
- Use it for analysis and practice. Do not use engine help in live rated games, which breaks the rules of sites like Chess.com and Lichess.
