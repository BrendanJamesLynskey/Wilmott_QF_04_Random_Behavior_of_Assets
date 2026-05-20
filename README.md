# The Random Behavior of Assets

Deck 04 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_04_Random_Behavior_of_Assets/

A guided tour of chapter 4 of *Paul Wilmott Introduces Quantitative Finance*
(2nd edition, Wiley, 2007) &mdash; from a discrete spreadsheet random walk to
the Wiener process and geometric Brownian motion, the continuous-time model
on which the rest of the book is built.

## What's inside

- Why a model for randomness is needed &mdash; Jensen's inequality and convex payoffs
- Examining returns: stylised facts and the Gaussian-iid assumption
- Timescales: drift $\mu$ scales linearly with $\delta t$, volatility $\sigma$ with $\sqrt{\delta t}$
- The drift $\mu$ &mdash; and why option pricing doesn't need it
- The volatility $\sigma$ &mdash; units, typical magnitudes, historic vs implied
- Estimating volatility from data: sample std of log-returns, annualisation, and the usual pitfalls
- The random walk on a spreadsheet: $\delta S = \mu S\delta t + \sigma S \phi \sqrt{\delta t}$
- The Wiener process $W_t$: defining properties, the $(dW)^2 = dt$ identity
- The accepted model $dS = \mu S\,dt + \sigma S\,dW_t$ (geometric Brownian motion) and the lognormal distribution of $S_T$
- **Interactive GBM path simulator** &mdash; sliders for $S_0, \mu, \sigma, T, N$ plus a *Resample* button; one panel shows ~50 sample paths and the theoretical mean $S_0 e^{\mu T}$, the other shows the histogram of terminal $S_T$ with the lognormal density overlaid; metrics compare empirical mean/std against $S_0 e^{\mu T}$ and $S_0 e^{\mu T}\sqrt{e^{\sigma^2 T} - 1}$

Companion to chapter 4 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
