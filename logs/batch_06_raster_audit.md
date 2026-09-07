# Batch 06 Production Raster Audit

## Summary

- Batch ID: `batch_06`
- Local directory: `data/raw/full/batch_06/`
- Audit command: `.\\.venv\\Scripts\\python.exe src/data/audit_raster.py <raster> --expected-width 5000 --expected-height 5000 --fail-on-all-nodata`
- Audit mode: read-only
- Expected files: 5
- Found files: 5
- Missing files: none
- Unexpected files: none
- Duplicate filenames: none
- Empty files: none
- Automated raster audit: PASS, 5/5
- Pixel accounting: PASS, every raster totals 25,000,000 label pixels
- Manifest lifecycle update: batch_06 rows promoted from `EXPECTED_PENDING` to `AUDITED_PASS`
- SHA-256: PASS, 5/5 captured
- Local storage >3 GiB: PASS
- Human QGIS production spot-check: PASS, exactly 2 production tiles
- Batch_06 Gate 4: PASS

Batch_06 Gate 4 is closed for this batch only. This does not authorize any next
production batch.

## Raster Results

### SULSEL_R006_C005

- Filename: `SULSEL_2021_SULSEL_R006_C005_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000 x 5000
- Total pixels: 25,000,000
- CRS: EPSG:3857
- Pixel size: 10 m x 10 m
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 25,000,000
- NoData pixels: 0
- Invalid label pixels: 0
- Coverage: 100.000000%
- Unique labels: 0,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 17742320
  - 2: 2019350
  - 3: 4584685
  - 4: 493744
  - 5: 12685
  - 7: 98207
  - 8: 10457
  - 9: 38552
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R006_C006

- Filename: `SULSEL_2021_SULSEL_R006_C006_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000 x 5000
- Total pixels: 25,000,000
- CRS: EPSG:3857
- Pixel size: 10 m x 10 m
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 2,556,222
- NoData pixels: 22,443,778
- Invalid label pixels: 0
- Coverage: 10.224888%
- Unique labels: 0,1,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 731316
  - 1: 337
  - 2: 120159
  - 3: 1033465
  - 4: 69884
  - 5: 5558
  - 7: 492318
  - 8: 51535
  - 9: 51650
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R007_C004

- Filename: `SULSEL_2021_SULSEL_R007_C004_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000 x 5000
- Total pixels: 25,000,000
- CRS: EPSG:3857
- Pixel size: 10 m x 10 m
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 16,166,961
- NoData pixels: 8,833,039
- Invalid label pixels: 0
- Coverage: 64.667844%
- Unique labels: 0,1,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 10253722
  - 1: 566
  - 2: 1392927
  - 3: 2803764
  - 4: 440746
  - 5: 18805
  - 7: 1066195
  - 8: 179259
  - 9: 10977
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R007_C005

- Filename: `SULSEL_2021_SULSEL_R007_C005_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000 x 5000
- Total pixels: 25,000,000
- CRS: EPSG:3857
- Pixel size: 10 m x 10 m
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 24,879,879
- NoData pixels: 120,121
- Invalid label pixels: 0
- Coverage: 99.519516%
- Unique labels: 0,1,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 7037861
  - 1: 27090
  - 2: 1854783
  - 3: 11170375
  - 4: 569941
  - 5: 15707
  - 7: 2296286
  - 8: 1874373
  - 9: 33463
- All-NoData: false
- Warnings: none
- Failures: none

### SULSEL_R007_C006

- Filename: `SULSEL_2021_SULSEL_R007_C006_S2WC_V1.tif`
- Audit status: PASS
- Dimensions: 5000 x 5000
- Total pixels: 25,000,000
- CRS: EPSG:3857
- Pixel size: 10 m x 10 m
- Band order: B2,B3,B4,B8,label
- Dtype: float32
- NoData: -9999
- Valid pixels: 790,663
- NoData pixels: 24,209,337
- Invalid label pixels: 0
- Coverage: 3.162652%
- Unique labels: 0,1,2,3,4,5,7,8,9
- class_pixel_counts:
  - 0: 33507
  - 1: 86
  - 2: 22362
  - 3: 240913
  - 4: 7433
  - 5: 2704
  - 7: 353810
  - 8: 26373
  - 9: 103475
- All-NoData: false
- Warnings: none
- Failures: none

## Gate-4 Closure Items

- SHA-256: PASS
- Local storage >3 GiB: PASS
- Human QGIS production spot-check: PASS, exactly 2 production tiles
- Final Gate-4 status: PASS for batch_06 only

## SHA-256 Checksums

- `SULSEL_2021_SULSEL_R006_C005_S2WC_V1.tif`: `B6F3387742FC82AC5B86FF8628EB35466B7AD1C4A577D9740C6546BE7C4DFBC3`
- `SULSEL_2021_SULSEL_R006_C006_S2WC_V1.tif`: `99DD5C01A1843A80D8B0398B5DCA517A6A81E7943206F5DE318A46BD387F7073`
- `SULSEL_2021_SULSEL_R007_C004_S2WC_V1.tif`: `9105F79B98B0C0FD7892ECC1AD2C5021EB593277CDE6CE2625040F461157AB9B`
- `SULSEL_2021_SULSEL_R007_C005_S2WC_V1.tif`: `FC4AA64415B3D5B10F6FDAE4F91E03CD6B61908E1DAC69CB0EC4EB66F3482131`
- `SULSEL_2021_SULSEL_R007_C006_S2WC_V1.tif`: `33AE7C4F613E5F7128E350D5FF5013DB7FE4B11676B811ABF9D698E15C82AB6D`

## Local Storage Audit

- Drive checked: `H:`
- Free bytes: 17,848,147,968
- Free GiB: 16.622383
- Gate-4 buffer requirement: >3.0 GiB
- Gate-4 storage status: PASS

PowerShell `Get-PSDrive H` returned `0` free bytes in this shell session, so the
recorded value uses .NET `System.IO.DriveInfo`, which reported drive `H:\` as
ready and fixed.

## QGIS Production Spot-Check

- Evidence directory checked: `docs/evidence/batch06_qgis_spotcheck/`
- Evidence already exists: YES
- Evidence files found:
  - `batch06_qgis_r006_c005_01_label_unique_values.png`
  - `batch06_qgis_r006_c005_02_rgb_label_alignment.png`
  - `batch06_qgis_r007_c006_01_label_unique_values.png`
  - `batch06_qgis_r007_c006_02_rgb_label_alignment.png`
- Status: PASS

Human QGIS spot-check results:

1. `SULSEL_R007_C006`
   - Visual status: PASS
   - Band 5 observed values: 0,1,2,3,4,5,7,8,9
   - RGB bands: B4/B3/B2
   - RGB-label alignment: PASS
   - Systematic offset: NO
   - Rotation: NO
   - Flip: NO
   - Low coverage expected: YES
   - Valid pixels: 790,663
   - NoData pixels: 24,209,337
   - Coverage: 3.162652%
   - Labels: 0,1,2,3,4,5,7,8,9
   - All-NoData: false
2. `SULSEL_R006_C005`
   - Visual status: PASS
   - Band 5 observed values: 0,2,3,4,5,7,8,9
   - RGB bands: B4/B3/B2
   - RGB-label alignment: PASS
   - Systematic offset: NO
   - Rotation: NO
   - Flip: NO
   - Full coverage expected: YES
   - Valid pixels: 25,000,000
   - NoData pixels: 0
   - Coverage: 100.000000%
   - Labels: 0,2,3,4,5,7,8,9
   - All-NoData: false
