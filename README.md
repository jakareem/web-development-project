# web-development-project
Tick by Tick: Learn to Trade Futures  I built this small website to explain how futures trading works in plain language. It starts with a profit and loss calculator so I can practice the math of ticks
Live site: https://YOUR-USERNAME.github.io/YOUR-REPO/

What's on the site
A profit and loss calculator for ES, MES, NQ, MNQ, CL, and GC contracts, with long and short positions
A six-step learning path that I follow as a beginner
A glossary of key terms: tick, margin, leverage, expiration, long and short, and stop orders
A risk section with an education-only disclaimer
How it's built

I wrote it as a single index.html file with inline CSS and JavaScript. It has no build step, no dependencies, and no external requests. It supports light and dark mode, works on phones, and can be used with a keyboard.

Run it locally

Open index.html in a browser.

Publish it with GitHub Pages
Push index.html to the root of the main branch.
In the repository, go to Settings > Pages.
Under Build and deployment, choose Deploy from a branch, select main and / (root), and save.
Wait a minute or two, then open the link shown on that page.
Contract specs

The calculator uses these dollar values per point and tick sizes. I recommend confirming them with the exchange, because specifications can change.

Contract	Dollars per point	Tick size
ES	$50	0.25
MES	$5	0.25
NQ	$20	0.25
MNQ	$2	0.25
CL	$1,000	0.01
GC	$100	0.10

The calculator shows results before commissions and fees.

Disclaimer

Trading futures involves substantial risk of loss and is not suitable for every investor. Because of leverage, you can lose more than your initial deposit. I share this project for education only. It is not financial, investment, or legal advice, so talk to a licensed professional before you trade with real money.
