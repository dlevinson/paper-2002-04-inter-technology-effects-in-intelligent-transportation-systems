# Inter-Technology Effects in Intelligent Transportation Systems

This package stages the local data and model-output files found for:

Seshasai Kanchi, David M. Levinson, and David Gillen. (2002). "Inter-Technology Effects in Intelligent Transportation Systems." Transportation Research Record 1800:1-5. https://doi.org/10.3141/1800-01

## Package Status

Status: ready for public upload review.

The package contains the AIMSUN2 simulation scenario and output files found in the local TOPS source tree for the paper's freeway service patrol, changeable message sign, and ramp-metering experiments. It also contains the small legacy Excel result workbooks and LibreOffice `.xlsx` conversions for modern inspection.

The package does not contain paper drafts, correspondence, presentation/prose files, the AIMSUN software license file, executable utilities, or unrelated reference/admin folders from the source directory.

## Contents

- `paper/` contains a local reference copy of the final/published paper used to validate the package boundary.
- `data/aimsun2_scenarios/original/1lane/` contains the one-lane incident scenario/state/output corpus.
- `data/aimsun2_scenarios/original/2lane/` contains the two-lane incident scenario/state/output corpus.
- `data/result_workbooks/original/` contains legacy `.xls`, `.est`, and `.txt` result/MOE files from the source tree.
- `data/result_workbooks/modernized/` contains LibreOffice `.xlsx` conversions of the legacy result workbooks.
- `metadata/` contains inventories, workbook-sheet metadata, source-review notes, and duplicate-source comparison notes.
- `documentation/` contains the paper-first validation note and the source-boundary note.

## Source Boundary

Canonical local source reviewed:

`/Users/dlev2617/Documents/Data/~Nexus_Data/~PATH/PATH-TOPS/TOPS`

Near-duplicate source reviewed but not staged separately:

`/Users/dlev2617/Documents/Students/SeshKanchi/TOPS`

The duplicate source tree had the same substantive TOPS corpus except for an extra support DLL and minor top-level workbook metadata/size differences. The package stages the canonical `~PATH/PATH-TOPS/TOPS` version.

## Reproduction Notes

The paper states that the experiments used AIMSUN2, a microscopic traffic simulator. These files preserve the legacy AIMSUN2 scenario/state/output materials and workbooks, but the package does not include AIMSUN2 itself. Re-running the original simulations would require a compatible AIMSUN2 environment. The staged files are sufficient for archiving the local simulation corpus and inspecting the published experiment setup/output boundary.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 14:46:37 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
