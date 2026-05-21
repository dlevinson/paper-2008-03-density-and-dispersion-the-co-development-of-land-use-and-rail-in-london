# Density And Dispersion: The Co-Development Of Land Use And Rail In London

This folder is a cleaned public-upload package for `paper-2008-03`.

## Citation

David M. Levinson. (2008). Density and dispersion: The co-development of land use and rail in London. Journal of Economic Geography, 8(1), 55-77. https://doi.org/10.1093/jeg/lbm038

## Paper Evidence

The inspected published PDF says the study uses panel data for 33 London boroughs over each decade from 1871 to 2001. The variables described in the paper include population density, employment/core classification, surface rail station density, Underground station density, distance/neighbor structure, and regional lag terms. The results section says the statistical models were estimated in Stata with `xtpcse`.

## Package Boundary

This package keeps the paper-facing research assets that correspond to those claims: borough panel workbooks, station/network workbooks, employment/land-use workbooks, and finalized London rail/spatial layers. No Stata `.do` file was found in the inspected London coevolution source folder, so the package does not claim to include an executable Stata reproduction script. The paper's model equations and reported `xtpcse` procedure are preserved in the paper reference.

## Contents

- `paper/`: local reference copy of the published PDF for audit convenience.
- `data/panel_and_model_workbooks/`: panel, density, station, distance, and model workbooks/CSV exports.
- `data/borough_analysis_workbooks/`: borough-level population/network analysis workbooks, including the expanded time-column variant renamed from the source file `London_analysis2 2.xls`.
- `data/network_workbooks/`: London Underground, surface rail, DLR, station, link, and source/extract workbooks.
- `data/employment_land_use_workbooks/`: employment, worker, and land-use workbooks used for core/periphery and land-use context.
- `data/gis/finalized_fixed_networks_feb_8_07/`: finalized London rail/spatial shapefile components.
- `documentation/`: source manifest, workbook sheet overview, GIS layer overview, and explicit exclusions.

## Exclusions

Non-archival project documents, proposals, reading notes, public source PDFs, RTF report extracts, unrelated Vienna material, scratch/backup workbooks, compressed duplicates, and map/movie outputs are excluded from the upload payload. See `documentation/EXCLUDED_NONARCHIVAL_FILES.csv`.

## Rights And Provenance

The package is staged for public repository review as an author research-data package with provenance notes. The underlying historical population, employment, rail-history, and land-use sources retain their original source terms; public/source PDFs are cited rather than copied into the package. Before external upload, set repository license text so it applies only to author-created documentation and derived research tables, not to third-party source publications.

Updated: 2026-05-17 12:31:00 AEST

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-21 20:04:48 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
