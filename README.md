# Fin Planning Pod — India Wealth & Financial Planning Video Library

Structured extraction of India wealth-management / financial-planning YouTube videos into the
`Financial_Planning_Extracted.xlsx` template format.

## Main deliverable
**`Financial_Planning_All_Videos.xlsx`** — 221 sheets:
- `README` — how the workbook is built
- `Index` — all 218 videos with title, source playlist/channel, person, city, headline net worth, **YouTube link**, and a link to its per-video sheet
- `Master_Data` — one row per video, every template field as a column (compare across videos)
- `V001`–`V218` — one sheet per video in the exact template layout:
  Pre-Tax Income → Post-Tax Monthly Calculation → Responsible Spending → Bonus Spending →
  Monthly Investment Allocation → Savings Spent → Current Portfolio Allocation,
  plus FIRE / passive income / side-hustle extras, strategy summary, key lessons, and notes on missing/unclear figures

`Financial_Planning_Template_Original.xlsx` is the original template file supplied on 2026-11-18.

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

- Transcripts pulled and extracted: **214**
- Private / unavailable (in INDmoney playlist): 3 — `jxXvguJ0g1g`, `9Q7coudMYW0`, `StxzTy-PcdY`
- Subtitles disabled: 1 — `2I92PFgzDgg` (Sandeep Tandon episode)

Amounts are INR, exactly as stated in each video's transcript. Blank = not stated in that video — never estimated.
Ranges are recorded at the low end with the full range in the sheet's notes. Foreign-currency figures stay in the notes in their original currency.

## Files
- `catalog.json` — machine-readable inventory + per-video status
- `data/extractions.json` — merged structured extraction for all videos
- `transcripts/<video_id>.txt` — plain-text transcript used for each extraction

## Weekly exercise
Every week the six sources above are re-checked for new videos. New videos are transcribed,
extracted into the same template, the workbook is rebuilt, and the update is pushed here with the new titles named in chat.
