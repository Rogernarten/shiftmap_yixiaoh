# Process log

How each version came about: what I asked for, what Claude proposed, where I pushed
back, and what I decided myself.

## Direction backlog (go wide, v01–v12)
- [x] Bill of lading — the page is a shipping document (v01)
- [x] Flow map — bubbles on a real map + pie charts (v02, from v01 feedback)
- [x] Antique sea chart — waterlined coasts, sea routes, sailing ships (v07)
- [x] Departure board — split-flap rows with tile bars (v04)
- [x] Care label — woven composition label + flipping hang tag (v06)
- [ ] Passport — each country a visa stamp
- [x] Data terminal — dense panels, keyboard views (v09)
- [x] Consulting exhibit — answer-first cover + 4 exhibits (v05)
- [ ] Magazine long-read — "The great sweater migration"
- [x] Container stack — 1 container = 1%, crane moves the shift (v03)
- [x] Brutalist type-as-chart — font size = share (v08)
- [ ] Win95 app — "Shiftmap.exe"
- [x] One-page brief — calm single column, print-ready (v12)

## Log

### Round 0 — setup (2026-10-09)
- **Asked:** turn my country-of-origin research tool idea into this assignment.
- **Claude proposed:** a fictional product name (Shiftmap), a fictional sample
  category with consistent numbers, a three-phase plan and 12 directions.
- **I decided:** keep the concept but make every name and number fictional; start
  small (setup + one version) before going wide.

### v01 — Bill of lading
- **Asked:** follow the plan, small scope first.
- **Claude built:** the whole page as a bill of lading. COO mix is the cargo
  manifest (red ribbon = Northfold, blue carbon = industry), the recommendation is
  an amendment stamp, "how it works" is the terms of carriage.
- **My take:** looks good, but it isn't intuitive for business readers. I want a map
  or pie charts, and there is too much text.

### v02 — Flow map
- **Asked:** a visual-first page: map and pie charts, far less text.
- **Claude built:** a map-first page. Bubbles on a real map of South and Southeast
  Asia are sized by share; a toggle switches Northfold today / Industry / After shift,
  and the shift is drawn as arrows CN→VN (+12) and CN→KH (+8). Below, three pie
  (donut) charts compare the mixes; "why" became three big numbers; "how it works" is
  three short steps. Country colors were checked for color-blind safety.
- **My take:** _to fill after review_

### Round — rule + v03–v05 (2026-10-10)
- **Claude proposed:** turn my v01 feedback into a rule for every version: the mix and
  the shift must be visual (map or chart), with minimal copy. Then three visual-first
  directions: container stack, departure board, consulting exhibit.
- **I decided:** adopt the rule (added to AGENTS.md) and go with all three.

### v03 — Container yard
- **Claude built:** a port yard. 100 containers (1 = 1% of units) stacked by origin;
  "Run the shift" lifts 20 boxes off China with a crane path and lands 12 in Vietnam,
  8 in Cambodia, recoloring them on arrival. Industry view re-stacks the same 100.
- **My take:** _to fill after review_

### v04 — Departure board
- **Claude built:** a dark split-flap departures board. Each origin is a row with its
  share, a tile bar (1 tile = 4%) and an action/status column; the three views re-flip
  the board (ACTION → VS NORTHFOLD → STATUS: DEPARTED 20 / ARRIVED +12).
- **My take:** _to fill after review_

### v05 — Exhibit deck
- **Claude built:** a consulting-style deck on one scrolling page. The cover states the
  answer with a today-vs-after stacked bar; then Exhibit 1 dumbbell (Northfold vs
  industry), Exhibit 2 ranked industry bars, Exhibit 3 waterfall of China's share
  (52 → 32), Exhibit 4 vendor capacity bars; a recommendation slide closes it.
- **My take:** the most professional of the set, and it carries enough information (answer first, then the evidence).

### Round — v06–v08 (2026-10-10)
- **Claude proposed:** three more directions that keep the visual rule but push the
  metaphor further: care label (origin mix as a fabric-composition label + hang-tag
  pie), antique nautical chart (the shift as sea routes), brutalist type-as-chart
  (font size = share).
- **I decided:** go with all three.

### v06 — Care label
- **Claude built:** a woven care label lists the origin mix as a fabric composition with bars and
  industry ticks; a kraft hang tag flips (click or toggle) from today's pie to the
  after-shift pie; reasons are care symbols (wash tub 31%, triangle 14, iron −5%).
- **My take:** also looks professional and carries enough information; second favourite after v05.

### v07 — Sea chart
- **Claude built:** the real map redrawn as a 19th-century sea chart: waterlines, graticule, rhumb
  lines, compass rose, cartouche. Red-ink circles (Northfold) / blue-ink (the trade);
  "The new route" adds dashed sea lanes CN→VN, CN→KH with ships sailing them.
- **My take:** _to fill after review_

### v08 — Type is the chart
- **Claude built:** black-and-white brutalist page; each country name's font size is proportional
  to its share (plus a bar), China in red when over-weight; switching views animates
  the type sizes, and gainers invert to black.
- **My take:** _to fill after review_

### Review after v08 (2026-10-10)
- **I decided:** v05 (exhibit deck) is the strongest direction, with v06 (care label)
  second: both look professional and carry enough information for a sourcing manager.
  These become the lead candidates for narrowing.

### Round — v09–v12 (2026-10-10)
- **Claude proposed:** either start narrowing now, or spend the last four go-wide slots
  on more *professional* genres so narrowing has more serious candidates.
- **I decided:** explore four more professional styles (data terminal, broadsheet
  front page, product UI, one-page brief), then narrow from v13 with v05 as the lead.

### v09 — Terminal
- **Claude built:** a dark data terminal: ticker, command line, five panels (mix bars Northfold amber vs industry cyan, diverging gap vs industry, key stats, shift scenario table, vendor leads). Views switch with buttons or keys 1/2/3; the gap panel animates from +25 to +5.
- **My take:** _to fill after review_

### v10 — Front page
- **Claude built:** a fictional broadsheet front page (The Sourcing Ledger): lead story with a slope chart of each origin's share, today → after shift or → industry (toggle, animated; hover isolates a line); right rail with industry bars, a market-data table and a 'Vendors wanted' classified; three below-the-fold number stories.
- **My take:** _to fill after review_

### v11 — Product window
- **Claude built:** a product-marketing page whose hero is a live app mock: sidebar history, scope chips, category tabs (sweaters / leggings / tees / jackets, all from the brief's sample data), KPI tiles, origin bars with industry ticks, a recommendation badge (Rebalance / Renegotiate freight / Add origin) and vendors. The ask box fakes the report steps and routes English or Chinese questions to a category.
- **My take:** _to fill after review_

### v12 — One-page brief
- **Claude built:** a Swiss-style one-page memo (TO / FROM / RE / DATE) with numbered sections: 01 the answer, 02 small multiples Northfold vs industry, 03 stacked bars today vs after (checkbox adds the industry bar), 04 three numbers, 05 vendor table, 06 next step. Print / save-as-PDF button with a print stylesheet.
- **My take:** _to fill after review_
