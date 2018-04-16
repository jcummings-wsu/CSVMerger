## Description

CSVMerger is an application to merge CSV files. It takes two (currently, variable number planned) CSV files and outputs a single CSV with all columns merged and any duplicate columns will be filled with either the highest priority (leftmost), or first non-null value.

## Instructions

Currently CSVMerger supports only two input files, but support for a dynamic number is planned.

After launching CSVMerger you will see 3 main panes and a footer. The left two are for loading input CSV's and the right for the output CSV.
Click "Browse" and choose a file for each input pane.
Check the box next to the header you wish to treat as the unique identifier for entries in that file.
You can then re-arrange the order of the columns in the output "Merged" pane as desired.

Check any options you wish to configure:
Currently only a "Remove Duplicates" is available. This will make sure that each identifier is unique and remove any duplicates.

Click "Merge." A prompt for where to save the file will appear.
Type a file name and save the file.
Your CSV's should now be merged!