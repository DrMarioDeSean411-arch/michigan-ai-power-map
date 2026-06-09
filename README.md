# Michigan AI Data Center Power Map

**An interactive research visualization by Dr. Mario DeSean Booker, Ph.D.**
Purdue University Global

Live map: https://drmariodesean411-arch.github.io/michigan-ai-power-map/

---

## What this is

Michigan is in the middle of a data center crisis that most residents never voted for and many have never heard about. Since 2024, more than 30 AI infrastructure proposals have landed across the state. On farmland. Near wetlands. Beside schools. In communities already stretched thin on water and power. This map tracks the ones that matter most to a specific research question: who bears the burden, and who gets the benefit?

This visualization is part of a larger scholarly project on digital redlining. That framework documents how AI and technology companies systematically place environmentally harmful infrastructure in communities with less institutional power to resist, while providing superior environmental protections to more affluent and predominantly white communities. The pattern is not coincidence. It is strategy.

The map plots ten verified sites across Michigan against publicly available demographic data, power capacity figures, and documented community resistance. It is updated as the situation changes.

---

## The research behind it

This map is a living supplement to peer-reviewed scholarship. The foundational publications are:

Booker, M. D. (2025). Digital redlining: AI infrastructure and environmental racism in contemporary America. World Journal of Advanced Research and Reviews, 27(01), 974–988.
https://doi.org/10.30574/wjarr.2025.27.1.2602

Booker, M. D. (2025). Watts the problem? Digital redlining and the hidden energy crisis Lyon Township never knew it approved. World Journal of Advanced Research and Reviews, 28(03), 2124–2133.
https://doi.org/10.30574/wjarr.2025.28.3.4306

Booker, M. D. (2025). Digital redlining validated: Corporate withdrawal from white communities confirms environmental racism in technology infrastructure. ResearchGate.
https://doi.org/10.13140/RG.2.2.35138.70081

The core argument across these works is straightforward. When corporations decide where to put a data center, they are not making a neutral technical decision. They are making a racial and economic one. The same companies that achieve LEED Gold certification and hold community town halls in predominantly white communities operate unpermitted gas turbines and bypass environmental review in predominantly Black and Brown ones. This map makes that pattern visible at the state level.

---

## What the map shows

Each marker represents a verified AI data center proposal, active construction site, or documented withdrawal. Markers are sized by power demand. The larger the dot, the more electricity the facility will consume. Color indicates capacity tier. An outer ring marks sites where community resistance has been formally documented.

### Sites currently tracked

| Site | Company | Status | Capacity | Community |
|---|---|---|---|---|
| Saline Township — Stargate | OpenAI / Oracle / Related Digital | Under construction | 1,400 MW | 89% white, $98K median income |
| Van Buren Township — Project Cannoli | Google | Approved | 1,000 MW | 67% white, $62K median income |
| Marshall | Alterra Development | Proposed | 1,400 MW | 79% white, $48K median income |
| Lyon Township — Project Flex | Verrus / Anthropic | Proposed, contested | 500 MW | 82% white, $105K median income |
| Hyperscale Data Campus | Hyperscale Data Inc. | Active | 340 MW | Genesee County area |
| Dorr Township | Microsoft | Proposed | 300 MW | 91% white, $72K median income |
| Gaylord / Otsego County | Undisclosed | Proposed | 200 MW | 93% white, $55K median income |
| Ypsilanti Township | U-M / Los Alamos Natl. Lab | Proposed, contested | 100 MW | 42% white, $41K median income |
| Gaines Township — Switch Pyramid | Switch | Active | 237 MW | 84% white, $68K median income |
| Mundy Township | SanDisk | Withdrawn | 0 MW | 96% white, $78K median income |

The Mundy Township withdrawal is analytically the most important entry in this dataset. SanDisk abandoned a $63 billion semiconductor campus after the state had already spent $260 million preparing the site, rather than face organized resistance from a 96% white community that elected an anti-megasite township supervisor in November 2024. In predominantly Black and lower-income communities, the same industry continues operating with environmental violations as a cost of doing business. That asymmetry is the argument.

The Ypsilanti Township site is the only majority non-white community in this dataset. It faces a $1.25 billion supercomputing facility developed by the University of Michigan in partnership with Los Alamos National Laboratory for classified nuclear weapons research. The township has passed three formal resolutions in opposition. The utility authority imposed a 12-month water moratorium. The university purchased the land anyway.

---

## A note on corrections

The Lyon Township publication (WJARR, 2025) contained two factual errors identified during post-publication verification and submitted for formal erratum.

Population: Published as 5,000 residents. The correct figure is 23,271 per the 2020 Census.

Water consumption multiplier: Published as 41 times Flint's annual municipal usage. The correct multiplier is 260 times Flint's annual usage, based on verified City of Flint utility data showing 3.5 billion gallons consumed annually.

Both corrections strengthen rather than undermine the research findings. The corrected 260x water multiplier provides a sharper illustration of the resource extraction involved. The corrected population figure demonstrates that even a community of 23,000 relatively affluent and majority-white residents with real institutional capacity can be bypassed when developers exploit existing industrial zoning to avoid public approval processes.

This map reflects the corrected figures throughout.

---

## How to use it

Visit the live site. Hover over any marker to see the full data card for that site: power capacity, racial demographics, median household income, resistance status, and sourced notes. Use the filter buttons at the top to isolate sites by project status.

If you are a researcher, journalist, community organizer, or policymaker, the map is yours to use with attribution. Please cite it as:

Booker, M. D. (2026). Michigan AI data center power map [Interactive data visualization]. GitHub Pages. https://drmariodesean411-arch.github.io/michigan-ai-power-map/

---

## Data sources

All site data is drawn from verified public reporting. No figure in this map is fabricated or estimated without a disclosed source.

United States Census Bureau, American Community Survey 5-Year Estimates (2020)

The Gander Newsroom, Michigan data center directory (updated June 5, 2026)

Planet Detroit, data center coverage (June 2026)

Crain's Detroit Business (May through June 2026)

Detroit News (June 1, 2026)

Eastern Echo and University of Michigan Daily (May 2026)

Ypsilanti Township Board of Trustees, official resolution records (2026)

Fortune (May 2026)

WXYZ Detroit (June 2026)

Southern Environmental Law Center press releases (2024)

City of Flint Department of Utilities, water consumption data (2022 through 2025)

Map topology uses U.S. Census Bureau cartographic county boundaries (2017 edition) via us-atlas@3. Rendered with D3.js and TopoJSON.

---

## About the researcher

Dr. Mario DeSean Booker is a professor at Purdue University Global specializing in digital forensics, AI governance, and technology ethics. His research examines how algorithmic systems and technology infrastructure reproduce racial and economic inequality. He is the author of multiple peer-reviewed publications on digital redlining, algorithmic discrimination, and AI environmental justice, including the foundational digital redlining framework that this map illustrates.

Contact: mario.booker@purdueglobal.edu

---

## License and attribution

Copyright 2026 Mario DeSean Booker. Research and educational use is permitted with full attribution. Commercial use requires written permission. If you build on this work, cite it.

Last verified: June 9, 2026
