# HRV Analysis Overview

*Note:* For inquiries, please visit the [NSRR Forum](https://sleepdata.org/forum).

## Methods

As part of the polysomnographic study, continuous electrocardiographic (ECG) signals were recorded at the following sample frequencies: 125 Hz (500 SHHS1 studies); 250 Hz (474 SHHS2 studies); 256 Hz (26 SHHS2 studies). A Notch filter of 60Hz was applied.

QRS complexes (R-points) were detected using Compumedics (Abbotsford, VIC, Australia) Somte software Version 2.10 (Builds 99 to 101). The R-points were classified as normal sinus, supraventricular premature complex or ventricular premature complex. The automated annotations were reviewed by a trained technician, who made appropriate corrections.

In this analysis, we follow the Task Force of The European Society of Cardiology and The North American Society of Pacing and Electrophysiology, Heart rate variability (HRV) standards of measurement, physiological interpretation, and clinical use (European Heart Journal, 1996;17:354–81).

Traditional heart rate variability (HRV) measures are commonly divided into two broad categories: time domain measures and frequency domain measures.

The time domain HRV statistics include the following measures:

- **AVNN** (the average of all the NN intervals)
- **IHR** (Mean value of instantaneous heart rate. For a given NN interval, the IHR is calculated as 60/NN. IHR is usually expressed as beats per minute but strictly speaking it is unitless.)
- **SDNN** (the standard deviation of all NN intervals)
- **SDANN** (the standard deviation of the averages of NN intervals in all 5-minute segments)
- **SDNNINDX** (the mean of the standard deviations of NN intervals in all 5-minute segments)
- **rMSSD** (the square root of the mean of the squares of difference between adjacent NN intervals), and
- **pNNx** (the percentage of differences between adjacent NN intervals that are > x ms). We used x = 10, 20, 30, 40 and 50 ms.

The frequency domain measures include:

- **TOTPWR** (total NN interval spectral power up to 0.4 Hz),
- **ULF** (ultra-low frequency power: the NN interval spectral power between 0 and 0.003 Hz of a 24-hour recording),
- **VLF** (very low frequency power: the NN interval spectral power between 0.003 and 0.04 Hz),
- **LF** (low frequency power: the NN interval spectral power between 0.04 and 0.15 Hz),
- **HF** (high frequency power: the NN interval spectral power between 0.15 and 0.4 Hz) and the
- **LF/HF ratio** (the ratio of low to high frequency power).

Traditionally frequency domain measures are calculated by resampling the original NN interval series and then applying the fast Fourier transform. This resampling, however, can cause an attenuation in the high frequency components. To eliminate the need for evenly sampled data required by the standard Fourier Transform, frequency domain spectra can be calculated using the Lomb periodogram for unevenly sampled data.

Although the long term (24-hour) statistics of SDANN, SDNNIDX and ULF power can be calculated for shorter data lengths they will become increasingly unreliable. For short term data (less than 15 minutes in length) only the time domain measures of AVNN, SDNN, rMSSD and pNN10, pNN20, pNN30, pNN40 and pNN50,  and the frequency domain measures of total power, VLF power, LF power, HF power and LF/HF ratio are computed.

## Sub-analyses

A set of 500 SHHS subjects with data at both visits and high quality ECG data were selected to serve as the basis of this analysis. HRV results are available for most subjects at both timepoints (SHHS1 and SHHS2).

1. `summary` (Entire night) - Analysis is performed from sleep onset to sleep termination. This analysis requires the following information: the time of occurrence of each R-wave, and the sleep onset and termination times. These times were extracted from the file containing the sleep stage annotations as the first and last 30 sec episode of stage 1, 2, 3 or 5 (REM), respectively. RR intervals larger than 2.5 seconds were excluded from the analysis.

2. `5min` (HRV of consecutive 5-min segments with no overlap) - The results of this analysis were used to quantify HRV by sleep stage with and without respiratory events.  In addition to restricting the analysis to RR intervals <2.5 s, only 5-min windows with at least 150 normal sinus beats were analyzed.

## Notes on excluded data

_SHHS1_: There were 14 cases with less than 5000 NN intervals for the full night, which were excluded.

_SHHS2_: There were 5 cases without any NN intervals (200858, 201622, 202164, 203329 and 204375 -- likely atrial fibrillation) that were excluded. In addition, two other cases with less than 50% NNs during sleep time (200139 and 201315) were excluded.

## Dataset Structure

[Result datasets](:files_path:/datasets/hrv-analysis) have been posted for HRV analysis. Datasets are keyed on `nsrrid`.

## R-point annotations

[Individual CSV files are available with R-points](:files_path:/polysomnography/annotations-rpoints) for each heartbeat. These annotations were reviewed by a trained technician after exporting from the Compumedics Somte software. ECG was sampled at 125 Hz in SHHS1 and 250/256 Hz in SHHS2. The Somte software outputs sampling numbers assuming 256 Hz, however the `rpointadj` column has been added to provide an adjusted sample number based on the actual sampling rate of the recording of interest.

| Name                      | Label (with Units / Notes)                                                                                                                                                            |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <nobr>`RPoint`</nobr>     | Sample Number indicating R Point (peak of QRS)                                                                                                                                        |
| <nobr>`Start`</nobr>      | Sample Number indicating start of beat                                                                                                                                                |
| <nobr>`End`</nobr>        | Sample Number indicating end of beat                                                                                                                                                  |
| <nobr>`STLevel1`</nobr>   | Level of ECG 1 in Raw data ( 65536 peak to peak rawdata = 10mV peak to peak)                                                                                                          |
| <nobr>`STSlope1`</nobr>   | Slope of ECG 1 stored as and int to convert to a double divide raw value by 1000.0                                                                                                    |
| <nobr>`STLevel2`</nobr>   | Level of ECG 2 in Raw data ( 65536 peak to peak rawdata = 10mV peak to peak)                                                                                                          |
| <nobr>`STSlope2`</nobr>   | Slope of ECG 2 stored as and int to convert to a double divide raw value by 1000.0                                                                                                    |
| <nobr>`Manual`</nobr>     | (True / False) True if record was manually inserted                                                                                                                                   |
| <nobr>`Type`</nobr>       | Type of beat (0 = Artifact / 1 = Normal Sinus Beat / 2 = VE / 3 = SVE)                                                                                                                |
| <nobr>`Class`</nobr>      | This Field is no longer used                                                                                                                                                          |
| <nobr>`PPoint`</nobr>     | Sample Number indicating peak of the P wave (-1 if no P wave detected)                                                                                                                |
| <nobr>`PStart`</nobr>     | Sample Number indicating start of the P wave                                                                                                                                          |
| <nobr>`PEnd`</nobr>       | Sample Number indicating end of the P wave                                                                                                                                            |
| <nobr>`TPoint`</nobr>     | Sample Number indicating peak of the T wave (-1 if no T wave detected)                                                                                                                |
| <nobr>`TStart`</nobr>     | Sample Number indicating start of the T wave                                                                                                                                          |
| <nobr>`TEnd`</nobr>       | Sample Number indicating end of the T wave                                                                                                                                            |
| <nobr>`TemplateID`</nobr> | The ID of the template to which this beat has been assigned (-1 if not assigned to a template)                                                                                        |
| <nobr>`nsrrid`</nobr>     | NSRR Subject Identifier                                                                                                                                                               |
| <nobr>`samplingrate`</nobr> | ECG Sampling Rate (Hz)                                                                                                                                                              |
| <nobr>`seconds`</nobr>    | Number of seconds from beginning of recording to R-point (RPoint / 256)                                                                                               |
| <nobr>`epoch`</nobr>      | Epoch (30 second) number                                                                                                                                                              |
| <nobr>`rpointadj`</nobr>  | R Point adjusted sample number (RPoint * (samplingrate/256))                                                                                                                          |

## References

The open source code used for this analysis along with a tutorial on its use is available at the NIH-sponsored Research Resource for Complex Physiologic Signals: http://physionet.org/tutorials/hrv-toolkit/
