# Clinical Data Projects — Bongani Mthethwa

Final-year BSc Genetics and Physiology student (University of the Free State), building practical
skills in clinical systems, data reporting, and relational databases ahead of a career in clinical
research and clinical systems support.

**Note:** All data in both projects is 100% fictional — no real patient, hospital, or personal
information is used anywhere. Everything was built as self-directed practice, inspired by a job
shadowing placement in the Department of Nuclear Medicine at Universitas Academic Hospital.

---

## 1. Nuclear Medicine Scan Register & Dashboard (`Scan_Register_Sample_Project.xlsx`)

A mock clinical scan-tracking workbook demonstrating ad-hoc query and reporting skills.

- **Scan Register** — a raw data table styled like an export from a clinical system (e.g. InnTrax),
  covering the scan types I observed while shadowing: bone, lung perfusion, myocardial perfusion,
  thyroid, and prostate scans.
- **Summary** — fully formula-driven reporting (`COUNTIFS`, `SUMIFS`, `AVERAGEIFS`) summarising
  volume by scan type, status, turnaround time, and referring physician. Nothing is hardcoded —
  add a row to the register and every total updates automatically.
- **Dashboard** — charts built directly from the Summary formulas.

## 2. Relational Scan Database (`Relational_Scan_Database_Sample_Project.xlsx`)

A normalized, Access-ready relational database built around the same scenario.

- Four linked tables — **Physicians**, **ScanTypes**, **Patients**, and **Scans** — each with a
  primary key, with `Scans` referencing the other three via foreign keys.
- A **Scan Details (Query View)** sheet uses `INDEX`/`MATCH` to join all four tables, simulating a
  SQL `JOIN`.
- A **Query Examples** sheet shows ad-hoc reporting built on top of the joined view.
- Structured so each sheet can be imported directly into **MS Access** as its own table, with
  relationships and queries then built natively in Access.

---

### What these projects show
- Comfort structuring and querying clinical-style data
- Understanding of relational database design: primary keys, foreign keys, normalization
- Formula-based reporting that updates live rather than static, one-off numbers
- Ability to translate a real clinical environment (Nuclear Medicine) into a data model

*Built independently as practice projects — feedback welcome.*
