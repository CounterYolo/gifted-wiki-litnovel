# Changelog

Changes to the Gifted Fan Wiki and Bastian's status tracker, newest first.

## 2026-11-09
- Advanced attributes: percentages now shown only for Talented and Gifted; other AA's show their tier without a percentage until the story clarifies how tiers relate to the bonus.

## 2026-11-08
- Affinity panels: now laid out like body features (Ch. | Grade | Rating | From), one row per change, showing the full rating instead of a +/− change.
- Path panels: the tier rewards table now shows even when "Full breakdown" is off; the box only adds the step-by-step table.
- Clickable items no longer have a dotted underline (the pointer still changes on hover).

## 2026-11-07
- "Achievements" reference tab in GoogleSpreadsheet entirely rewritten to accomodate the changes below. Additional reference tab called "Details" also added to said GoogleSpreadsheet.
- Info panels: every item can now be clicked for details (basic attributes, advanced attributes, affinities, body features, boons, paths, skills, spells, achievements, skill seeds). A **Popup / Dropdown** switch picks how they open, and a **Full breakdown** checkbox shows every step change instead of a summary.
- Skill Seeds: new dropdown. Seeds used straight away are struck through; bought seeds show their grade and type from the Details tab until they are used or sold off.
- Column 3 now has 2 rows of checkboxes to show or hide each optional dropdown (paths on the first row, the rest on the second), remembered in each browser.

## 2026-11-01
- Affinity: the "Castable Affinities" dropdown is replaced by a **Castable & Tier** checkbox by the Affinity heading (off by default). When ticked, each affinity shows its type in italics after its grade ("T1 affinity"), lined up in one column. Affinities Bastian can only cast through others appear as an extra row in italics, with a dashed EQUIV oval and their type (e.g. Dream: *EQUIV-Moderate*, "T2, Life+Shadow", *108*). The EQUIV value is the average of the two affinities, then lowered one grade (Potent 116 + Moderate 100 → Strong 108 → Moderate 108). This grade "downgrade" is to help illustrate that there is indeed an advantage to combining affinities to a higher tier -- if someone needed intends to use that higher tier for skills & spells primarily vs the lower-tier affinities.
- Spells: "Spells Learned" and "Spells in Progress" are combined into one **Spells** dropdown with **Learned / In-Progress / Lost** tabs in its heading. The tabs only appear once Bastian has spells, and Lost only once a spell has been lost. Spells of his own direct affinities are listed before those cast through combined ones like Life+Shadow=Dream.
- Advanced Attributes: the "XP" checkbox is now **Tier**. When ticked it shows each AA's tier in italics (Talented T2 AA, Gifted T3 AA; Aethersensing and Aether Manipulation assumed as T1 AA's for now), lined up in one column, with each one's bonus % by its number.
- Body Features: the BMC checkbox is now **BMC & BWC**. Aether Channels also show their capacity in Base Weak Channels (Weak 100 = 1 BWC), assuming channels scale the same way as cores.
- How the numbers work:
  - The Talented/Gifted note is replaced by a new **Advanced attributes** section on the advanced attribute tiers (T1 +10%, T2 +20%, T3 +40%, T4 +80%…, scaled by rating, fractions dropped; Talented is T2, Gifted is T3).
  - "Aether Core scaling" is now **Aether Core & Aether Channels scaling**, covering both BMC and BWC.

## 2026-10-30
- Achievements & Path Progress: Adjusted into 3 variants 
  - **Age Summary** (default): Summary of info by age in the series. Due to the timeskips not always being on a year-by-year basis, this isn't an exact science
  - **Chapter Summary**: Summary of info by chapter in the series.
  - **By Entry** (old way): Has actual info by row entry in the GoogleSpreadsheet -- as it generally appears in the chapter. Best tab for verifying if the info going into the tracker was entered correctly.
- How the Numbers Work: section is now a button on the top bar of the tracker, that is a dropdown above the status sheet when clicked

## 2026-10-28
- Active Paths: a new dropdown next to the path count chooses how the path bars look:
  - **Classic view** (default): the original bar, filled toward the next tier's total. This is how one would expect the bar to look from how the status screen looks.
  - **Current tier progress**: the bar shows only the current tier, and the number beside it becomes the % done in that tier. This helps clarify how far along someone is along the current tier of a path.
  - **Full path**: one bar for the whole path, with a separator between each tier at its true position (IX|X halfway on basic paths, IV|V halfway on advanced). The small early tiers grow steadily in size. This helps clarify & give context to how far along someone is to the full completion of a path.
- Advanced Attributes: a new **XP** checkbox (off by default) shows the XP% modifier bonus to path rewards & path progress speed as a result of the Talented/Gifted Advanced Attribute. It displays the whole percentage rounded down, as that is how the author also calculates path progress through this advanced attribute.
- Body Features: a new **BMC** checkbox (off by default) shows the Aether Core's capacity in Base Minor Cores next to its rating, calculated from the Aether Core scaling table using a piecewise linear formula to estimate the BMC between established breakpoints.

## 2026-10-25
- Per suggestion from Fred on Discord "Switch to HSL, and use higher luminosity for brightness", colors adjusted accordingly and the grade 1 gray now looks like a light red (light pink).
- Notes section below tracker now also includes an Aether Core Scaling section

## 2026-10-22
- Grade colors adjusted to match the guardian bracelet's color order from chapter 148 (book 3 chp 26): red (lowest) → orange → yellow → green → blue (highest). For easier color differentiation & to less emphasize the lowest grades/paths, red was replaced with gray.

## 2026-10-18
- Added a **Spreadsheet** button to the top bar that opens the Community GoogleSpreadsheet the tracker reads from (reads & auto-updates from the Achievements tab specifically from that web link).
- Renamed the **Royal Road** button to **Ellake's Royal Road** for added clarity that the Spreadsheet isn't updated by Ellake.

## 2026-10-14
- GitHub depository for Gifted Fan Wiki created
- Tracker branch created that only does the tracker (as rest of wiki is still WIP)
- Tracker linked to **Achievements tab** of the Google Sheet directly every time it loads, so new chapters only need to be added to the sheet. If the sheet can't be reached, the page uses its saved copy.
- Added three columns to the Achievements tab (Achievement?, Path Progress, Status Changes) so the tracker can rebuild every earlier status screen exactly.
- Tracker published on GitHub Pages from the `tracker` branch.

