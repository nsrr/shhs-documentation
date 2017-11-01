# Dataset Introduction

The [Sleep Heart Health Study dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. The dataset was based upon the [data prepared and deposited on BioLINCC in May 2014](https://biolincc.nhlbi.nih.gov/studies/shhs/?q=sleep) by the [SHHS Coordinating Center at Johns Hopkins University](http://www.jhsph.edu/research/centers-and-institutes/johns-hopkins-center-for-clinical-trials/shhs.html). Changes and updates to the source data and variable definitions have been coordinated in the [shhs-data-dictionary repository](https://github.com/sleepepi/shhs-data-dictionary).

**Disclaimer:** These data are not perfect. Known implausible or impossible values have been tracked and documented in our [KNOWNISSUES list](https://github.com/sleepepi/shhs-data-dictionary/blob/master/KNOWNISSUES.md). Please [submit issues](https://github.com/sleepepi/shhs-data-dictionary/issues) for any new problematic findings.

## Structure of the dataset

The dataset is broken down into five (5) files that correspond to the main SHHS encounters:

1. `shhs1` (Visit 1) -- the baseline clinic visit and polysomnogram performed between 1995 and 1998
	- 5,804 rows, down from the original 6,441 due to data sharing rules on certain cohorts and subjects
2. `shhs-interim-followup` (Interim Follow-up) -- an interim clinic visit or phone call 2-3 years after baseline
  - 5,804 rows, despite some subjects not having complete data, all original subjects are present in the dataset
3. `shhs2` (Visit 2) -- the follow-up clinic visit and polysomnogram performed between 2001 and 2003
	- 4,080 rows, not all cohorts and subjects took part
4. `shhs-cvd` (CVD Outcomes) -- the tracking of adjudicated heart health outcomes (e.g. stroke, heart attack) between baseline and 2008-2011 (varies by parent cohort)
	- 5,802 rows, outcomes data were not provided on all subjects
5. `shhs-cvd-events` (CVD Outcome Events) -- event-level details for the tracking of heart health outcomes
  - 4,839 rows, representing individual events

**Note:** Due to sovereignty issues, Strong Heart Study participants are not included in the shared SHHS data. Data from a total of 5804 participants (1915 ARIC, 1230 CHS, 688 Framingham Offspring and 1971 from other studies) consenting to share data are available.

## Identifiers in the dataset

As part of the de-identification process, all calendar dates were censored from the datasets. These dates have been replaced with a *day offset* type variable that is based upon the `index date`, which for SHHS represents the date of the overnight polysomnography measurement from SHHS Visit 1.

A "cohort" (i.e. data collection site) variable is not available. This variable was censored because it is an identifier.

## CVD outcomes and mortality adjudication

The following description was provided by the SHHS Coordinating Center:

> The SHHS cohort was enrolled in the mid-1990s from existing epidemiological studies. There were 6,441 participants enrolled at 11 different investigative sites across the country; the data from these participants are referred to as SHHS 1. Followup 1 data was collected on cardiovascular events for this original cohort approximately 2-3 years after the enrollment visit. The population for the second follow-up examination (SHHS 2) includes surviving members of the original cohort who when contacted by a letter announcing the continuation of the study, indicated interest in undergoing a second home visit AND/OR PSG.
>
> Outcomes data for SHHS subjects belonging to these cohorts have been provided to SHHS by the parent cohorts; these data are referred to as CVD Outcomes. ARIC, CHS, FHS, and SHS studies have had mechanisms in place for determining CVD outcomes since the start of SHHS. The SHHS subjects recruited in Tucson and New York were members of research cohorts that did not include ongoing assessment of CVD outcomes. In these two sites, SHHS investigators have implemented their own procedures for ascertaining and adjudicating CVD outcomes among SHHS participants. These procedures have been closely modeled on those of CHS.
>
> Key outcomes for SHHS include the following incident or recurrent CVD events or diagnoses occurring subsequent to the first SHHS PSG:
>
> A. Hospitalized acute MI (HAMI)
> B. Coronary surgical intervention -- percutaneous transcutaneous angioplasty (PTCA), coronary stent placement, coronary artery bypass grafting (CABG)
> C. Congestive Heart Failure (CHF)
> D. Coronary heart disease death
> E. Any coronary heart disease (CHD) -- summary variable which includes a, b, and d above.
> F. Any cardiovascular disease (CVD) -- summary variable which includes a - d above.
> G. Angina pectoris (AP) -- at CHS and FHS only
>
> The following recurrent events will be considered endpoints for the SHHS:
>
> A. HAMI
> B. Coronary surgical intervention
> C. Stroke

[Punjabi et al. (2009)](https://www.ncbi.nlm.nih.gov/pubmed/19688045) includes an overview of how mortality data were ascertained from the cohorts:

> Deaths from any cause, the primary endpoint for this report, were identified and confirmed for the cohort using multiple concurrent approaches including follow-up interviews, written annual questionnaires or telephone contacts with study participants or next-of-kin, surveillance of local hospital records and community obituaries, and linkage with the Social Security Administration Death Master File. Using these methods, 1,047 deaths were identified in the incident cohort with a censoring date of April 1, 2006. During the follow-up period, 147 participants reported treatment with positive airway pressure, an oral appliance, supplemental oxygen, or an open tracheostomy. Sensitivity analyses with exclusion of these participants showed that estimates of mortality risk associated with sleep-disordered breathing remained materially unchanged. Thus, analyses that exclude these participants are reported herein.
