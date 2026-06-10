# Michigan AI Infrastructure — Projected Water & Power Burden

**Interactive visualization · Dr. Mario DeSean Booker, Ph.D. · Purdue University Global**

Live tool: [michigan_water_power_projection.html](https://drmariodesean411-arch.github.io/michigan-ai-power-map/michigan_water_power_projection.html)

Part of the [Michigan AI Power Map](https://drmariodesean411-arch.github.io/michigan-ai-power-map/) research project.

---

## What this tool does

This visualization projects water consumption and power demand across ten verified Michigan AI data center sites from 2026 through 2030, applying the Gartner electricity demand growth model to each site's verified baseline figures.

Drag the year slider. Watch what happens to Flint.

The tool displays two data layers toggled by the user:

**Water burden** shows each site's projected daily water consumption in gallons against a fixed reference line representing Flint's daily municipal water usage (9.59 million gallons per day, derived from the verified 3.5 billion gallon annual supply). The Flint line does not move. Every other line does.

**Power demand** shows each site's projected megawatt load scaled by the Gartner growth multiplier. The same nine active sites that consumed approximately 4,300 MW at baseline are projected to demand roughly 8,600 MW by 2030.

---

## Growth model

The projection applies the Gartner (November 2025) electricity demand forecast for global data centers:

| Year | Multiplier vs. 2026 baseline |
|------|------------------------------|
| 2026 | 1.00 (baseline) |
| 2027 | 1.16 (+16%) |
| 2028 | 1.38 (+38%) |
| 2029 | 1.62 (+62%) |
| 2030 | 2.00 (×2.0 Gartner peak) |

Gartner projects global data center electricity consumption rising from 448 TWh in 2025 to 980 TWh by 2030. AI-optimized servers alone are projected to increase nearly fivefold, from 93 TWh to 432 TWh over the same period. Water consumption scales proportionally because cooling demand tracks power demand.

---

## Water consumption methodology

All water figures use the IEA and Congressional Research Service baseline: a 100 MW U.S. data center consumes approximately 530,000 gallons per day. Figures scale linearly by site capacity.

The **Flint comparison baseline** is 3.5 billion gallons annually (verified City of Flint utility data), equivalent to 9.59 million gallons per day. Every site panel and projection uses this figure as the community impact reference. Flint is not an abstraction. It is a city of 81,000 people whose water system became a national crisis. Using it as a baseline is a deliberate research and communication choice.

**Saline Township (Stargate) is flagged as disputed.** The developer claims approximately 20,000 gallons per day via closed-loop air cooling. The IEA methodology for a 1,400 MW facility using evaporative cooling would project 7.42 million gallons per day. No independent verification of the closed-loop claim has been published. The visualization uses the developer's figure and flags it accordingly. The research program treats disputed figures as distinct from verified empirical data.

---

## The ten sites

| Site | Company | Status | MW (2026) | White % | Median Income |
|------|---------|--------|-----------|---------|---------------|
| Saline Township (Stargate) | OpenAI / Oracle / Related Digital | Under construction | 1,400 | 89% | $98,000 |
| Van Buren Township (Project Cannoli) | Google | Approved | 1,000 | 67% | $62,000 |
| Marshall | Alterra Development | Proposed | 1,400 | 79% | $48,000 |
| Lyon Township (Project Flex) | Verrus / Anthropic | Proposed, contested | 500 | 82% | $105,000 |
| Hyperscale Data Campus | Hyperscale Data Inc. | Active | 340 | N/A | N/A |
| Dorr Township | Microsoft | Proposed | 300 | 91% | $72,000 |
| Gaines Township (Switch Pyramid) | Switch | Active | 237 | 84% | $68,000 |
| Gaylord / Otsego County | Undisclosed | Proposed | 200 | 93% | $55,000 |
| Ypsilanti Township | U-M / Los Alamos Natl. Lab | Proposed, contested | 100 | 42% | $41,000 |
| Mundy Township | SanDisk | **Withdrawn** | 0 | 96% | $78,213 |

Demographic data: U.S. Census Bureau American Community Survey 5-year estimates (2020). Income figures are median household income.

**Ypsilanti Township** is the only majority non-white site in the dataset (42% white, $41,000 median income). It carries the lowest projected water consumption of any active site. The Ypsilanti Community Utilities Authority nonetheless imposed a 12-month water moratorium in April 2026. The University of Michigan purchased the 124-acre site anyway.

**Mundy Township** is the key validation case. SanDisk abandoned a $63 billion investment entirely rather than accept community oversight after residents elected an anti-megasite supervisor in November 2024. The state had already spent $260 million preparing the site. The corporation walked away. The contrast with sites where communities have organized resistance and been overruled is the empirical foundation of the digital redlining framework.

---

## Sources

- Gartner Inc. (November 17, 2025). Electricity demand for data centers to grow 16% in 2025 and double by 2030. https://www.gartner.com/en/newsroom/press-releases/2025-11-17-gartner-says-electricity-demand-for-data-centers-to-grow-16-percent-in-2025-and-double-by-2030
- International Energy Agency (2024). Data Centres and Data Transmission Networks. https://www.iea.org/energy-system/buildings/data-centres-and-data-transmission-networks
- United Nations University INWEH (June 8, 2026). Environmental Cost of AI's Energy Use: Carbon, Water and Land Footprints. https://unu.edu/inweh/news/environmental-cost-of-AIs-Enrgy-use-carbon-water-and-land-footprints
- Congressional Research Service (2024). Data Centers: Power and Water Demands.
- City of Flint Utility Data (verified 2025). Annual municipal water consumption: 3.5 billion gallons.
- U.S. Census Bureau. American Community Survey 5-year estimates (2020). https://www.census.gov/programs-surveys/acs

---

## Related publications

Booker, M. D. (2025). Digital redlining: AI infrastructure and environmental racism in contemporary America. *World Journal of Advanced Research and Reviews, 27*(01), 974–988.
https://doi.org/10.30574/wjarr.2025.27.1.2602

Booker, M. D. (2025). Watts the problem? Digital redlining and the hidden energy crisis Lyon Township never knew it approved. *World Journal of Advanced Research and Reviews, 28*(03), 2124–2133.
https://doi.org/10.30574/wjarr.2025.28.3.4306

Booker, M. D. (2025). Digital redlining validated: Corporate withdrawal from white communities confirms environmental racism in technology infrastructure. ResearchGate.
https://doi.org/10.13140/RG.2.2.35138.70081

---

## Technical notes

The visualization is a single self-contained HTML file. No server, database, or internet connection is required after download. It runs in any modern browser. All projection calculations execute client-side in JavaScript.

The file uses Space Grotesk and Space Mono typefaces loaded from Google Fonts. An internet connection is required for the fonts to render correctly, though the visualization functions without them.

All data is hardcoded from verified sources as of June 2026. The file does not update automatically. When site status changes, the file requires a manual update.

---

## License and attribution

This visualization is part of an ongoing peer-reviewed research program. Data and methodology are documented in the publications listed above.

If you cite this tool, use:

Booker, M. D. (2026). Michigan AI infrastructure projected water and power burden [Interactive visualization]. GitHub Pages. https://drmariodesean411-arch.github.io/michigan-ai-power-map/michigan_water_power_projection.html

For research inquiries: mario.booker@purdueglobal.edu

---

*Verified June 2026. Part of the Digital Redlining Research Program.*
