# 6.6 Scoring Procedures

## 6.6.1 Overview of Scoring

The Compumedics software system will be used to process all the records.  Scorers will review the record using a computer monitor in two passes.  First, computer generated scoring of respiratory events during the “offline” processing will be deleted. Then during the first pass, sleep stages and arousals will be marked manually on a (30 s. time base) epoch by epoch basis.  During the second pass, respiratory signals will be displayed (2 or 5 min. time base), respiratory events will be manually marked, and oxygen saturation data edited.

During manual scoring, the following are primary “events” that are identified:

<u>Sleep stages</u> will be identified for each 30 second epoch using Rechtshaffen and Kales criteria (Rechtshaffen A, Kales A. A Manual of Standardized Terminology Techniques And Scoring System for Sleep Stages in Human Subjects.  Washington, DC: US Government Printing Office, 1968).

<u>Arousals</u> will be characterized by the ASDA (now American Academy of Sleep Medicine) criteria (The Atlas Task Force, EEG Arousals: Scoring Rules and Examples.  Sleep 1992: 15:173-84).

<u>Obstructive Apneas</u> will be identified if the amplitude (peak to trough) of the airflow signal is flat or nearly flat. This is noted when amplitude of airflow decreases below at least 75% of the amplitude of “baseline” breathing, i.e. to < 25% of the baseline, (identified during a period of regular breathing with stable oxygen levels), and if this change lasts for ≥ 10 s.  Obstructive apneas cannot be designated in areas of the study where thermistry is missing or uninterpretable.

<u>Hypopneas</u> will be identified if the amplitude of any respiratory signal decreases by at least (approximately) 30% of the amplitude of “baseline”, i.e. to < 70% of baseline, (identified during a period of regular breathing with stable oxygen levels), if this change lasts for > 10 s.

<u>Central Apneas</u> will be noted if no displacement is seen on either the chest or abdominal inductance channels.  Otherwise, events will be noted as “obstructive”. Central events cannot be designated if either or both band data are missing or uninterpretable.

Computer analysis will link data from varying channels to identify desaturation levels, sleep summary data, and various Respiratory Disturbance Indices (RDIs). The following describe how these data are used:

The <u>desaturation associated with any respiratory event</u> will be based on the nadir desaturation reached within a user defined amount of the time (usually within 30 sec) of the end of the event.  The magnitude of the desaturation for an event is the difference between the greatest saturation level observed during the event and this minimum.  The scorer will manually check events to assure that the appropriate desaturation is identified and modify the time lag as needed.

<u>An arousal will be associated with a respiratory event</u> if the arousal begins less than 5.0 seconds after the end of the event (i.e.: 0-4.9 seconds).

<u>RDI</u> (Respiratory Disturbance Index) is defined as the number of respiratory events (apneas and hypopneas) per hour of the sleep. Events will be included in different indices according to level of associated desaturation and/or arousal:

- All events (regardless of desaturation or arousal)
- Summary RDI values, based on events associated with ≥ 2%, ≥ 3%, ≥ 4%, and
 ≥ 5% desaturation levels.
- Summary RDI values based on events associated with  > 2%, 3%, 4%, and 5% desaturation levels or associated arousal.
- Summary RDI values based on events associated with arousal regardless of desaturation.

<u>Time in apnea or hypopnea:</u>

- Percent sleep time in apnea (obstructive or central, with at least a 3% desaturation +/- arousal).
- Percent sleep time in hypopnea (with at least a 3% desaturation +/- arousal).

<u>Oxygen Desaturation Profile:</u>

- Percent sleep time in desaturation (<95%, <90%, <85%, <80%, <75%).
- Number of desaturations/hour of sleep (unlinked with respiratory events) of 2%, 3%, 4%, 5%.

<u>Sleep Architecture:</u>

- Time and percent of sleep time in each sleep stage (combine Stages 3 and 4).
- Arousal index.
- Number/hour of upward stage (from deeper to lighter) shifts; wake shifts.
- Sleep efficiency.(sleep time/time in bed – lights off to end of study)
- Sleep latency (lights off to sleep onset); REM latency I (defined as time from onset of sleep to first REM).

<u>Heart Rate data:</u>

- Maximum, minimum and mean heart rate noted during sleep, associated with respiratory events and associated with the arousals (in REM and Non-REM separately).

Following manual scoring of the computer record, the scorer also completes the QS Form to indicate whether unusual patterns describing breathing or EEG are noted or if problems were encountered during the scoring process that could reduce the reliability of the scored data. These include:

- Abnormal Awake EEG
- Alpha intrusion
- Abnormal Eye Movements
- Periodicity
- Periodic large breaths
- Sleep staging/arousal unreliable
- Apneas vs. hypopneas unreliable


## Summary of Scoring Process

Each study will be manually scored in the two passes:

During the first pass:

- Review the “lights” channel and manually set time of “lights off” and “lights on.”
- The EEG, EMG and EOG signals from each study will be reviewed on an epoch by epoch (30 s.) basis (screen).  Each epoch will be assigned a sleep stage. Periods of EEG change that meet the criteria for arousal will be marked.

During second pass:

- Respiratory data (airflow/abdominal/chest/saturation) will be reviewed on 5 minute pages.  The saturation channel will be edited for artifact and respiratory events will be marked manually according to the rules stated below.

Finally, the following will be done:

- The QS Form will be completed, indicating unusual patterns, reliability problems, and signal/study QA grades.
- The outlier program will be run, to identify implausible values.
- Participant Feedback Sleep Reports will be generated.
- The raw and scored files and summary reports will be saved, to the scoring hard drive.


<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
<div class="btn-group">
  <a href=":pages_path:/mop/6-50-mop-data-processing.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    6.5 Data Processing
  </a>

  <a href=":pages_path:/mop/6-00-mop-toc.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Table of Contents
  </a>

  <a href=":pages_path:/mop/6-620-mop-scoring-rules.md" class="btn btn-success">
    6.6.2 Scoring Rules
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
