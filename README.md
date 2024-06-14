# ConsistenyCheck 
ConsistenyCheck is a toolkit for checking data consistency among ENSDF datasets, grouping levels and gammas, averaging values from different datasets, making a new adopted dataset based on grouping results and analysis, and more. It is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change history

#### 2024-06
Critical update: update NSR retrieval methods (for keynumber checking) with the new NSR search engine (online Jun 2024). Note that all previous versions using the old NSR search engine are no longer working for checking keynumbers due to the offline of the old NSR.

#### 2024-03
Bug fixes and improvements

#### 2023-11
Bug fixes and improvements

#### 2023-06
Major update: add checking for keynumber format and relevance (by querying NSR database online), with report in the A#_keynumber.rpt file, e.g., 31_keynumber.rpt for A=31 nuclide or mass chain.

#### 2023-05
Bug fixes and improvements

#### 2023-03
Major update: add function for checking ENSDF format with error messages in the .fmt file.

#### 2022-11
Minor improvements.

#### 2022-09
Bug fix.

#### 2022-06
Bug fixes.

#### 2021-03
More checking items have been included, and improved level-matching algorithm for matching levels from different datasets

#### 2019-10
New version of the utility code replacing Pandora

#### 2019-04
- option ''.fed'' in main window for writing feeding gammas of all levels into an output file (Ninel)
- band labels of initial and final level of a feeding gamma in the display window and output file for feeding gammas (Jag)

#### 2018-12
beta version 

## Disclaimer

Neither the author nor anybody else makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness or usefulness of any information disclosed, or represents that its use would not infringe privately owned rights.
