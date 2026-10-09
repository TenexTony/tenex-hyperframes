# 11 · Spreadsheet to slideshow

## What it makes

A 45-second widescreen update with three data findings, a title, and a closing card.

## What to attach

An Excel file or CSV. Optional: your logo. For Excel, specify the sheet to use.

## The prompt

```text
Turn [spreadsheet filename] into a 45-second widescreen business update video, 16:9. Use sheet [sheet name, or "not applicable for CSV"] and these columns: [column names].

Audience: [who will watch]
Question to answer: [the business question]
Reporting period: [period]
Units or currency: [units]
Style: [your brand colors] and [your font or "a clean sans-serif"].

Read the data before planning the video. Identify three supported findings that answer the question. Do not fill missing cells with guesses. If you cannot read the Excel file, ask me to export the relevant sheet as CSV. Use saved values only if formulas cannot be recalculated, and flag that limitation.

Build this sequence:
- 0–5 seconds: title and reporting period.
- 5–17 seconds: finding one, with a simple chart and one takeaway.
- 17–29 seconds: finding two, with a comparison and clear labels.
- 29–41 seconds: finding three, with the relevant values and a conclusion supported by those values.
- 41–45 seconds: one-line summary and the logo, or [your brand name].

Choose chart types that fit the data. Keep scales and units clear, and use consistent colors for the same categories. Include all transitions in the 45-second total. Do not imply that a trend proves its cause.

No voiceover is needed. Save the source cells or rows and calculations for each finding in NOTES.md. Show me the findings and scene plan before building, then the preview. After my approval, run the project checks and export an MP4 video, not an interactive deck.
```

## Tips

- Keep private or irrelevant columns out of the file you attach.
- This prompt makes several findings into a story; prompt 02 makes one chart.
- Check its calculations before approving the preview.
