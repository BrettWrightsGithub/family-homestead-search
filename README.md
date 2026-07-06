# Family Homestead Search

Regional decision framework and search playbook for a multi-generational family homestead matching specific criteria.

## What This Is

- A geographic decision framework identifying US sub-regions that meet multi-hazard, Costco access, fertility, and utility constraints
- A search playbook with listing-site queries, saved-search alerts, and verification checklists
- A prioritized tier ranking of candidate regions (Tier 1: Middle TN, KY Bluegrass fringe, VA Southside/Piedmont edge; Tier 2: NC Piedmont, Central Texas exclaves)

## Live Deployment

[View live on Vercel](https://family-homestead-search.vercel.app/)

## Quick Start

1. Clone this repo
2. Open `index.html` in your browser
3. Use the search playbook and checklist to evaluate candidates

## Priority Options (Decision Framework)

This page documents the research framework. To narrow the search further, prioritize:

| Dimension | Options | What to Tell Your Agent |
|-----------|---------|-------------------------|
| **Aesthetic preference** | Rolling pasture (KY), mixed woods+pasture (TN), flatter row-crop (TX/NC Piedmont) | "We want [rolling pasture / mixed woods+pasture / flatter row-crop]. Focus on [KY Bluegrass / Middle TN / TX/NC Piedmont]."
| **Critical infrastructure** | Fiber internet, hospital-within-30min, school district rating, or none of the above | "Fiber internet is [critical / nice-to-have / not required]. Must be within 30min of a hospital. School district rating [matters / doesn't matter]."
| **Distance from extended family** | Current location matters for "what's actually feasible to drive to inspect." | "We're currently in [location]. We can drive up to [X] hours for on-site visits. Prioritize regions within that radius." |

## How I Can Help Further

- Provide drive-time estimates from specific addresses to the nearest Costco
- Run hazard overlay (FEMA NRI, USFS WHP, USGS seismic) on specific candidate addresses
- Pull soil quality (NRCS SSURGO) for specific parcels
- Summarize county-level crime statistics from FBI UCR data

## Security Note

This page uses Tailwind CSS via CDN for rapid prototyping. For production use with SRI, configure a build step with Tailwind CLI.

## License

CC0 1.0 Universal (public domain) — use and remix freely.

## Credits

Research compiled by Hermes Agent. Hazard and soil data sources: FEMA National Risk Index, USFS Wildfire Hazard Potential, USGS, NRCS Web Soil Survey. Costco locations from Costco.com sitemap. Crime data from FBI UCR.

---