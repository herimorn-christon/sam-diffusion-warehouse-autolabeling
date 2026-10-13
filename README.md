# Warehouse image classification — research evidence deposit candidate

**Status: NOT PUBLISHED. NOT A DOI-REGISTERED DEPOSIT.** Prepared 13 October 2026.

This repository candidate contains only curated supporting evidence for the associated manuscript and an appendix; no raw warehouse photographs, complete original image-level training/validation/test membership, model weights, independent pixelwise SAM reference masks, or reviewer identity records are included.

## Files
- `evidence/S01__dataset_partition_summary.json` summarizes the 3,816-record original partition; it is NOT the original full split manifest.
- `evidence/S02...S20...` are transformed source snapshots with absolute private/internal file locations replaced by `[INTERNAL_FILE_LOCATION_REDACTED]`.
- `evidence_index.json` lists each supporting source's transformation and SHA-256 checksum.
- `Warehouse_Q1_Supplement_V25_Repository_Evidence.docx` and corresponding PDF contain the scientific interpretation and S01–S20 indexing.
- `SHA256SUMS.txt` lists SHA-256 checksums of the package payload.

## IMPORTANT LIMITATIONS
- The package is neither a full reproducibility dataset nor proof of model training/checkpoint retrieval.
- Source datasets may contain third-party images. **DO NOT publish raw images or full manifests without checking ownership, licensing and privacy.**
- Diffusion screening and SAM human review outcomes must not be treated as human-adjudicated IoU/Dice, annotation speed-up, or demonstrated independent generalization.
- Archive candidate must be checked for author names, affiliations, metadata, third-party licensing and blind-review restrictions before release.

## DOI and repository status
No Zenodo upload was made. No DOI has been registered. Do not write a placeholder DOI as if genuine. Once the author approves the final public contents, deposit them under appropriate repository settings and replace the data-availability text in the manuscript with the actual DOI.

## Public and private separation
A separate private provenance package contains exact Google Drive file IDs, source URLs and unmodified archived source records. **That private package is not for public upload or journal supplementary submission.**
