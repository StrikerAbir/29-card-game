# 29 — The Card Game

A single-file, browser-playable version of **29**, the South Asian trick-taking card game. You and a computer partner play against two computer opponents.

## Play
Open `index.html` in any modern browser, or enable GitHub Pages (Settings → Pages → deploy from `main`, root) to play online.

## Rules in brief
- 32 cards (7 to Ace). Rank in each suit: J, 9, A, 10, K, Q, 8, 7.
- Points: J = 3, 9 = 2, A = 1, 10 = 1, others 0. Total 28, plus 1 for the last trick = 29.
- Bidding (16–28): the first three players may open (the dealer may not). After that the two teams bargain back and forth: raise, say *ditto* (match the bid), or pass. A pass is final, then the partner takes over. When both partners of a side have passed, the other side wins the bid. If the first three pass, the cards are redealt.
- Trump stays hidden. A player who cannot follow suit may press **Show trump**; the suit is revealed and that player must trump if able.
- A bidding side that wins at least its bid scores +1 game point, otherwise −1. First to +6 wins; −6 loses.

## Optional rules (built in)
- **Double / redouble:** after trump is chosen and before the second deal, an opponent of the bidder may double (stake 2 instead of 1). The bidder's side may then redouble (stake 4).
- **7th card:** the bidder may let the 7th card they are dealt set trump. It is set aside and hidden until trump is revealed; it can't be led (unless it is the last card), and it can be shown and played when the bidder can't follow suit.
- **Single hand:** after the second deal, a player may call single hand: no trump, the partner sits out, and the caller must win all 8 tricks alone. Success is +3 game points, failure is −3.

## Files
- `index.html` — the whole game (HTML, CSS, JavaScript; no dependencies)
