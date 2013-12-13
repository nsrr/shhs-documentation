## 6. Scoring Procedures

### 6.1. Overview of Scoring

The Compumedics software system will be used to process all the records.  Scorers will review the record using a computer monitor in two passes.  First, computer generated scoring of respiratory events during the “offline” processing will be deleted. Then during the first pass, sleep stages and arousals will be marked manually on a (30 s. time base) epoch by epoch basis.  During the second pass, respiratory signals will be displayed (2 or 5 min. time base), respiratory events will be manually marked, and oxygen saturation data edited.

During manual scoring, the following are primary “events” that are identified:

<u>Sleep stages</u> will be identified for each 30 second epoch using Rechtshaffen and Kales criteria (Rechtshaffen A, Kales A. A Manual of Standardized Terminology Techniques And Scoring System for Sleep Stages in Human Subjects.  Washington, DC: US Government Printing Office, 1968).

<u>Arousals</u> will be characterized by the ASDA (now American Academy of Sleep Medicine) criteria (The Atlas Task Force, EEG Arousals: Scoring Rules and Examples.  Sleep 1992: 15:173-84).

<u>Obstructive Apneas</u> will be identified if the amplitude (peak to trough) of the airflow signal is flat or nearly flat. This is noted when amplitude of airflow decreases below at least 75% of the amplitude of “baseline” breathing, i.e. to < 25% of the baseline, (identified during a period of regular breathing with stable oxygen levels), and if this change lasts for > 10 s.  Obstructive apneas cannot be designated in areas of the study where thermistry is missing or uninterpretable.

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


### Summary of Scoring Process

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


### 6.2. Scoring Rules

_Locally introduced rules, based on discussions among the SRC staff and outside consultations are indicated by an (*)._

**Scoring sleep stages**

Scoring sleep stages is based on the guidelines specified by Rechtshaffen and Kales. When guidelines were adopted from other sources, the source is marked in parenthesis.  M.C. & A.R refers to Section 7, Chapter 73: Monitoring and Staging Human Sleep, written by M.A. Carskadon and A. Rechtschaffen, in Principles and Practice of Sleep Medicine ed. by M.H. Kryger, T.Roth and W. Dement; W.B. Saunders Co, 1989 (1st edition).

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.1 Rules for assigning epoch-specific sleep score:

Epoch-by-epoch approach: The polygraph record is divided into consecutive segments of equal size (30 s., each termed an “epoch”). Each epoch has assigned a single sleep stage score. The epoch duration is maintained for the duration of the recording.

- When more than one stage is present in an epoch, that epoch is assigned a single  stage score reflecting the stage that occupied the greatest portion of the epoch.
- When two stages of sleep are evenly distributed on the epoch, and one of these stages was the same stage as in the preceding epoch, then that epoch will be assigned the same sleep stage as the preceding epoch (*).
- Portions of two epochs may not be combined to create a new epoch.
- When an arousal of <15 sec. occurs within an epoch, the time “in arousal” is not counted when determining the predominant sleep stage time in that epoch.

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.2 Sleep onset

Sleep onset is defined by three consecutive epochs of stage 1 or one epoch of any other sleep stage.

<div class="bs-callout bs-callout-warning">
  <p>
    <strong>Caution in interpreting reports:</strong>
    The Compumedics software report identifies sleep onset as three consecutive epochs of sleep regardless of the stage. This may rarely cause a discrepancy between the identity of sleep onset, sleep time, and sleep latency as defined using the conventional approach used by the scorers (sleep onset as 3 epochs of stage 1 or one epoch of any other sleep stages) versus the output of computer generated reports.
  </p>
</div>

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.3 EEG arousal

Scoring arousals is based on “A Preliminary Report from the Sleep Disorders Atlas Task Force of the American Sleep Disorders Association” Sleep, vol. 15, no 2, 1992. (ASDA criteria)

The scoring of EEG arousals is independent from the scoring of sleep stages (i.e. an arousal can be scored in an epoch of recording which would be classified as wake by R & K criteria).  An arousal can proceed to the wake stage (by R & K criteria) or can be followed by a return to sleep.

<u>Definition of Arousal:</u>

An EEG arousal is an abrupt shift in EEG frequency, which may include alpha and/or theta waves and/or delta waves and/or frequencies greater than 16 Hz lasting at least 3 s., and starting after at least 10 continuous seconds of sleep.  (ArFigures 1a and 1b)

<div class="row">
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 1a - Sample Arousals</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar1a.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar1a.jpg">
      </a>
    </div>
  </div>
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 1b - Sample Arousals</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar1b.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar1b.jpg">
      </a>
    </div>
  </div>
</div>

Artifacts, K complexes and delta waves are included in meeting the 3 s. duration criteria only when they occur within the EEG frequency shift (change in frequency must be visible before these waveforms).   A "K" complex or spindle occurring immediately prior to the EEG shift or following is not included in the arousal duration.  (ArFigures 2a, 2b, 2c and 2d)

<div class="row">
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 2a - Sample Artifacts</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar2a.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar2a.jpg">
      </a>
    </div>
  </div>
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 2b - Sample Artifacts</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar2b.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar2b.jpg">
      </a>
    </div>
  </div>
</div>

<div class="row">
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 2c - Sample Artifacts</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar2c.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar2c.jpg">
      </a>
    </div>
  </div>
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 2d - Sample Artifacts</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar2d.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar2d.jpg">
      </a>
    </div>
  </div>
</div>

Parts of the EEG totally obscured by EMG artifact are considered an arousal if the change in background EEG in addition to the area obscured by EMG is at least > 3 sec.  (ArFigure 2e)

<div class="row">
  <div class="col-xs-12 col-sm-6 col-sm-offset-3">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 2e - Sample Artifacts</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar2e.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar2e.jpg">
      </a>
    </div>
  </div>
</div>

Alpha activity of less than 3 s. duration in Non-REM sleep at a rate greater than one burst per 10 s. is not scored as an EEG arousal.  Three seconds of alpha sleep is not scored as an arousal unless a 10 s. episode of alpha free sleep precedes this.

If both central EEGs are equivalent and interpretable, the arousal (EEG frequency shift) must be observed in both channels. If observed in only one of two equivalent channels, the change in EEG is assumed to be artifact and not an arousal.

Arousals lasting > 15 s. and containing awake EEG within an epoch cause the epoch to be classified as AWAKE.

**TIPS for Arousals Generally:**

- When unsure if change in background EEG represents an abrupt change, look at a 60 sec epoch and note if there is a discrete change from background EEG.
- Note whether changes were evident on both EEG channels.
- Be careful to distinguish an increase in EEG frequency from EMG artifact (esp. in delta sleep).  (ArFigures 3a and 3b).
- Isolated bursts of delta activity or sawtooth-like waves do not constitute an arousal.  In contrast, slow waves intermixed with fast activity that differs from background do qualify as arousals.  (ArFigures 4a, 4b and 4c.)
- Occasionally, EEG acceleration is superimposed on slower waves.  The slowing may be an artifact secondary to movement or burst of delta waves. If there is evidence of embedded EEG acceleration for > 3 sec., mark as an arousal. (ArFigures 5a and 5b)

<div class="row">
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 5a - EEG accleration</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar5a.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar5a.jpg">
      </a>
    </div>
  </div>
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">ArFigure 5b - EEG accleration</h3>
      </div>
      <a href=":datasets_path:/shhs/images/a/ar5b.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/a/ar5b.jpg">
      </a>
    </div>
  </div>
</div>

<u>Arousals in REM</u>

In stage REM, an EEG frequency shift must be accompanied by a simultaneous increase in amplitude of the chin EMG (lasting over 0.5 s.).  An arousal starts when a definite change in background EEG is visualized.  The increase in the chin EMG can occur anytime during the arousal (can be at the end) and is not a marker for the beginning of the arousal  However, increased EMG activity without a change in background EEG does not constitute an arousal (ArFigures 6a, 6b and 6c)

**TIPS for Arousals in REM:**

- If the level of REM EMG appears to be fluctuating, then the increase in EMG in the area of a putative arousal needs to be more than the background level of fluctuations, to identify this as a REM arousal.
- A long period of alpha activity before an EMG increase may mark the beginning of the arousal if the alpha activity represents the change in the background pattern.

**Potential Problems:**

Some studies with high RDIs have many arousals that may appear to last > 15 sec. within given epochs. If all such epochs were classified as AWAKE, then the respiratory events would not be included in the RDI and the RDI will be underestimated. When faced with this situation, the scorer may attempt to keep the duration of the arousal to as short as feasible (e.g., corresponding to the length of the waking EEG in that epoch.) This will maximize the number of epochs containing arousals that are captured as "sleep".

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.4 Rules for assigning sleep stages when arousal is present in the epoch

The following rules were established to maximize the amount of sleep identified and thus the number of respiratory events recorded (*):

Brief arousals (e.g. arousals < 15s. long) do not automatically require a change in sleep stage. The epoch is staged according to the sleep stage in the remaining parts of the epoch (not including the arousal).

If an arousal or an area of increased EMG causing artifact in the EEG channels is followed by Stage wake (W), then the arousal is considered part of the record scored as a stage Wake.  If this part is > 15 s. long, then epoch is scored as a Stage Wake.

In  Deep Sleep (unequivocal Stage 3/4), <u>when fast frequency waves are visualized as “riding” on the top of the delta waves</u>, and there are no frequencies characteristic of Stage Wake (*):

- If there is any reason to suspect that the fast frequencies are result of artifact (like a sudden increase in EMG bleeding into EEG), an arousal is not scored.
- When the fast frequencies are not the result of artifact, an arousal is scored. Deep Sleep is scored when delta waves persist despite the faster frequencies riding on top, independent of the length of the arousal.

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note for Delta Sleep:</strong>
    When an arousal includes bursts of Delta waves: these waves are not used for meeting Deep Sleep criteria (e.g. Deep Sleep is scored only if there is > 20 % of the epoch covered by delta waves outside of the arousal).
  </p>
</div>

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.5 Episodic events in sleep

**Sleep spindles:** clearly visible, rhythmic bursts of activity 12-14 Hz, duration at least 0.5 s. (one should be able to count 6 or 7 distinctive waves within a half-second period); the amplitude variability appears sinusoidal.  (EpFigures 1a and 1b)

<div class="row">
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">EpFigure 1a - Sleep Spindle Activity</h3>
      </div>
      <a href=":datasets_path:/shhs/images/e/ep1a.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/e/ep1a.jpg">
      </a>
    </div>
  </div>
  <div class="col-xs-12 col-sm-6">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">EpFigure 1b - Sleep Spindle Activity</h3>
      </div>
      <a href=":datasets_path:/shhs/images/e/ep1b.jpg?inline=1">
        <img src=":datasets_path:/shhs/images/e/ep1b.jpg">
      </a>
    </div>
  </div>
</div>

Sleep spindle activity occurs in adults with a frequency of about three to eight bursts per minute in Stage 2 sleep.  These are absent in wakefulness and Stage 1.  Spindles may be rarely observed in Stage REM and 3-4.  Spindle rate appears to be a fairly stable individual characteristic.  In the elderly and in individuals with various medical conditions, sleep spindles tend to lose their classic morphology and may have a slightly slower frequency, lower amplitude, and shorter duration.

**Medication effects** can introduce beta range activity that may be confused with spindles.
Tips to alert to the presence of drug effects mimicking spindles are two or more of the following:
(EpFigures 2a and 2b)

- Increased beta activity (spindle like) in well defined REM sleep and wakefulness.
- Increased spindle duration (often > 1 sec.)
- Increased frequency of spindles per epoch (>5/epoch).
- Spindle like activity with amplitude variability that is NOT sinusoidal.
- Fast frequencies (often > 13 Hz).
- When identifying atypical “spindle activity,” review previous epochs to ascertain if stage was properly scored.
- When atypical spindle like activity is observed, then such activity cannot be used to distinguish Stage 2 from other sleep stages.  This may lead to some underscoring of Stage 2 from 1.

**K-complex:**  EEG waveforms having a well-outlined negative sharp wave, immediately followed by a positive component.  Total duration of the K complex should exceed 0.5 s.  Waves of 12-14 Hz (sleep spindles) may or may not constitute part of K complex. K complexes can occur as a response to sudden auditory stimuli.  K complexes may be reflected on the EOG channels.  When in doubt about whether a particular polyphasic wave is a “true” K complex, record is scanned for clear Stage 2 sleep.  Questionable K complexes are only designated as K complexes if their morphology closely matches those seen in unequivocal Stage 2 sleep.  (EpFigures 3a, 3b, 3c, and 3d)

<div class="bs-callout bs-callout-warning">
  <p>
    <strong>Caution!</strong>
    On the Compumedics system used in SHHS 1, with correct electrode placements, the first, negative part of K complex should be down going and subsequent positive component up (as  seen with some traditional polygraphs).  If the K complex is reflected on the EOG channels, it will usually appear to be in the opposite phase as that seen on the EEG channel.  Sometimes K complexes on EEG are in the same phase as on EOG channels (EEG tracing is upside down).  This may be caused by erroneous electrode placement (switching the reference with the C3 or C 4 electrode).  If this happens on the channel used for scoring sleep stages, the computer will not recognize K complexes during automatic analysis.
  </p>
</div>

**Hypersynchrony:** bursts of high voltage delta (< 4 Hz) or theta (4 - 7 Hz) waves lasting 2-3 s. with a comb-like morphology with a positive polarity (points up going).  Hypersynchrony is not considered an arousal. May need to be distinguished from seizure discharges. (EpFigures 4a, 4b, 4c, and 4d)
In children, this actually may be exaggerated.  It is relatively more common during the transition from wakefulness to sleep.

**Seizures:**  This is manifest by an abrupt change in background EEG.  This usually requires a wider sampling of areas of the brain than is provided with our montage.  Two patterns are commonly seen: 1) High voltage, rhythmic activity in the 2-6 Hz range, or 2) Diffuse sustained beta activity.  A seizure is often accompanied by prominent muscle artifact.  A seizure is usually followed by low to moderate voltage irregular slowing.  On the 10 s. screen, characteristic ‘spikes and wave’ pattern may be seen.  If a possible seizure is identified, a physician investigator will be immediately asked to review the study. (EpFigures 5a, 5b, 5c, 5d, and 5e)

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.6 Rules for assigning sleep stages

EEG frequencies are divided into following bandwidths:

<pre>
           β  (beta)     > 13 Hz
13 Hz    ≥ α  (alpha)    ≥  8 Hz
&nbsp;8 Hz    > θ  (theta)    ≥  4 Hz
&nbsp;4 Hz    > δ  (delta)
</pre>

An alpha wave is any wave that has the frequency in alpha range.
Alpha rhythm (also known as posterior background rhythm) has the following characteristics:

- Is seen in the relaxed waking state with the eyes closed.
- Attenuates with eye opening, anxiety or mental activity such as mental calculations
- Slows in drowsiness (occasionally <8 Hz) and then disappears in sleep. The slowing may be so brief as to be unnoticed.
- Generated by occipital lobes and has a broad reflection to temporal and mastoid areas.

An illustration of the differences in alpha with open and closed eyes is shown in (SsFigures 1a, 1b, 1c, and 1d).

**<u>Stage W - Waking State</u>**

Stage W, when eyes are open, is defined by low voltage, mixed frequency EEG in the alpha and beta ranges (> 8 Hz). When eyes are closed, wake is defined by the presence of the alpha rhythm.  There is usually (but not necessarily), a relatively high tonic EMG.  Waking shows frequent eye movements and eye blinks.  Some subjects may have  virtually continuous alpha activity, others may show little or no alpha activity in the waking record.

**<u>Stage 1 sleep</u>**

Stage 1 sleep occurs most often in transition from wakefulness to other sleep stages.

Stage 1 is defined by a background of relatively low voltage, mixed frequency EEG activity with noticeable activity in the 2-7 Hz range with no clearly defined K complexes or sleep spindles. Faster frequencies are mostly lower voltage (amplitude).  High voltage (50-75 μV) 2-7 Hz activity tends to occur in irregularly spaced bursts mostly during the later portions of the stage.  There are slow eye movements, each of several seconds duration, usually most prominent during early portions of the stage.  No rapid eye movements or blinks are present.  During the latter portion of the stage, vertex sharp waves, occasionally as high as 200 μV, are often seen in conjunction with high amplitude 2-7 Hz activity.  The amount of alpha activity combined with low voltage activity comprises less than half of the epoch.  Finally, the tonic EMG level may be lower than observed during relaxed wakefulness.  (SsFigures 2a, 2b, 2c, and 2d)

Traces of low voltage activity at 12-14 Hz may begin to appear as the transition to Stage 2 approaches, but this activity is not defined as a sleep spindles until the rhythmic bursts are clearly visible for at least 0.5 s.

Intervals of > 3 minutes between K complexes or spindles (and which do  not meet criteria for REM of delta sleep or Wake ) are staged as Stage 1 (“3 minute rule”).
 

**<u>Stage 2 sleep</u>**

Stage 2 is defined by a background similar to Stage 1 sleep with the presence of the K complexes and/or sleep spindles.  It is impossible to define the difference between Stage 1 and Stage 2 sleep on the basis of background activity alone. Bursts of other polymorphic high voltage slow waves, which do not have the precise morphology of K complex, are also frequently seen.  Delta waves: high amplitude ( > 75 μV), slow (≤ 4 Hz;  duration 0.5 s. and longer) activity occupy no more than 19% of the epoch.  At the beginning of the Stage 2, slow eye movements may infrequently, and only briefly, persist after the appearance of sleep spindles and K complexes. (SsFigures 3a, 3b, and 3c)

Relatively long periods may intervene between K complexes and/or sleep spindles without a background change in the EEG.  Regardless of the presence of the arousal:

- If there is <3 minutes of the low voltage, mixed frequency EEG between sleep spindles and/or K complexes, this portion of the record is scored as Stage 2.
- Otherwise if > 3 minutes,  this portion of the record is scored Stage 1.

K complexes may be imbedded within an arousal and nonetheless constitute evidence of Stage 2.
(SsFigure 4a)

**<u>Deep Sleep (Stage 3 and 4)</u>**

In SHHS, no attempt is made to distinguish Stage 3 from Stage 4 which are combined into a single category: Deep Sleep.

Deep Sleep is scored when 20% or more of the epoch consists of delta waves which are < 2 Hz (duration 0.5 s.) and have an amplitude greater than 75 μV.  The 20% criteria refers specifically to the time occupied by the high amplitude, slow waves, and does not include intervening waves of higher frequency and lower amplitude or K complexes. To fulfill the criteria for Deep Sleep, one should be able to find at least 5-6 high voltage delta waves in the 30second sleep epoch (SsFigures 5a and 5b).  Delta waves embedded in increased frequency activity (an arousal) do not contribute to the calculation of time in delta sleep. (SsFigure 5c)

Sleep spindles and K complexes may or may not be present in Deep Sleep (SsFigure 5d).  Eye movements do not occur in Deep Sleep, although the EOG may reflect the high voltage slow wave activity.  The EMG is tonically active, although the tracing may achieve very low levels, indistinguishable from that of REM sleep.

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    In the Compumedics software Stages 2, 3/4 are assigned based on the amount of the  “delta-H” waves.  K complexes and all the waves from the delta range (< 2 Hz) are considered by the computer algorithm  in the count of these waves. The computer based calculation of delta sleep can be used to help determine % of slow waves when there are K complexes or events or other artifact.  When any ambiguity exists, the scorer must quantify the percentage of time delta waves occupy within the epoch.   Any questionable areas should be re-measured, subtracting time occupied by K complexes and other waveforms.
  </p>
</div>

An attempt should be made to distinguish between spontaneous K complexes and delta waves, although this distinction is not always easy.  When a K complex distinction is in doubt, comparison should be done with the K complex in unambiguous Stage 2.


**<u>Stage REM sleep</u>**

Stage REM is defined by a background of relatively low voltage, mixed frequency EEG with accompanying episodes of REMs (Rapid Eye Movements).  The EEG pattern resembles Stage 1, except that vertex sharp waves are not readily noticeable.  Bursts of characteristic “sawtooth” waves may appear, appearing as notched waves in the theta range.  Alpha activity is usually more prominent than in Stage 1 and its frequency is 1-2 Hz slower than the alpha rhythm in wakefulness.  The EMG reaches its lowest levels (it cannot be higher than the level during the preceding stage). Phasic twitches and intermittent increases of EMG activity may be observed but intervening baseline must remain low.  Phasic twitch (EMG) defined as:  short (no longer than .10 sec burst of EMG activity superimposed on suppressed muscle tone which physically manifests as a twitch (contraction) of a muscle or jerk of a limb.  In REM such muscle contractions may be isolated or become repetitive, but they remain distinctive.  Periods of the relatively low voltage, mixed frequency EEG and EMG at Stage REM level but without eye movements may follow unambiguous stage REM and is considered Stage REM unless criteria for a state change are met. (SsFigures 6a, 6b, 6c, 6d, and 6e)

The EOG shows bursts of rapid eye movements; often the density of such bursts increase as sleep progresses. Thus, earlier Stage REM episodes usually contain fewer REMs than later episodes.

Rarely delta waves may be observed in an epoch that is within a period of REM (SsFigures 7a and 7b).  If occurring within period of REM, a low EMG, continue to score as REM.  Large sawtooth waves also may be confused with hypersyncrony  (SsFigure 7c).

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    <u>Excessive beta activity may be observed in REM and should not be confused with spindles.</u> Medications (benzodiazepine or barbiturate ingestion) may induce excessive beta activity in both REM and Non-REM sleep. This beta activity can mimic sleep spindles. Their frequencies often are faster than those seen with the true sleep spindles (see above Stage 2 sleep section  for guidance on identifying spindles). Rarely, sleep spindles can be seen in REM in subjects with substantial sleep deprivation (SsFigures 7d, 7e, and 7f).
  </p>
</div>


**Start of the Stage REM:**

At the start of Stage REM, K complexes, sleep spindles and delta waves end, characteristic sawtooth waves can appear.  EMG levels tend to be the lowest after eye movements begin.  The fall in EMG may not coincide with the EEG changes.

- If the EMG drops before the last sleep spindle, K complex or delta wave: Score Stage REM from the point the last sleep spindle, K complex or delta wave was seen. (SsFigure 6a).
- Otherwise: Score Stage REM from the point where EMG drops.  The period of the record before the EMG drop is scored according to the rules for NREM sleep. (SsFigure 8a).

<u>Periods of elevated sustained EMG during Stage REM sleep:</u>

When EMG is elevated above the REM level for longer than .5 sec, then this portion of the record is scored as a Non-REM sleep or WAKE.  If phasic twiches or sawtooth waves are seen, but intervening EMG is low, the epoch remains REM (SsFigure 6e).

**WAKE-REM Transition:**

When one epoch or more of Stage Wake slows into a low voltage, mixed EEG pattern before REMs or sawtooth waves begin: Score Stage 1 until the EMG drops to REM level and Stage REM afterwards. (*)   (SsFigure 8a)

<u>When Stage Wake (> 15s.) interrupts Stage REM</u> (i.e., REM-> WAKE ): (*)

If the EEG background of the epochs between the intervening waking epoch and the appearance of REMs (eye movements) is ambiguous (i.e. the EEG background is compatible with either REM or Non-REM sleep), then
Score as Stage 1 if the EMG is elevated  (SsFigure 8a).
Score as Stage REM when EMG is at the Stage REM level  (SsFigures Series 9a, 9b, 9c, 9d, and 9e).
However, if a sleep spindle or K-complex appears prior to the appearance of REMs, then the waking epochs are considered the end of the Stage REM (SsFigures Series 9f, 9g, 9h, 9i, 9j, and 9k).

<u>When arousals (< 15 sec) interrupt REM:</u>

The occurrence of an arousal in REM does not automatically change sleep state. However, if the EMG increases after the arousal, REM is considered terminated by the arousal.  The following epoch is non REM.

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    Often a single K complex may be seen in REM after an arousal, with subsequent REMs. This per se does not change REM state. In particular, K complexes do not change REM state if intervening eye movements are seen following the K complex or the interval between the first K complex and the subsequent K complex is > 3 minutes  (SsFigure 7f).   In contrast, a K-complex occurring after a period of wake interrupting REM does change the state (beginning with Stage 2 at the first K-complex, and Stage 1 between the end of wake and the next K-complex)  (SsFigures 9f, 9g, 9h, 9i, 9j, and 9k).
  </p>
</div>

**<u>End of the Stage REM</u>**

Stage REM is scored until a clear evidence of sleep stage change is visualized:

- Appearance of K complexes or sleep spindles without presence of eye movements or sawtooth waves between them, or at intervals of < 3 minutes  (SsFigures 10a, 10b, 10c, and 10d).
- Transition to Stage Wake  (SsFigures 9b and 9c).
- Sustained, increased EMG  (SsFigures 11a, 11b, 11c, and 11d).

<u>When K complexes or unquestionable sleep spindles are seen in the Stage REM:</u>

An isolated K complex may be seen in REM. When K complexes or unquestionable sleep spindles (as compared to Stage 2) are present in stage REM, then an interval between two K complexes or sleep spindles is scored as Stage 2 only if there are no REMs (eye movements) or sawtooth waves in this interval and it is less than 3 min. long. Otherwise the interval is scored as Stage REM  (SsFigure 7f).

<u>Scoring REM when there are problems with REM related atonia or the EMG is difficult to interpret.</u>

Identification of the Stage REM is may be difficult when there are prolonged bursts of elevated EMG seen during eye movements or the EMG increases with snoring. In such cases:

- EMG increases clearly related to snoring (changing with breathing) may be ignored, as long as intervening EMG is low  (SsFigure 12a).
- The portion of the record with unquestionable Stage REM should be reviewed to provide a visual reference of the characteristic Stage REM EEG pattern. Stage REM is scored when EEG pattern changes to the pattern characteristic for Stage REM regardless of the level of the EMG  (SsFigures 12b and 12c).  When EEG is consistent with Stage REM, and there is no evidence of wake (blinking), no  evidence of Stage 1 (vertex waves, slow rolling eye movements), or the presence of REMs, then score stage Stage REM from the last K complex, sleep spindles or delta wave. Distinguishing between Stage 1 and Stage REM is unreliable and noted as such on the PSG scoring notes form.

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.7 Scoring respiratory events

SHHS will identify the following categories of discrete breathing events: obstructive apneas, central apneas, and hypopneas. Additionally, periodic breathing and periodic large breaths will be identified. No attempt will be made to distinguish mixed apneas from obstructive apneas. This decision was based on previous data that indicated mixed events cannot be reliably identified.  Central hypopneas and increased upper airway resistance (RERAs) will not be identified because of controversies in the defining these events and the probable need to use invasive monitoring to identify these accurately  (ResFigures 1a, 1b, 1c, and 1d).

**<u>Obstructive Apneas</u>** are identified when the amplitude (peak to trough) of the airflow signal decreases to a flat or almost flat signal (showing a 75% reduction of the amplitude of “baseline” breathing) if this change lasts for > 10 s. Baseline breathing is defined as a period of regular breathing with stable oxygen levels  (ResFigures 2a, 2b, 2c, and 2d).

**<u>Hypopneas</u>** are identified if the amplitude of the any respiratory signal is reduced by 30% of the amplitude of “baseline” (identified during a period of regular breathing with stable oxygen levels), if this change lasts for > 10 s and for >2 breaths  (ResFigures 3a and 3b).   Sometimes more subtle changes in breathing are observed (not clearly reduced by 30% or more from baseline).  These require at least a 2% desaturation  (ResFigure 3c).

- <u>Distinguishing Between Hypopneas and Apneas.</u> This distinction only can be made for events in which airflow is interpretable. (If airflow is uninterpretable, the event-based on inductance data is considered by default to be a hypopnea.)  (ResFigure 4a).   Apneas are marked if > 50% of the event shows absent or nearly absent airflow on the thermister channel (and this reduction is 75% the amplitude of the surrounding breaths). (ResFigures 4b and 4c)
- <u>Variation in signal amplitude on airflow, thoracic and abdominal channels:</u> In some studies, information appears qualitatively different from different channels. Scoring will be done from the channel that correlates the best with the changes in the oxygen saturation  (ResFigure 4d).  If there are no changes in O2 saturation, scoring will be done from the channel that shows the clearest amplitude variation  (ResFigure 4e).  In cases where the thermister varies from the inductance channels, and the inductance channels appear mostly artifact free, the inductance channels will be used for event identification and classification  (ResFigure 3b, 4f).  For example, sometimes the airflow channels will suggest prolonged periods of  “no flow”, but changes in inductance and oxygen saturation suggest that breathing is occurring.  When in doubt, use data from the inductance and saturation channels to identify/classify events.

A **<u>Central apnea event</u>** is scored if NO displacement is noted on both chest and the abdominal inductance channels  (ResFigures 5a and 5b).  Otherwise, events are noted as “obstructive.”

- <u>Distinguishing Between Central and Obstructive Events.</u> Only events in which there is clear data from both the abdominal and chest signals can be distinguished as “central” or “obstructive”. (Events where one or both of these channels are missing or contain artifact are considered “obstructive.”)  (ResFigure 5c).

- Often determining whether an event is central or obstructive is influenced by where the event is noted to begin and end. Sometimes, small efforts are seen following a completely flat area, followed by a large (”breaking”) breath. If a single small breath is seen at the beginning or the end of the period of flat signal, the event will be marked as “central.” (This recognizes that shortening the event slightly would make it a central event)  (ResFigure 6a).   However, if 2 or more consecutive small breaths are seen in the period in question, the event is marked as “obstructive.”  Many of these events would be noted as “mixed” by non-SHHS scorers  (ResFigures 6b and 6c).

- Determining whether an event is central or obstructive in areas of periodic breathing can be difficult because of uncertainties in deciding when to start and end such events. Often, these areas contain breaths that gradually increase and decrease, sometimes decreasing to an imperceptible level. Marking “longer” events in these areas would result in identifying “obstructive” events; “shorter” events are more likely to appear “central.” When it is unclear as to when to start an event, look for evidence of paradoxical breathing.  Change in phase angle between thoracic and abdomen is an indicator of upper airway obstruction (such events will be designated as obstructive)  (ResFigure 6d).  When still unclear, the event duration will be marked using the airflow channel. Identify the areas where airflow stops and starts, then assess whether the period is also associated with effort on either channel/band.   Then, the inductance channels will be visualized to decide whether during this period, any effort occurred. If any effort was visualized, the event will be considered “obstructive”, otherwise, “central.”  (ResFigures 6e, 6f, and 6g).

<u>Duration criteria:</u> The beginning of an Apnea/Hypopnea is marked at the end of the last “normal” breath; the end of the event is identified as the beginning of the first breath that exceeds the amplitude of the first reduced breath used to mark the beginning of the event. Duration is based on a “trough to trough” marking  (ResFigures 6h, 6i, and 6j).

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

#### 6.2.8 Dealing with ambiguous respiratory events:

<u>If changes in amplitude are reduced by < 30%,</u> but a ≥ 10 s. period of a clearly discernible reduction in the amplitude of respiratory signals from baseline is observed, then score events when:

- they occur as part of a series of events (that do meet the 30% reduction criteria) (ResFigures 7a, 7n, and 7o).
- they are associated with desaturations of at least 2% (ResFigures 7b, 7m, 7p).

<u>Apneas/hypopneas immediately following large breaths or movements</u> are not scored, unless they are part of the cycle (there are other respiratory events before and following). Such isolated events may be “sighs” or artifact  (ResFigures 7c).   When such an event is noted after a movement/large breath and appears to “trigger” a series of events, the first respiratory event is not scored (unless apneas/hypopneas were scored before the movement/large breath)  (ResFigure 7d and 7e).

<u>Determining whether to score one long event or two short events</u> (i.e., after an initial decrease in amplitude of a breathing signal, there is some increase, but not to baseline, and then a fall again): In these cases, the oxygen saturation channel will be checked to determine whether one or more than one event should be marked.  If the event is punctuated by a clear decrease in oxygen saturation followed by a rise or a stabilization, and then a decrease again, two events are marked; otherwise if the event is characterized by one steady progressive fall in desaturation, than one event is scored  (ResFigure 7f, 7g, 7h, 7i, and 7j).

<u>Periods of hyperventilation followed by long periods of hypoventilation:</u> If periods of hypoventilation have clearly visible beginnings and endings (i.e., are “discrete”) and are associated with at least 2% desaturation, score as hypopneas regardless of their length (they can last up to a few min.). (Note: This is commonly observed in REM.)  (ResFigure 7k and 7l).


<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
<div class="btn-group">
  <a href=":datasets_path:/shhs/pages/mop/6-50-mop-data-processing.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    5. Data Processing
  </a>

  <a href=":datasets_path:/shhs/pages/mop/6-00-mop-toc.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Table of Contents
  </a>

  <a href=":datasets_path:/shhs/pages/mop/6-70-mop-qs-form-scoring-notes.md" class="btn btn-success">
    7. QS Form - Scoring Notes
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
