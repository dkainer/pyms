# pyms
GC-MS analysis library.
This project is based off the Automatically exported package from code.google.com/p/pyms

PyMS already does a pretty good job of processing GC-MS data. It currently finds peaks, deconvolutes peaks, integrates peaks and aligns peaks across multiple GC-MS runs. Howver it can be improved

# Goal
To improve the PyMS GC-MS library. In particular to make it easier to manually correct false alignments after running the PymS pipeline.

# Additional Functionality
1. detect outliers in RT aligments
2. remove outliers from Peak Average RT calculation
3. Remove outliers from Common Peak mass spec and common ions calculation
4. output top N ions (i.e. a mini mass spec) from each peak in the alignment in a separate CSV file.


