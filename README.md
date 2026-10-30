## About me

I build R packages for data engineering, financial planning and analysis, energy, and public data. Most of my work leverages `R` and `DuckDB` but I also use bash and lua.

I do all of my development on [codeberg](www.codeberg.org) but mirror the repos in github. Please direct all issues / pull requests to codeberg.

If you're interested in collaborating in projects please reach out!

## Packages on CRAN

These packages are stable and available on CRAN.

| Package | Description | CRAN |
| ------- | ----------- | ---- |
| [contoso](https://usrbinr.codeberg.page/contoso/)       | Synthetic sales, customer, store, and product tables from the fictional Contoso company, for practicing analysis and BI | ![CRAN](https://www.r-pkg.org/badges/version/contoso) |
| [motherduck](https://usrbinr.github.io/motherduck/)     | Utilities for administering and managing 'DuckDB' databases on the 'MotherDuck' cloud platform | ![CRAN](https://www.r-pkg.org/badges/version/motherduck) |
| [sqlm](https://usrbinr.codeberg.page/sqlm/)             | Fit statistical models (lm, glm, ridge, PCA, k-means, trees, and more) inside SQL databases without pulling data into R | ![CRAN](https://www.r-pkg.org/badges/version/sqlm) |

## Packages under development

These packages are not on CRAN yet.

- ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) packages should give correct results but may still need documentation polish or a CRAN submission.
- ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) packages work, but features are still being added.
- ![Static Badge](https://img.shields.io/badge/lifecycle-experimental-yellow) packages are under active development and their APIs may change.

| Package | Description | Lifecycle |
| ------- | ----------- | --------- |
| [ti](https://usrbinr.codeberg.page/ti/)                 | Time intelligence (YoY, MTD, QTD, YTD) and customer segmentation (ABC, cohorts) with retail calendar support, in memory or in database | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) |
| [qrtdown](https://usrbinr.codeberg.page/qrtdown/)       | Build R package documentation websites with Quarto instead of pkgdown | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) |
| [tidychain](https://usrbinr.codeberg.page/tidychain/)   | Excel forensics: parse `.xlsx` internals and `calcChain.xml` to decompose models and flag manipulation | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) |
| [flixpatrol](https://usrbinr.codeberg.page/flixpatrol/) | R client for the 'FlixPatrol' streaming rankings API | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) |
| [tsadata](https://usrbinr.codeberg.page/tsadata/)       | TSA passenger screening data, streamed from 'Cloudflare R2' into 'DuckDB' | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [stwd](https://usrbinr.codeberg.page/stwd/)             | Storytelling with Data layouts and highlighting for ggplot2, with a Shiny layout designer | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [kalshi](https://usrbinr.codeberg.page/kalshi/)         | R client for the Kalshi prediction market API | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [pvwatts](https://usrbinr.codeberg.page/pvwatts/)       | Client for NREL's 'PVWatts' v8 solar production API | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [icbs](https://usrbinr.codeberg.page/icbs/)             | IBCS-style business charts for ggplot2, including variance and waterfall charts | ![Static Badge](https://img.shields.io/badge/lifecycle-experimental-yellow) |
| [awh](https://usrbinr.codeberg.page/awh/)               | Workflow helpers: 'Cloudflare' R2 storage, database-aware counting, and input validation | ![Static Badge](https://img.shields.io/badge/lifecycle-experimental-yellow) |

## Coming soon

These are in progress and not public yet.

| Package | Description |
| ------- | ----------- |
| pudl         | Query the Public Utility Data Liberation ('PUDL') energy database from S3 via 'DuckDB', with plant economics and emissions analysis |
| solarfinance | FAST-methodology project finance model for solar power plants |
| rpsa         | Power system analysis in R (optimal power flow, capacity expansion), inspired by 'PyPSA' |
| htxdata      | One interface to City of Houston and Harris County open data portals |
| elections    | Texas county election data ETL: voter lists, results, and precinct summaries |
| pivot        | A language-agnostic pivot table viewer for 'VS Code', powered by 'DuckDB-WASM' |

## Other repos

| Repo | Description |
| ---- | ----------- |
| [1br](https://github.com/usrbinr/1br)             | The One Billion Row Challenge in R, benchmarking dplyr, data.table, collapse, 'DuckDB', 'Arrow', and 'Polars' |
| [learningR](https://github.com/usrbinr/learningR) | Notes and learnings on using R |
| [usrbinr](https://github.com/usrbinr/usrbinr)     | The README you are reading |
