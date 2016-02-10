# Dataset Introduction

The [Sleep Heart Health Study dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. The dataset was based upon the [data prepared and deposited on BioLINCC in May 2014](https://biolincc.nhlbi.nih.gov/studies/shhs/?q=sleep) by the [SHHS Coordinating Center at Johns Hopkins University](http://www.jhsph.edu/research/centers-and-institutes/johns-hopkins-center-for-clinical-trials/shhs.html). Changes and updates to the source data and variable definitions have been coordinated in the [shhs-data-dictionary repository](https://github.com/sleepepi/shhs-data-dictionary).

**Disclaimer:** These data are not perfect. Known implausible or impossible values have been tracked and documented in our [KNOWNISSUES list](https://github.com/sleepepi/shhs-data-dictionary/blob/master/KNOWNISSUES.md). Please [submit issues](https://github.com/sleepepi/shhs-data-dictionary/issues) for any new problematic findings.

## Structure of the Dataset

The dataset is broken down into five (5) files that correspond to the main SHHS encounters:

1. `shhs1` (Visit 1) -- the baseline clinic visit and polysomnogram performed between 1995 and 1998
	- 5,804 rows, down from the original 6,441 due to data sharing rules on certain cohorts and subjects
2. `shhs-interim-followup` (Interim Follow-up) -- an interim clinic visit or phone call 2-3 years after baseline
  - 5,804 rows, despite some subjects not having complete data, all original subjects are present in the dataset
3. `shhs2` (Visit 2) -- the follow-up clinic visit and polysomnogram performed between 2001 and 2003
	- 4,080 rows, not all cohorts and subjects took part
4. `shhs-cvd` (CVD Outcomes) -- the tracking of adjudicated heart health outcomes (e.g. stroke, heart attack)
	- 5,802 rows, outcomes data were not provided on all subjects
5. `shhs-cvd-events` (CVD Outcome Events) -- event-level details for the tracking of heart health outcomes
  - 4,840 rows, representing individual events

**Note:** Due to sovereignty issues, Strong Heart Study participants are not included in the shared SHHS data. Data from a total of 5804 participants (1915 ARIC, 1230 CHS, 688 Framingham Offspring and 1971 from other studies) consenting to share data are available.

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

