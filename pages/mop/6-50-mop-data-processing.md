## 6.5 Data Processing

### 6.5.1 Study Receipt

Upon receipt of studies at the Reading Center all zip cartridges will be scanned for viruses.  The Study Receipt form will be completed, including the following information:  Field Center ID, Participant ID, Alpha Code, Study Date, Zip cartridge number, date received, Monitor/Headbox ID, and Technician ID.  If there is a discrepancy between the data contained the Signal Verification Form and the Compumedics Sleep Study recorded file, an e-mail will be sent to the Site Coordinator requesting clarification.    If any site is noted to have a significant number of discrepancies in the data submitted, the Coordinator at the site will be contacted by the SRC to request they identify source and report action taken to correct.   The data from the study receipt form will be entered into the Receipts table database.

The Signal Verification (SV) Form and Sleep Study Evaluation (SE) form for studies that have been evaluated at the site and determined to be Failed will be sent to the SRC along with the weekly zip cartridges.   This data will also be entered into the Receipts table database when received, indicating study was Not Sent and coded with a reason for the failure.


### 6.5.2 Offline Automatic Analysis

This Compumedics program must be run prior to review of studies and final scoring to allow visualization of signals and graphic screens.  Automatic sleep staging and respiratory scores are generated during the process. These data will not be used as final scores.  (Offline Analysis detailed procedures are located in Appendix).





### 6.5.3 Preliminary Review

After offline analysis of the record, the CP will then review each study to determine if overall quality is sufficient to be scored (passed/failed), and identify any potential medical alerts (defined as preliminary RDI >45).      In addition, the CP will note any signal quality issues, possible monitor malfunctions, and recommendations for electrode replacements on the Receipt form.

Minimal criteria for study acceptability:  The record must contain at least 4 hours of scorable EEG, oximetry and respiratory data (either airflow, thoracic or abdomen) between (edited) lights off and lights on (Total Recording Time). Recorded time after final awakening will not contribute to this time. Two continuous blocks of scorable data, each at least 2 hours long are required to consider study acceptable for scoring.

### 6.5.4 Feedback of Data to the Sites

After preliminary review by the CP is completed, the pass/fail status of the record is entered into the Receipts table database along with any comments and feedback notes regarding quality of the study and equipment troubleshooting.   On a weekly basis the following reports are e-mailed to the site coordinator:

- <u>Record of Receipts</u> -  Lists Participant ID, Study Date, Date Received at SRC,
Zip Cartridge Number, Monitor ID, Headbox ID, Tech ID, and Pass/Fail Status.

- <u>Preliminary Study Quality Report</u> - Contains Participant ID, Study Date, Tech ID,
Pass/Fail status and Comments from the CP regarding study quality and/or reasons
for failure.

The site coordinator is to verify that all information on the Record of Receipts is accurate and notify the SRC of any changes or corrections to be made.   The Preliminary Study Quality Report should be made available to the field site technicians and quality issues reviewed and discussed.

Failed studies are removed from the zip cartridges prior to scorer assignment and archived to CDs for troubleshooting exercises and review.

### 6.5.5 Assignment of Studies to Scorers

Potential Medical Alerts - Studies identified as potential medical alerts will be triaged for immediate full scoring (within 48 hours of assignment to scorer).   Once fully scored and determined to meet criteria for Medical Alerts (final RDI > 50, time in desaturation of <70% for >10% TST, or average heart rate > 150 BPM or <30 BPM for 2 minutes), a physician investigator will be asked to review the study.  If the medical alert is ascertained, it will be logged into a Medical Alert Log and the site will receive the Participant Feedback Sleep Report   and quality grades (QS form) with the regular weekly reports.

All remaining studies are scored based on date received.     Bi-monthly review of scored studies by site by scorer is done to maintain equal distribution of studies from all sites among the scorers.



### 6.5.6 Quality Grades (QS Form; Sleep Quality Form)

The quality of each signal and overall study quality will be assessed at the time of scoring of the record.  The Scorer will code each channel of information according to the duration of:  i) scorable signals; ii) duration of artifact free signals during sleep, and iii) an overall QA grade to each study.  The total duration of the study (from the edited lights off to the lights on) and the total duration of sleep will also be indicated.   Scoring notes regarding staging, event identification, outliers, and specific physiologic signal issues are also recorded on the QS form.   (See Section 7.0 for a more detailed description of criteria for grades and scoring notes. [Appendix B](:pages_path:/mop/6-AB-mop-sample-qs-form.md) contains a sample QS Form.)

All data contained in the QS form (quality grades and scoring notes) will be entered in the QS table database which contains only passed scored studies.

### 6.5.7 Scored Sleep Data

After full scoring, the scorer will generate:

- <u>SHHS Participant Feedback Report</u> (rtf format – See [Appendix C](6-AC-mop-sample-participant-feedback-sleep-report.md) for sample report),  contains summary sleep data. Data will be displayed in two parts (top/bottom of form), including the RDI (the number of apneas and hypopneas per hour of the sleep associated with a desaturation > 3%), a summary of the desaturation profile, time in REM/Non-REM sleep, stage distributions, and the arousal index.  The top half of the report will be used in the Participant Feedback Letters, and the bottom half (containing stage distribution and arousal indices) can be used in communications with local physicians.

- <u>SAS report</u> containing >760 variables.

- <u>Completed QS form</u> containing all quality grades and scoring notes.

The Sleep Data Summary Report and QS Report are e-mailed to each site on Mondays following the week scored (generally within 12 weeks of  receipt of the SRC, except for studies which are triaged as possible Medical Alerts, which will be returned within one to two weeks of receipt).

### 6.5.8 Archival of Data

After QS data has been entered and weekly reports are sent to sites, the complete study folder containing the raw data file, scored files, sleep study report, and the SAS report is placed in a site directory for the creation of CDs.   When sufficient studies have been scored for a particular site (15-20 studies), they will be archived onto CDs (in triplicate).   Copy A will be retained at the SRC, Copy B will be sent to the site along with zip cartridges that can now be reused, and Copy C will be sent to the Coordinating Center.

The summary scored data (>760 SHHS variables) are output as individual .txt files. After outlier checks, studies are imported on a monthly basis into a SAS file. This file is sent periodically to the CC for merging with the main SHHS dataset.


<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
<div class="btn-group">
  <a href=":pages_path:/mop/6-40-mop-quality-assurance-and-control.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    6.4 Quality Assurance and Quality Control
  </a>

  <a href=":pages_path:/mop/6-00-mop-toc.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Table of Contents
  </a>

  <a href=":pages_path:/mop/6-610-mop-overview-of-scoring.md" class="btn btn-success">
    6.6.1 Overview of Scoring
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
