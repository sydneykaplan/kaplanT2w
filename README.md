# kaplanT2w

This software uses ANTs and FSL to generate a pseudo-T2w image from a T1w image in neonatal MRI.

The currrent paper is at https://doi.org/10.1016/j.neuroimage.2022.119091

# Software Requirements
* ANTs
  * Install from: http://stnava.github.io/ANTs/
* FSL
  * Install from: https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation

# Set up
All image files are expected to be in nifti format.

## Configuration File ##
TBD

## Atlases ##
High-quality T1w and T2w images that have been co-registered within an individual atlas participant. Recommended at least 10 individual atlas participants per age bin. Age bins are organized by gestational age in weeks. The number of bins as well as ages contained in a bin are optional. Age bins must be organized in the following structure:

<!-- AUTO-GENERATED-CONTENT:START (DIRTREE:dir=./&depth=1) -->
```
atl_dir/
├── minage1_maxage1/
    ├── PATIENT01_T1w.nii.gz
    ├── PATIENT01_T1w_brain.nii.gz
    ├── PATIENT01_T2w.nii.gz
    ├── PATIENT01_T2w_brain.nii.gz
    ├── PATIENT02_T1w.nii.gz
    ├── PATIENT02_T1w_brain.nii.gz
    ├── PATIENT02_T2w.nii.gz
    └── PATIENT02_T2w_brain.nii.gz
├── minage2_maxage2/
    ├── PATIENT03_T1w.nii.gz
    ├── PATIENT03_T1w_brain.nii.gz
    ├── PATIENT03_T2w.nii.gz
    ├── PATIENT03_T2w_brain.nii.gz
    ├── PATIENT04_T1w.nii.gz
    ├── PATIENT04_T1w_brain.nii.gz
    ├── PATIENT04_T2w.nii.gz
    └── PATIENT04_T2w_brain.nii.gz
└── minage3_maxage3/
    ├── PATIENT05_T1w.nii.gz
    ├── PATIENT05_T1w_brain.nii.gz
    ├── PATIENT05_T2w.nii.gz
    ├── PATIENT05_T2w_brain.nii.gz
    ├── PATIENT06_T1w.nii.gz
    ├── PATIENT06_T1w_brain.nii.gz
    ├── PATIENT06_T2w.nii.gz
    └── PATIENT06_T2w_brain.nii.gz
```
<!-- AUTO-GENERATED-CONTENT:END -->

## Running ##
TBD

### Processing directives and options ###
TBD
