# Source Boundary

Validated on: 2026-05-16

## Included

The package stages the data/code-adjacent materials required to preserve the local simulation corpus for the paper:

- AIMSUN2 one-lane scenario/state/output files from `1lane/`.
- AIMSUN2 two-lane scenario/state/output files from `2lane/`.
- Legacy Excel result workbooks from the source root.
- Modern `.xlsx` conversions of those workbooks.
- AIMSUN2 text/statistics output files from the source root.

## Excluded

The following source-tree materials were reviewed and intentionally excluded:

- Draft paper/prose files and presentation-style materials.
- Reference/admin folders.
- The AIMSUN software license file.
- Executable utility files without source review.
- Duplicate TOPS copies from the student folder.

## Duplicate Source Check

The folder `/Users/dlev2617/Documents/Students/SeshKanchi/TOPS` was compared against `/Users/dlev2617/Documents/Data/~Nexus_Data/~PATH/PATH-TOPS/TOPS`. It is a near-duplicate, with one extra support DLL and minor differences in two top-level result workbooks. The staged package uses the `~PATH/PATH-TOPS/TOPS` source as canonical.

See `metadata/SOURCE_CORPUS_COMPARISON.csv` for the comparison details.
