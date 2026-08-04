# Retirement Accumulation Planner

A standalone, interactive retirement savings planner. It presents a guided, slide-based walkthrough of a retirement forecast and recalculates the projection as assumptions change.

## Run locally

No build step or dependencies are required. Open `index.html` in a modern web browser.

## Features

- Editable salary, contribution, savings, tax, return, and age assumptions
- Annual salary growth, employer matching, annual contributions, and annual compounding
- Three investment phases: aggressive, normal, and conservative
- Projected retirement balance, contributions, investment growth, final salary, chart, and annual forecast table
- Keyboard, button, dot, touch-swipe, browser-history, and reduced-motion deck navigation
- Responsive layout and accessible navigation announcements

## Projection rules

- The forecast runs from **Starting age** through the year before **Retirement age**.
- Contributions are made from **Saving starts** through the year before **Saving ends**.
- Each year's investment growth is applied to the opening balance; that year's contribution is then added.
- The conservative phase occupies the final configured years before retirement. The aggressive phase is twice as long, and the normal phase fills the remaining time.
- To keep phases valid and non-overlapping, the conservative phase is capped at one-third of the years between starting and retirement ages.
- Retirement age is always kept later than starting age.

This is a planning estimate only, not investment, tax, or financial advice.
