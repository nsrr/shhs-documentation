# Dataset Introduction

The [Sleep Heart Health Study dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. At a time in the future, the SHHS data are set to be deposited into [NHLBI's BioLINCC resource](https://biolincc.nhlbi.nih.gov/home/), at which point the NSRR SHHS data will be brought in line to closely match what is in BioLINCC.

Until then, the SHHS data shared on the NSRR closely match the latest analytic datasets produced by the SHHS Coordinating Center. Some steps have been taken to deidentify the dataset (mostly by removing dates) and clean of extraneous values for certain variables. 

## Structure of the Dataset

The dataset is broken down by participant and by visit. The `visitnumber` variable is defined as follows:

1. Visit 1 -- the baseline clinic visit and polysomnogram performed between 1995 and 1998
	- 5,804 rows, down from the original 6,441 due to data sharing rules on certain cohorts and subjects
2. Visit 2 -- the follow-up clinic visit and polysomnogram performed between 2001 and 2003
	- 4,080 rows, not all cohorts and subjects took part
3. CVD Outcomes -- the tracking of adjudicated heart health outcomes (e.g. stroke, heart attack)
	- 5,042 rows, not all cohorts and subjects took part


<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
<div class="btn-group">
  <a href=":pages_path:/3-data-analysis-tip-sheet.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    Data Analysis Tip Sheet
  </a>
  
  <a href=":pages_path:/3-reliability-shhs1.md" class="btn btn-success">
    Reliability for SHHS1
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>

