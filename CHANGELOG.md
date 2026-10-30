# Changelog

Changes to the Gifted Fan Wiki and Bastian's status tracker, newest first.

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

