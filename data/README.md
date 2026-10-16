# Data Guidance

## Approved Core Dataset

Use the **National Energy Efficiency Data-Framework (NEED) Anonymised Data 2026 — 50,000-row sample**.

Official source:
https://www.gov.uk/government/statistics/national-energy-efficiency-data-framework-need-anonymised-data-2026

## Why This Version Is Approved

The 50,000-row sample is large enough to support:
- profiling;
- segmentation;
- scenario analysis;
- BI;
- transparent prioritisation;
- model-governance work.

It is also manageable in:
- Excel;
- Google Sheets;
- Python;
- Power BI;
- SQL-based local workflows.

## What to Put in `data/raw/`

Store the original CSV unchanged:

```text
data/raw/
└── need-2026-50k.csv
```

Do not overwrite it with a cleaned version.

## Approved Scope

Use the **entire 50k sample** unless a documented technical reason requires a subset.

Do not take an arbitrary smaller sample merely to make the analysis easier.

## Analytical Grain

Preserve the source property/sample-unit grain.

Document:
- identifier strategy;
- consumption fields;
- property characteristics;
- efficiency-measure fields;
- missing/suppressed values.

## Spreadsheet Guidance

Excel/Google Sheets may be used for profiling and summary analysis.

However:
- the frozen 50k CSV remains the source of truth;
- any smaller summary sheet must be reproducibly derived;
- core transformations should be documented.

## Large Dataset Extension

The publisher also provides a much larger anonymised dataset.

That larger file is **optional** and should only be used after the 50k solution passes acceptance criteria.

If the large file exceeds normal GitHub limits:
- do not commit it;
- record official URL;
- filename;
- file size;
- checksum;
- acquisition date;
- retrieval instructions.

## Core Assessment Rule

Mettelo assessment should be reproducible from the frozen 50k dataset alone.
