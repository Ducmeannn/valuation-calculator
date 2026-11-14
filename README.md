# DDM and CAPM Valuation Calculator

A one-page web tool that values a dividend-paying share.

- Cost of equity with CAPM: `rf + beta x equity risk premium`
- Share value with the Gordon Growth model (DDM): `D0 x (1 + g) / (ke - g)`
- Upside vs the current price, a simple Buy / Hold / Sell rule, and a sensitivity table (growth vs cost of equity)

Built from the DDM and CAPM methods I used in my university valuation reports. Built with AI assistance (vibe coding) as a learning project.

## Use it
Open `index.html` in a browser, or use the GitHub Pages link of this repo.

## Limits
- One-stage DDM only: it fits mature, dividend-paying companies
- The result is very sensitive to growth and cost of equity (see the table)
- Learning tool, not investment advice
