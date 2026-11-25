# 29 — The Card Game

A single-file, browser-playable version of **29**, the South Asian trick-taking card game. You and a computer partner play against two computer opponents.

## Play
Open `index.html` in any modern browser, or enable GitHub Pages (Settings → Pages → deploy from `main`, root) to play online.

## Rules in brief
- 32 cards (7 to Ace). Rank in each suit: J, 9, A, 10, K, Q, 8, 7.
- Points: J = 3, 9 = 2, A = 1, 10 = 1, others 0. Total 28, plus 1 for the last trick = 29.
- Each player bids once (16–28). The highest bidder secretly picks a trump suit.
- Trump stays hidden. A player who cannot follow suit may press **Show trump**; the suit is revealed and that player must trump if able.
- A bidding side that wins at least its bid scores +1 game point, otherwise −1. First to +6 wins; −6 loses.

## Files
- `index.html` — the whole game (HTML, CSS, JavaScript; no dependencies)
