# fMRI Experiment Files
The following repository contains files relevant to the fMRI analysis carried out by the *Cognition* group as part of the "Functional Neuroscience (C-track)" course.
It includes the following content:

- **onset_duration_files** - this directory contains the *.txt* onset-duration files for every subject (subject-3037, subject-3038, subject-3039) for every condition (baseline, memorable_repeat, memorable_non_repeat, non_memorable_repeat, non_memorable_non_repeat)
- **subject_logs** - this directory contains the *.csv* log files generated by *OpenSesame* during the fMRI experiment
- **fmri_experiment_final.osexp** - the experiment implementation in *OpenSesame*
- **onset_durations.m** - the *MATLAB* script used to create the onset-duration files from the subject logs (*.csv* files in the **subject_logs** directory).
- **searchfiles.m** - a supplementary *MATLAB* function used in **onset_durations.m** 
