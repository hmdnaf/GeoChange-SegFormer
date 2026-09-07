# Batch 07 Raster Audit

## Scope

- Task: M6 Batch 07 Local Raster Audit
- Batch: batch_07
- Local directory: `data/raw/full/batch_07/`
- Audit command: `.\.venv\Scripts\python.exe src/data/audit_raster.py <raster> --expected-width 5000 --expected-height 5000 --fail-on-all-nodata`
- Production raster contract: 5000x5000, EPSG:3857, 10 m pixels, 5 bands B2/B3/B4/B8/label, float32, NoData -9999
- Low coverage policy: allowed when valid pixels are greater than zero and all raster-contract checks pass
- Gate 4 status: PENDING_HUMAN_QGIS_SPOT_CHECK; SHA-256 and current local storage checks are complete, but human QGIS production spot-check is still required

## File Reconciliation

- Expected files: 5
- Found files: 5
- Missing files: none
- Unexpected files: none
- Duplicate filenames: none
- Zero-byte files: none

Expected files:

- `SULSEL_2021_SULSEL_R008_C003_S2WC_V1.tif`
- `SULSEL_2021_SULSEL_R008_C004_S2WC_V1.tif`
- `SULSEL_2021_SULSEL_R008_C005_S2WC_V1.tif`
- `SULSEL_2021_SULSEL_R008_C006_S2WC_V1.tif`
- `SULSEL_2021_SULSEL_R009_C003_S2WC_V1.tif`

## Raster Results

### SULSEL_R008_C003

- Filename: `SULSEL_2021_SULSEL_R008_C003_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000x5000
- Total pixels: 25000000
- CRS: EPSG:3857
- Pixel size: 10 m
- Transform: `(10.0, 0.0, 13246793.831951, 0.0, -10.0, -386593.62424300006)`
- Bounds: `(13246793.831951, -436593.62424300006, 13296793.831951, -386593.62424300006)`
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 1196
- NoData pixels: 24998804
- Invalid label pixels: 0
- Coverage: 0.004784%
- Unique labels: 7
- class_pixel_counts:
  - 7: 1196
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R008_C004

- Filename: `SULSEL_2021_SULSEL_R008_C004_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000x5000
- Total pixels: 25000000
- CRS: EPSG:3857
- Pixel size: 10 m
- Transform: `(10.0, 0.0, 13296793.831951, 0.0, -10.0, -386593.62424300006)`
- Bounds: `(13296793.831951, -436593.62424300006, 13346793.831951, -386593.62424300006)`
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 22567575
- NoData pixels: 2432425
- Invalid label pixels: 0
- Coverage: 90.270300%
- Unique labels: 0,1,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 11353302
  - 1: 3468
  - 2: 1510897
  - 3: 7731778
  - 4: 627088
  - 5: 37257
  - 7: 988399
  - 8: 314277
  - 9: 1109
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R008_C005

- Filename: `SULSEL_2021_SULSEL_R008_C005_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000x5000
- Total pixels: 25000000
- CRS: EPSG:3857
- Pixel size: 10 m
- Transform: `(10.0, 0.0, 13346793.831951, 0.0, -10.0, -386593.62424300006)`
- Bounds: `(13346793.831951, -436593.62424300006, 13396793.831951, -386593.62424300006)`
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 24989533
- NoData pixels: 10467
- Invalid label pixels: 0
- Coverage: 99.958132%
- Unique labels: 0,1,2,3,4,5,7,8
- class_pixel_counts:
  - 0: 19685409
  - 1: 84
  - 2: 2207707
  - 3: 2710399
  - 4: 148628
  - 5: 18898
  - 7: 192573
  - 8: 25835
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R008_C006

- Filename: `SULSEL_2021_SULSEL_R008_C006_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000x5000
- Total pixels: 25000000
- CRS: EPSG:3857
- Pixel size: 10 m
- Transform: `(10.0, 0.0, 13396793.831951, 0.0, -10.0, -386593.62424300006)`
- Bounds: `(13396793.831951, -436593.62424300006, 13446793.831951, -386593.62424300006)`
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 2868572
- NoData pixels: 22131428
- Invalid label pixels: 0
- Coverage: 11.474288%
- Unique labels: 0,1,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 1508777
  - 1: 1143
  - 2: 48540
  - 3: 722462
  - 4: 64514
  - 5: 6941
  - 7: 434705
  - 8: 38219
  - 9: 43271
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R009_C003

- Filename: `SULSEL_2021_SULSEL_R009_C003_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000x5000
- Total pixels: 25000000
- CRS: EPSG:3857
- Pixel size: 10 m
- Transform: `(10.0, 0.0, 13246793.831951, 0.0, -10.0, -336593.62424300006)`
- Bounds: `(13246793.831951, -386593.62424300006, 13296793.831951, -336593.62424300006)`
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 636117
- NoData pixels: 24363883
- Invalid label pixels: 0
- Coverage: 2.544468%
- Unique labels: 0,2,3,4,5,7
- class_pixel_counts:
  - 0: 446970
  - 2: 182063
  - 3: 6434
  - 4: 354
  - 5: 249
  - 7: 47
- All-NoData: false
- Warnings: none
- Failures: none

## Pixel Accounting

- `SULSEL_R008_C003`: 1196 + 24998804 + 0 = 25000000
- `SULSEL_R008_C004`: 22567575 + 2432425 + 0 = 25000000
- `SULSEL_R008_C005`: 24989533 + 10467 + 0 = 25000000
- `SULSEL_R008_C006`: 2868572 + 22131428 + 0 = 25000000
- `SULSEL_R009_C003`: 636117 + 24363883 + 0 = 25000000

Every raster totals 25000000 pixels: YES

## SHA-256 Checksums

- `SULSEL_2021_SULSEL_R008_C003_S2WC_V1.tif`: F646E1D06496AA532710E12C9A1D77867F417003A91D6913B30AF2491CCCBBC2
- `SULSEL_2021_SULSEL_R008_C004_S2WC_V1.tif`: 6D816D44698E3C3B61348146E1425428B2B321B4BAD5D64D611148166961FD0F
- `SULSEL_2021_SULSEL_R008_C005_S2WC_V1.tif`: 9B36F9EFC975E688BC2694AB0163382D1AAD3C9C1F513C7681F78EBC9F86DD03
- `SULSEL_2021_SULSEL_R008_C006_S2WC_V1.tif`: 8E1E6D6F39AD7F46907AEA1A50F52D81052E11B059E49524F037241AA1DE4F06
- `SULSEL_2021_SULSEL_R009_C003_S2WC_V1.tif`: 88CC40B378EB8870C87BB36B2BE78D92B1FA15E923BEC9D962D1CAD31B60D101

## Local Storage Gate

- Drive: `H:\`
- Free bytes: 17470386176
- Free GiB: 16.270565
- Gate-4 buffer threshold: >3.0 GiB
- Gate-4 buffer status: PASS

## Human QGIS Production Spot-Check

- Evidence directory: `docs/evidence/batch07_qgis_spotcheck/`
- Evidence already exists: NO
- Status: PENDING_HUMAN_QGIS_SPOT_CHECK

Recommended human spot-check tiles:

1. `SULSEL_R008_C003`
   - Reason: extreme low coverage
   - Valid pixels: 1196
   - NoData pixels: 24998804
   - Coverage: 0.004784%
   - Labels: 7 only
   - Class 7 pixels: 1196
   - All-NoData: false

2. `SULSEL_R008_C005`
   - Reason: near-full coverage
   - Valid pixels: 24989533
   - NoData pixels: 10467
   - Coverage: 99.958132%
   - Labels: 0,1,2,3,4,5,7,8
   - All-NoData: false

## Manifest Bookkeeping

- Approved lifecycle update: EXPECTED_PENDING -> AUDITED_PASS
- Rows changed: 5
- Batch_07 statuses after update: AUDITED_PASS
- Manifest expected state after update: 40 AUDITED_PASS; 15 EXPECTED_PENDING; 0 AUDITED_FAIL; 0 QUARANTINED

## Current State

- M6: IN_PROGRESS
- Batch_07 automated local raster audit: PASS, 5/5
- Batch_07 Gate 4: PENDING
- Production automated-audit PASS: 40 of 55
- Production remaining: 15

## Safety

- Raster contents modified: NO
- Raster renamed, moved, or deleted: NO
- Google Earth Engine run: NO
- New production batch started: NO
- Patch extraction started: NO
