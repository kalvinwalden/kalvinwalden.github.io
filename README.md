# Kalvin Walden — Data Analysis Portfolio

Live site: https://kalvinwalden.github.io

## Kansas City, MO 2026 Disparity Study

[Case study](https://kalvinwalden.github.io/kcmo-disparity-study/) of my statistical work on the
[Kansas City, MO 2026 Disparity Study](https://www.kcmo.gov/home/showpublisheddocument/16672/639143574123270000)
(Griffin & Strong, P.C., May 2026). I drafted its quantitative chapter (Chapter V, pp. 62–106) and wrote the
R and Python pipeline behind its tables.

The page includes:

- an interactive disparity index chart built from the report's Table 37
- a six-step primer on how a disparity study works, starting from *City of Richmond v. J.A. Croson Co.* (1989)
- a code walkthrough from import to report-ready Excel tables
- all 37 tables and figures from Chapter V, cropped from the public report

### Data note

The client's data is confidential and is not in this repository. Code outputs on the page are synthetic
unless they are marked as coming from the published report. Step 5 of the code walkthrough reproduces
Table 37's construction indices from the report's published shares.

Tables, figures and findings are from the public report. County boundaries are from the U.S. Census Bureau
(via us-atlas). This is a personal portfolio, not a publication of the City of Kansas City or Griffin & Strong.

### Structure

```
index.html                     redirects to the case study
kcmo-disparity-study/
  index.html                   the case study (single file, fonts embedded)
  og.png                       link preview image
  tables/                      37 exhibits from Chapter V
```
