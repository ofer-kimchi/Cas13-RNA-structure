# Cas13-RNA-structure
Code to accompany "RNA structure modulates Cas13 activity and enables mismatch detection"

The python code "combined_analysis_for_upload.py" when run imports data from all other files and generates the figures in the paper. 

randwalk_results is a folder containing 28 numpy arrays, each of which gives the first passage times for 10^6 simulated random walks of 28 different lengths. These were used for certain model predictions, but none of these were ultimately used in the manuscript, for which we implemented a simplified but nevertheless accurate model.
