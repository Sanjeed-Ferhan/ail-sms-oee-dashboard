# AIL SMS — Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **AIL — SMS (Steel Melting Shop)** covering **CCM** and **Furnace 1–3**, shifts A–C.

## Features
- **Toggle:** Last day (12-Oct-2026) and Month-to-date (Oct 2026)
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs targets **A90 / P86 / Q97 / OEE75**
- Where time is going (planned / available / down)
- OEE by machine (CCM, Furnace 1, Furnace 2) + Find-the-bottleneck (OEE factor constraint)
- Top downtime + downtime by category (min)
- **Opportunity Loss = NPT min ÷ cycle time (min/MT)** (CCM 2, Furnace 6) → lost output (MT)
- Production & OEE trend (last 16 days)
- Shift Action Board — downtime reasons with **responsible team** tagging
- Shift OEE and Gemba walk

## Data source
`Production Report` and `SMS Breakdown` tabs of the AIL SMS OEE sheet.

## Usage
Open `index.html` in any browser. Use the toggle to switch reporting period. Print (Ctrl+P) to PDF for a one-pager.

## Notes
- OEE = Availability × Performance × Quality.
- Data through 12-Oct-2026.
