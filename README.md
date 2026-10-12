# Price sync site (GitHub Pages)

`prices.json` = the owner's **signed** price list (KeyMaker), **encrypted** (AES-GCM, key in the KeyMaker folder, never here).
The partner and client price apps download it at start (at most every 12 h) and apply it only when it is genuine and newer.

Written and pushed by `Source code/tools/apply-prices.mjs` (⚡ Apply prices in the owner app). Do not edit by hand.
