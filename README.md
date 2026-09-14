# McDonald's: What Actually Made It More Profitable

*A financial model and analysis built from McDonald's own public filings, looking at where its 2025 profit improvement actually came from, and what the business is worth.*

**By Kaushal Jaiswal** · [LinkedIn](https://www.linkedin.com/in/kaushal-jaiswal) · [GitHub](https://github.com/kaushaljaiswal-fpa)

**Skills demonstrated:** 3-statement financial modeling · DCF valuation · Segment and margin analysis · Power BI (DAX) · Power Query automation · SEC filings research

**Quick links:** [Live one-pager](https://kaushaljaiswal-fpa.github.io/mcdonalds-fpa-portfolio/one-pager.html) · [Excel model](./McDonalds_3Statement_Model.xlsx) · [Power BI dashboard](./McDonalds_Dashboard.pbix)

---

## What is this?

I built a complete financial model of McDonald's Corporation, the kind of work a financial analyst does before recommending whether to invest in, partner with, or work for a company. It includes a full set of linked financial statements, a breakdown of exactly where the company's profit comes from, and an estimate of what the business is worth today, all built from McDonald's own real, publicly filed numbers, not estimates or textbook data.

## Why does it matter?

People often describe McDonald's as a real estate and licensing company that happens to sell burgers, collecting rent and franchise fees rather than running kitchens itself. It is a fair description, but it usually stops there, as a line people repeat without ever putting a number on it. This project does that: it measures, precisely, how much of McDonald's recent profit improvement actually came from that licensing model versus from the business simply running better day to day.

## What does the analysis show?

McDonald's operating margin, the share of every revenue dollar it keeps as profit, rose from 45.2% to 46.1% in 2025. Breaking that change apart by segment shows two very different stories happening at once:

- **McDonald's international business got bigger, not better.** Its own profitability barely moved, but it now makes up a larger share of the total company, 50.7% versus 48.7% the year before, and it happens to run at a healthier margin than the U.S. does.
- **McDonald's licensing business got better, not bigger.** This is a much smaller segment, covering markets run by outside partners under license. Its share of revenue actually shrank, but its profit margin rose from 1.2% to 8.4%, nearly seven times higher than the year before.
- **The U.S., McDonald's largest and most familiar market, held margin back slightly**, losing a little ground on both revenue share and profitability.

Put together, just over half of last year's total margin improvement came from the business getting bigger in an already-profitable place, not from anyone running restaurants better. That is the real, measured version of the "real estate company" idea.

The model also estimates what McDonald's is worth today, using a standard cash flow valuation: **about $172 billion**, which works out to roughly $186 a share, about 40% below where the stock actually trades. That gap is real and worth being upfront about rather than smoothing over. The three honest reasons for it, and the full assumptions behind the $172 billion figure, are laid out plainly inside the model itself.

## What should we take away from it?

The headline is simple: McDonald's got more profitable last year, but "growing into a bigger, better business mix" and "running the existing business better" are two different things, and only one of them showed up much in 2025. That distinction matters for anyone trying to judge whether the improvement continues, since a shift in business mix and a genuine efficiency gain are not equally likely to repeat.

Like any model, this one relies on a handful of simplifying assumptions, held flat where the real driver was uncertain, tapered where a business reason supported it. Each one is disclosed directly next to the number it affects, rather than buried in a separate technical appendix, because a model that hides its own assumptions is less useful, not more impressive.

## How can someone explore the analysis further?

| File | What it is |
|---|---|
| `McDonalds_3Statement_Model.xlsx` | The full financial model. Seven tabs, covering the linked financial statements, the supporting schedules behind them, the segment breakdown behind the finding above, and the valuation. |
| `McDonalds_Dashboard.pbix` | An interactive Power BI dashboard built directly from the same model. |
| `Dashboard_Export.pdf` | A static export of the Power BI dashboard, for viewing without installing Power BI. |
| `one-pager.html` / `one-pager.png` | A one-page visual summary of the finding above. [View it live here.](https://kaushaljaiswal-fpa.github.io/mcdonalds-fpa-portfolio/one-pager.html) |

A reviewer short on time could read just the one-page summary. Someone who wants to see the actual mechanics can open the Excel file, starting with the Cover tab, which indexes every section, then the Segment and Margin Analysis tab, where the finding above is calculated line by line and reconciles exactly to McDonald's own reported numbers.

---

*Built from McDonald's real SEC filings using Excel, Power Query, and Power BI.*
