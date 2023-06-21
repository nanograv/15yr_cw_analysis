# CW analysis of the NANOGrav 15-year dataset

The notebooks in this repository show how the analysis was done in the paper "The NANOGrav 15-year Data Set: Bayesian Limits on Gravitational Waves from Individual Supermassive Black Hole Binaries". It also provides instruction on how one could reproduce those results on their own.

The following notebooks are available:

- [running_quickcw.ipynb](https://github.com/bencebecsy/15yr_cw_analysis/blob/main/running_quickcw.ipynb): This notebook provides instructrions on how to install and run the required software (QuickCW) to reproduce our results.
- [detection_analysis.ipynb](https://github.com/bencebecsy/15yr_cw_analysis/blob/main/detection_analysis.ipynb): This notebook performs a detection analysis (calculating Bayes factors) based on either the posterior samples obtained from running running_quickcw.ipynb or from the provided samples based on longer, better sampled runs.
- [UL_analysis.ipynb](https://github.com/bencebecsy/15yr_cw_analysis/blob/main/UL_analysis.ipynb): This notebook calculates upper limits on the GW amplitude from individual binaries based either on samples from running running_quickcw.ipynb or from the provided samples based on longer, better sampled runs.
- [distance_limit_freq_sky.ipynb](https://github.com/bencebecsy/15yr_cw_analysis/blob/main/distance_limit_freq_sky.ipynb): This notebook serves as a supplemental material to the NANOGRav 15yr individual binary paper, where one can get the derived limits on the luminosity distance of binaries given their sky location, GW frequency, and chirp mass.
