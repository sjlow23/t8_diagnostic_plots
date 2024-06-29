# T8 diagnostic plots

An R script to visually assess data generated by and exported from Axxin T8 in Excel format.

### Input
  - An Excel file(s) from multiple T8 runs
  - Multiple runs can be collated in one Excel file as separate sheets
  - The last sheet in the Excel file should list the sample ids present in each run
  - See "test_input.xlsx" for an example

### Output
  - A PDF file containing sample statistics and diagnostic plots for assessing run quality
  - Tab-delimited file with sample and readout in tabular format
  - Output files will be in a directory called "t8_assessment_output"
