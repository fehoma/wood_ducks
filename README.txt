This is a project about wood ducks.
Raw data contains one file per each observation.
Individual observations were combined in the tidy_data.xlsx file. The following tidying steps were taken:
1. Missing, unknown, empty, etc. were set to value "N/A"
2. Changed the variable names to include the units (we assume temperature was recorded in celsius)
3. Some unsure values ("probably 14" and "5?" total number of eggs for observations A1B and U10C) were set to the estimated value, and the variable name was changed to include "(estimated)"
4. Changed the mass values to gram units (because all values seemed to be around 500 grams)
5. Saved as a .csv with "," delimiter
