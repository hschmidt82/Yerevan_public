# Yerevan_public

Contains the processed structural data from the Yerevan study (language training in native speakers), and the MATLAB code to analyse them.


Scripts utilise the circulargraph function as found on https://www.mathworks.com/matlabcentral/fileexchange/48576-circulargraph. See https://github.com/paul-kassebaum-mathworks/circularGraph for documentation and licensing details.


This package contains the structural data in the following folders:

'ordered_matrices/' - data for left hemisphere

'probtrackX_rh/'    - data for right hemisphere


The following m-files recreate parts (b) and (c) of Figures 2-4 of the manuscript that soon to be published (updates will follow shortly). NB: Part (a) of Figures 2-4 are created with external software for visualisation purposes only, and do not contain any critical information for the reproduction of this study.


List of scripts to execute:

Yerevan_SVD_baseline.m        - recreates results shown in Figure 2

Yerevan_SVD_training.m        - recreates results shown in Figure 3

Yerevan_SVD_baseline_right.m  - recreates results shown in Figure 4
