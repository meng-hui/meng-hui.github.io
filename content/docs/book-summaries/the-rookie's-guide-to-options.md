---
title: "The Rookie's Guide to Options"
weight: 10004
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# The Rookie's Guide to Options - by Mark Wolfinger

###### Date Read: 2020-07-12

### Notes

option price = intrinsic value (how much it is ITM) + time value (volatility & time to expiration)

When buying options, you profit only if stock closes above strike by option price.

- (1) buy OTM option = time value
- (2) sell near expiration = intrinsic value
- (2) > (1) to profit from buying options

equivalent positions: S = C -P

Basic Strategies:
- Covered Call Writing: S -C
- Collar: S -C +P
- ≈ "sell put spread": -P(high) + P(low)
- ≈ "buy call spread": +C(low) -C(high)
- Cash-secured Put Writing: -P

Greeks

Delta 𝛿

- Bullish = long delta, positive delta
- C = 0 to 100
- P = -100 to 0
- S = 100
- e.g. C𝛿 = 30. If S +$1, C +$0.30
- e.g. P𝛿 = -60. If S +$1, P -$0.60
- 𝛿 measures expected change as underlying changes by $1.
- 𝛿 is probability option finish ITM.
- Position 𝛿 is also the equivalent number of shares.

Gamma γ
- γ is the rate of change of 𝛿 when S +$1.
- buying options = positive γ

vega ν
- v is always positive
- v measures the change in option price when there is a one point change in volatility
- Typical v, longer term option > nearer term.
- Typical v, OTM > ATM > ITM.

theta θ
- θ is the change in option price as one day passes
- option owners have negative θ
- option sellers have positive θ

Checklist for selling put spreads
- bullish bias
- OTM reasonably
- high probability of expiring worthless, look for low delta (1-8)
- enough premium to be worth selling. Look at price. Check if bid-ask spread is too risky for a quick exit
- position size as if you are holding stock
- CONS: poor risk reward ratio

Iron condors

When you have no bullish or bearish bias, when you believe it will be range bound.
