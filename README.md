# language-guided-robot

## DATASET
### SIMPLE_INS
[https://drive.google.com/file/d/1FjtO0em3iYpZYoxniVp0O6GjJqgWllWL/view?usp=drive_link](https://drive.google.com/file/d/1FjtO0em3iYpZYoxniVp0O6GjJqgWllWL/view?usp=drive_link)

### MIXED_INS
[https://drive.google.com/file/d/1arJhWOOYmGlMPQ87B_bSo2hRy9ZS0SPD/view?usp=drive_link](https://drive.google.com/file/d/1arJhWOOYmGlMPQ87B_bSo2hRy9ZS0SPD/view?usp=drive_link)

### MIXED_INS_S
[https://drive.google.com/file/d/1qGavexpMvB0JVZSkTzL2OXYEdLtJ166t/view?usp=drive_link](https://drive.google.com/file/d/1qGavexpMvB0JVZSkTzL2OXYEdLtJ166t/view?usp=drive_link)

`<path_to_dataset>` for dataset directory. Note that after unzipping the download, this directory should have the following files
        
        <path_to_dataset>
		└── instructions-*.json
		└── scenes-*.json
		└── train
		└── test
		└── val
		└── vocab.json

## Main Result
### SIMPLE_INS
| Method   | Overall |One_step |Two_step | Link  |
|---------|-----------|-----------|-----------|-------|
| IoU_F | 0.79 | 0.84 | 0.68 | [point](https://drive.google.com/file/d/1JirNe2phLsDbStr9RzT6ntcAwMagLr8g/view?usp=drive_link)|
| GIoU_F | 0.82 | 0.84 | 0.69 | [point](https://drive.google.com/file/d/1C1r1EF17KFN6sfhr0Dqy3usO2G4Iz9Jd/view?usp=drive_link) |
| DIoU_F | 0.80 | 0.86 | 0.68 | [point](https://drive.google.com/file/d/14KW9IvdVEqWerFLTHjEHgaE1e-vLBOvm/view?usp=drive_link)|
| CIoU_F | 0.72 | 0.80 | 0.56 | [point](https://drive.google.com/file/d/16XHdtmpVx8sD8oUANb68YySRGMVO8bIl/view?usp=drive_link)|
| DAIoU_F | 0.87 | 0.90 | 0.80 | [point](https://drive.google.com/file/d/18nsXllg4RsMKoC2lylYJO_tuY4VWycq0/view?usp=drive_link)|


### MIXED_INS
| Method   | Overall |One_step |Two_step | Link  |
|---------|-----------|-----------|-----------|-------|
| IoU_F | 0.60 | 0.68 | 0.53 | [point](https://drive.google.com/file/d/1u1oB8AlGVT4d4k52Pomomk-XyJ0JGh84/view?usp=drive_link)|
| GIoU_F | 0.52 | 0.64 | 0.44 | [point](https://drive.google.com/file/d/1CYSF_bChrjBailf-dMm9JtT5GgeDjAY6/view?usp=drive_link) |
| DIoU_F | 0.56 | 0.66 | 0.48 | [point](https://drive.google.com/file/d/1DvrttAmmZFLAT0EuIpiKoD62_RQynD4O/view?usp=drive_link)|
| CIoU_F | 0.55 | 0.65 | 0.48 | [point](https://drive.google.com/file/d/1S1k2LttJ5ZAHZ6RmD2NPRF952MMJhawy/view?usp=drive_link)|
| DAIoU_F | 0.73 | 0.83 | 0.65 | [point](https://drive.google.com/file/d/1iEflymBfpLwnlPoVU0uYJYg2ztk3Km8Y/view?usp=drive_link)|

### MIXED_INS_S
| Method   | Overall |One_step |Two_step | Link  |
|---------|-----------|-----------|-----------|-------|
| IoU_F | 0.59 | 0.68 | 0.52 | [point](https://drive.google.com/file/d/1R_8T48PfIFT9IXj0YzY64lRwRDX5T_wI/view?usp=drive_link)|
| GIoU_F | 0.54 | 0.63 | 0.47 | [point](https://drive.google.com/file/d/1MVhy5fB1yWgXrL5yi9O332YdIQcvr10g/view?usp=drive_link) |
| DIoU_F | 0.57 | 0.66 | 0.49 | [point](https://drive.google.com/file/d/1B9FqpaTmAYIufKInPRIGTXeCFvuRS33a/view?usp=drive_link)|
| CIoU_F | 0.57 | 0.64 | 0.49 | [point](https://drive.google.com/file/d/15us-9VW8f_axhZAnI7PUSzvB1UU5qtbf/view?usp=drive_link)|
| DAIoU_F | 0.61 | 0.73 | 0.50 | [point](https://drive.google.com/file/d/1L0s1PGrcxR2iVNcwstBYsHCg2XJqgwLQ/view?usp=drive_link)|

## Test Model

[Learning Neuro-symbolic Programs for Language Guided Robot Manipulation](https://nsrmp.github.io/)





