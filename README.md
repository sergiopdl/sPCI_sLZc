# sPCI_sLZc
1. Create the following directories in the root of your Google Drive (replacing "Sample" with any desired name of your project):
* /Sample/Data/Inputs/Activations/
* /Sample/Data/Inputs/Events/
* /Sample/Data/Outputs/Timepoints/
* /Sample/Data/Outputs/Measures/
* /Sample/Data/Outputs/Measures/Filtered/
3. Put your 2x2 activation matrix .CSVs (channels x timepoints, 1 file per subject) in /Sample/Data/Inputs/Activations/.
4. Put your corresponding EventList .TXTs (1 per subject) in /Sample/Data/Inputs/Events/.
5. Run each code chunk from top to bottom (PCI code, Python imports, and helper functions) until you get to Main.
6. In the first code chunk in Main, configure the parameters accordingly.
7. Run the second code in chunk Main, which outputs one file for each subject with PCI and LZc in /Sample/Data/Outputs/Measures/Filtered/.
8. Run the last code chunk to aggregate the outputs across all subjects into one file for analysis in R.
