# apaper_apqc_etal
These scripts were used to process the dataset used to demo quality
control (QC) tools in AFNI (Taylor et al., 2024).

For more details, please see:

  A Set of FMRI Quality Control Tools in AFNI: 
  Systematic, in-depth and interactive QC with afni_proc.py and more

  by Paul A. Taylor, Daniel R. Glen, Gang Chen, Robert W. Cox, Taylor
  Hanayik, Chris Rorden, Dylan M. Nielson, Justin K. Rajendra,
  Richard C. Reynolds.

-----------------------------------------------------------------------

The primary processing is contained in the scripts/ directory:

  do_13_ssw.tcsh  : run sswarper2 to perform skullstripping (ss) and
                    nonlinear alignment (warping) to a template

  do_20_ap.tcsh   : run afni_proc.py to perform full single subject
                    processing on task-based FMRI data

-----------------------------------------------------------------------

The dataset accompanying these scripts and the reference draft is
located for public download here: https://osf.io/un56d/ .

This dataset is actually the same subject used in the standard AFNI
Bootcamp courses (AFNI_data6/FT_analysis/FT).