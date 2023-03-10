# ContourAnalysis

Scripts for analysing melodic contour of monophonic audio file.

If you want to analyse the Essen dataset, start from step 0: the humdrum2audio code.
For all other audio files, or once you have created audio files for the Essen dataset,
Step 1: phrase_generator -- load audio file, trim leading and trailing silence, set phrase length to 10 seconds, and export phrase
Step 2: create_data_table -- load audio file, estimate pitch, normalise and transform to log scale, and save dataset
Step 3: PCA_cluster -- load dataset, perform PCA, permutation test, clustering analysis, and statistical analysis for cluster size
