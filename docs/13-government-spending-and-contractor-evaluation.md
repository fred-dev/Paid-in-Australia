# Government Spending and Contractor Evaluation

## Status

MVP research workstream.

## Purpose

This document defines the research needed to support claims about public spending, major contractors, profits, tax paid, ownership, and value leakage. It should prevent the project from making broad claims before the evidence has been assembled.

The goal is to build an informed evaluation across local, state, territory, and federal spending.

## Core research questions

1. How much government procurement spending occurs at Commonwealth, state, territory, and local levels?
2. Which sectors receive the largest public contracts?
3. Which suppliers receive the largest contract values and highest numbers of contracts?
4. Which suppliers are Australian owned, foreign owned, superannuation owned, private equity owned, publicly listed, privately held, mutual, cooperative, or not-for-profit?
5. How much profit do major suppliers report?
6. How much Australian corporate tax do they pay?
7. How much of their Australian revenue comes from public contracts?
8. How much public contract value appears to flow to wages, subcontractors, dividends, related parties, offshore entities, debt servicing, executive remuneration, or retained earnings?
9. Which contracts could plausibly be delivered by Public-Benefit Suppliers?
10. Which sectors are suitable for early adoption, and which require longer-term reform?

## Commonwealth procurement baseline

The Department of Finance publishes annual statistics on Australian Government procurement contracts. These figures report contract values on AusTender and should not be treated as identical to annual cash expenditure, because contract values can span multiple years and include maximum values.

Initial source notes:

- Department of Finance, Statistics on Australian Government Procurement Contracts: https://www.finance.gov.au/government/procurement/statistics-australian-government-procurement-contracts-
- AusTender contract notices: https://www.tenders.gov.au/cn/search
- AusTender reports: https://www.tenders.gov.au/reports/list
- ANAO, Australian Government Procurement Contract Reporting 2022 update: https://www.anao.gov.au/work/information/australian-government-procurement-contract-reporting-2022-update

Initial facts to verify and track:

- 2024-25 Commonwealth AusTender contract value was reported by Finance as $104.9 billion.
- 2024-25 contract value was heavily concentrated in large contracts, with newly reported contracts over $20 million representing 60.5 percent of new contract value.
- Finance reports that 2024-25 services contracts represented 74.3 percent of total reported Commonwealth contract value.
- Finance also reports that 88.3 percent of 2024-25 contract value was awarded to suppliers with an Australian address. This is not the same as Australian beneficial ownership.

## State and territory spending

Each state and territory uses different procurement portals, reporting formats, annual reports, and disclosure thresholds. The project should build a jurisdiction-by-jurisdiction data map rather than assuming comparability.

Initial source notes:

- NSW procurement and annual reporting portals
- Victoria goods and services annual reports: https://www.buyingfor.vic.gov.au/annual-reports
- Queensland procurement data and open data portals
- South Australia, Western Australia, Tasmania, ACT, and Northern Territory procurement portals

Required fields:

- jurisdiction
- source portal
- financial year
- reporting threshold
- contract value basis
- whether contract value is annual or whole-of-life
- supplier name
- ABN or ACN
- category
- agency
- start date
- end date
- amendments
- procurement method
- panel use
- local content or social procurement flags

## Local government spending

Local government is especially relevant for waste removal, facilities, maintenance, local roads, parks, cleaning, fleet, and community services. However, council-level data may be fragmented and inconsistent.

Initial source notes:

- council annual reports
- local government procurement bodies
- state audit office reports
- tender portals
- waste contract registers where available

Research should distinguish whole-of-life contract values from annual expenditure. Waste contracts may run for many years, so a single contract notice can overstate annual spend if not annualised.

## Major contractor identification

The project should create a repeatable method for identifying major contractors rather than manually selecting politically visible firms.

Suggested method:

1. Download or query contract notice data for a financial year.
2. Normalise supplier names and ABNs.
3. Aggregate by supplier, category, agency, jurisdiction, and financial year.
4. Separate whole-of-life value from estimated annualised value.
5. Identify top suppliers by value, number of contracts, amendments, direct approaches, and panel use.
6. Link each supplier to ASIC, ABR, annual reports, ultimate parent entities, ownership type, and ATO tax transparency data where available.
7. Flag suppliers with high public revenue exposure, low tax payable, high related-party payments, offshore ownership, private equity ownership, or high subcontracting exposure.

## Profit and tax evaluation

Profit and tax evaluation should use primary sources wherever possible.

Primary sources:

- company annual reports
- ASIC filings where available
- ATO Corporate Tax Transparency Report
- data.gov.au corporate tax transparency data
- ASX announcements for listed entities
- parent company annual reports
- modern slavery statements where they reveal supply chains
- procurement disclosures and senate estimates answers

The ATO Corporate Tax Transparency Report publishes information for large corporate entities. It is useful, but it does not by itself prove tax avoidance. Entities may report no tax payable for different reasons, including losses, offsets, timing differences, or group structures. The project should treat low or zero tax as a flag for further analysis, not as proof of wrongdoing.

Initial source notes:

- ATO Corporate Tax Transparency Report 2023-24: https://www.ato.gov.au/businesses-and-organisations/corporate-tax-measures-and-assurance/large-business/in-detail/tax-transparency/corporate-tax-transparency-report-2023-24
- ATO corporate tax transparency reports: https://www.ato.gov.au/businesses-and-organisations/corporate-tax-measures-and-assurance/large-business/corporate-tax-transparency/our-corporate-tax-transparency-reports
- data.gov.au corporate tax transparency dataset: https://data.gov.au/data/dataset/corporate-transparency

## Evaluation outputs

The research should eventually produce:

1. a Commonwealth procurement baseline table
2. state and territory procurement baseline tables
3. local government sample tables
4. sector spend maps
5. top contractor lists
6. top contractor ownership profiles
7. contractor profit and tax summaries
8. sector leakage estimates
9. candidate sectors for early Public-Benefit Supplier adoption
10. candidate sectors for later-stage reform

## Guardrails

Do not claim that all for-profit suppliers are inefficient.

Do not claim that no-tax outcomes prove wrongdoing without evidence.

Do not conflate Australian address with Australian beneficial ownership.

Do not conflate not-for-profit status, charity status, mutual ownership, cooperative ownership, and Public-Benefit Supplier status.

Do not use one sector example as proof for all sectors.

Do not move consulting into early adoption until the data and legal pathways are stronger.
