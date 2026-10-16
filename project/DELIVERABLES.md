# Required Deliverables

## D1 — Discovery, Decision & Requirements Pack
**Due:** Week 1  
**Location:** `docs/01-discovery/`

Decision statement; stakeholder map; as-is/to-be process; at least 8 prioritised functional/user requirements; non-functional requirements; assumptions/dependencies; acceptance criteria mapped to requirements.

**Acceptance:** every planned feature/analysis maps to an approved requirement.

## D2 — Data Governance & Source Control Pack
**Due:** Week 2  
**Location:** `docs/02-data-governance/`, `data/SOURCE_REGISTER.md`

Source inventory/frozen version; glossary; critical data elements; owners/stewards; lineage; DQ rules; reuse notes; governance risks.

**Acceptance:** every headline KPI traces to governed source fields.

## D3 — Reproducible Ingestion & Analytical Model
**Due:** Week 3  
**Location:** `src/`, `sql/`, `docs/03-data-model/`

Load process; raw preservation; schema/type checks; standardisation; keys/grain; curated table(s); rerun instructions; exception handling.

**Acceptance:** same frozen input produces equivalent curated output on clean rerun.

## D4 — Data Quality, Reconciliation & Exceptions
**Due:** Week 3  
**Location:** `docs/04-data-quality/`, `tests/`

Row reconciliation; duplicate checks; missingness; accepted values/ranges; exception log; inclusion/exclusion rules.

**Acceptance:** material exclusions are quantified and explained.

## D5 — KPI & Metric Catalogue
**Due:** Week 4  
**Location:** `docs/05-kpi-catalogue/`

Minimum metrics:
- annual gas/electricity consumption where available;
- median/mean consumption by property segment;
- property segment count/share;
- efficiency-measure prevalence;
- high-consumption segment rate;
- consumption distribution percentile;
- prioritisation score components;
- score sensitivity under alternative weights;
- records with missing critical fields;
- segment coverage;

Each metric requires purpose, definition, formula, grain, source, exclusions, owner, refresh expectation and limitation.

## D6 — Core Analytical Assessment I
**Due:** Week 5  
**Location:** `analysis/`, `docs/06-analysis/`

- property-type and age-band consumption patterns;
- heating/fuel/property characteristic variation;
- efficiency-measure prevalence;
- high-consumption segment identification;

Each major finding must state comparison basis, materiality and limitation.

## D7 — Core Analytical Assessment II & Decision Framework
**Due:** Week 6  
**Location:** `docs/07-decision-framework/`

- transparent prioritisation factors;
- alternative weighting scenarios;
- fairness/proxy review;
- manual feasibility-review criteria;
- explicit factors/thresholds;
- rationale;
- at least one sensitivity test;
- manual-review triggers;
- evidence insufficient for action.

## D8 — BI / Decision-Support Product
**Due:** Draft Week 6; final Week 7  
**Location:** `dashboard/`

Executive view; diagnostic drill-down; governed measures; source/reporting period; definitions/quality notes; filters; accessibility/readability; reproducible build/access instructions.

**Acceptance:** at least five headline measures reconcile to curated data.

## D9 — Assurance & UAT
**Due:** Week 7  
**Location:** `docs/08-assurance-uat/`

Minimum 10 test scenarios; calculation/filter/edge-case checks; reconciliation; defect log; requirement-to-test traceability; UAT feedback; acceptance status.

## D10 — Technical & Operational Handover
**Due:** Week 8  
**Location:** `docs/09-technical-handover/`

Setup; run/refresh; architecture/data flow; transformations; metric logic; tests; troubleshooting; limitations; maintenance/change guidance.

## D11 — Executive Briefing & Presentation
**Due:** Week 8  
**Location:** `deliverables/`

Maximum two-page briefing plus 15–20 minute presentation covering decision, evidence, recommendation/investigation, limitations and next steps.

## D12 — Contribution & Delivery Evidence
**Due:** Final submission  
**Location:** `CONTRIBUTIONS.md`

Role, owned work packages, artefacts, linked issues/PRs/commits, review contribution and presentation contribution. Commit count alone is insufficient.
