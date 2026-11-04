# Gold loan estimator

A concept prototype by Gaurav Kumar: an accurate, explained gold loan estimate before a doorstep visit, with eligibility checks before a visit is booked, so fewer visits end without a loan.

**Try it:** https://dalpatyan.github.io/gold-loan-estimator/

## What it shows

- An estimate without logging in: items, karat (with a "not sure" range), stones, RBI limits and the full working
- PAN and consent before any visit slot is offered
- A different message for each check result: clear, PAN not found (with a fallback), wilful defaulter, politically exposed person, or a possible AML or sanctions match
- Date, time and a pickup address a loan manager can find

All data, rates and checks are simulated. Not affiliated with any lender. Prototyped with Claude.

The whole prototype is one self-contained file, `index.html`, with no build step or dependencies.
