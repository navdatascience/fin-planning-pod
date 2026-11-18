# Fin Planning Pod — India Wealth & Financial Planning Video Library

Structured extraction of India wealth-management / financial-planning YouTube videos into the
`Financial_Planning_Extracted.xlsx` template format — **one individual spreadsheet per video**.

## Deliverable: individual spreadsheets
**`spreadsheets/` — 218 individual .xlsx files**, one per video, named `V<nnn>_<video_id>_<title>.xlsx`.
Each file is a single "Financial Plan" sheet in the exact template layout:
Pre-Tax Income → Post-Tax Monthly Calculation → Responsible Spending → Bonus Spending →
Monthly Investment Allocation → Savings Spent → Current Portfolio Allocation,
plus FIRE / passive income / side-hustle extras, strategy summary, key lessons, and notes on missing/unclear figures.
Each file carries its own YouTube link at the top.

- `spreadsheets_index.json` / `catalog.json` — list of every video, its YouTube link, source, status, and its spreadsheet file
- `Financial_Planning_Template_Original.xlsx` — the original template file supplied on 2026-11-18
- `data/extractions.json` — merged structured extraction data behind the spreadsheets
- `transcripts/<video_id>.txt` — plain-text transcript used for each extraction

## Coverage (2026-11-18, first full run)
| Source | Videos |
|---|---|
| PerspectiveByICM channel (@PerspectiveByICM/videos) | 21 |
| NRI Wealth Stories (PLE-4XBQNfzW6vDzJytUBNBJjD1vWwh-NN) | 15 |
| Life Beyond Freedom (PLBM2AYYPgO_Sdli5mTcYxm5Rq0gQFCFwI) | 18 |
| Side Quest (PLJxWDsYbHwPY) | 6 |
| Interesting people (PLBM2AYYPgO_Tb-wz90suPEajJY55B65vG) | 48 |
| Net Worth Show with INDmoney (PLkrXev16srPB3tlGBpIe7mRIIOZmJdyqK) | 110 |
| **Total listed (unique)** | **218** |

- Transcripts pulled and extracted: **214** (those 214 spreadsheets are fully filled from their transcripts; the 4 below are present as files with status noted)
- Private / unavailable (in INDmoney playlist): 3 — `jxXvguJ0g1g`, `9Q7coudMYW0`, `StxzTy-PcdY`
- Subtitles disabled: 1 — `2I92PFgzDgg` (Sandeep Tandon episode)

Amounts are INR, exactly as stated in each video's transcript. Blank = not stated in that video — never estimated.
Ranges are recorded at the low end with the full range in the sheet's notes. Foreign-currency figures stay in the notes in their original currency.

## Weekly exercise
Every week the six sources above are re-checked for new videos. Each new video gets its own new individual spreadsheet in `spreadsheets/` (next V-number), its transcript and extraction are added, and the update is pushed here with the new titles named in chat.
