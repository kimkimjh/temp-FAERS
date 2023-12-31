# temp-FAERS
This repository contains the prepared dataset for the manuscript titled "Utilizing Temporal Patterns of Adverse Event Reports to Identify Potential Late-Onset Adverse Events." The dataset consists of 1,426,781 reports, as described in Table 1 of the manuscript. To facilitate analysis of adverse events or drugs, these three files should be merged into a single file using the 'primaryid' as the key column. Further details on the merging process are provided in the manuscript.

## Contents
- `df_summarized.csv.gz`: Contains the processed adverse event reports. Contains primaryid, caseid, age, occp_cod, drugname, etc. 
- `df_OUTC.csv.gz`: Contains OUTC records.
- `df_REAC.csv.gz`: Contains REAC records.

For more information and a comprehensive explanation, please refer to the manuscript.
