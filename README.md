# Students by State at The University of Illinois

A collection of students' home state at the University of Illinois from the 1998 - 2017 in a clean CSV format.

[A single CSV containing all of the data can be downloaded here (29 KB, 1079 rows x 6 columns)][CSV_Download]

[CSV_Download]: https://raw.githubusercontent.com/wadefagen/Students-by-State-at-UIUC/master/students-by-state-uiuc.csv


## Data Format

The first row in the CSV are column headers.  Every other row contains data.  Sample:

| State | Year | Undergrad | Professional | Grad | Total |
| ----- | ---- | --------- | ------------ | ---- | ----- |
| Alabama | 2017 | 20 | 2 | 14 | 36 |
| Alabama | 2016 | 17 | 2 | 15 | 34 |
| ... |
| Illinois | 2017 | 24251 | 537 | 3330 | 28118 |
| ... |

### Values of `State`

Data for each the 50 US states is present for every year in the dataset.  In addition to the 50 states, the following data is labeled as `State`s:

- `District of Columbia`, data present for all years
- `Guam`, data present in 2013-2017
- `Military`, data present in 2000-2017
- `Puerto Rico`, data present in 2013-2017
- `Unknown`, data present in 2004-2017
- `Virgin Islands`, data present in 2017 only


## Data Source

All data contained here was sourced from the [Final Statistical Abstract][DMI_FSA] provided by the [Division of Management Information at The University of Illinois][DMI].  The data provided by DMI is organized as a combination of files in Excel, HTML, and PDF formats; the data here is the same data as a single CSV file.

[DMI]: http://dmi.illinois.edu/
[DMI_FSA]: http://dmi.illinois.edu/stuenr/#abstract
