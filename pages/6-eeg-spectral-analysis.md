# EEG Spectral Analysis

*Note:* For EEG spectral analysis inquiries, please visit the [NSRR Forum](https://sleepdata.org/forum).

Sleep is a complex dynamic process often quantified through spectral analysis of the electroencephalogram (EEG). Quantitative EEG (qEEG) analysis has been shown to be associated with wake period length, brain state, memory consolidation, cognitive development and decline, and psychological states. NREM and REM are two distinct sleep states that progress from lighter to deeper sleep. NREM and REM states cycle throughout the night with the distribution of NREM/REM states changing across the night. Sleep complexity as well as the complexity of the association of sleep with psychological/behavioral states suggesting the need for methods such as spectral analysis for quantifying EEG dynamics. Spectral analysis of the EEG signal was proposed early in the study of EEG analysis and continues to be a commonly used approached to analyze EEG signals. Spectral analysis transforms the EEG times-series into a compact representation that is defined as a sum of sinusoidal signals with different frequencies.

## Current Approaches

The current gold standard approach to applying spectral analysis to EEG studies involves manual identification and removal of EEG artifacts prior to performing spectral analysis. Commercial software tools for manually identifying artifacts and performing spectral analysis are commonly provided as part of an EEG data collection system or can be purchased as a standalone software product. Our estimates for performing spectral analysis with manual artifact detection by the gold standard approach range between 1 and 2 hours per lead in each study. Although commercial software tools provide a turnkey solution for analyzing small numbers of sleep studies, the cost of manual artifact detection can become prohibitive when epidemiological scale (thousands of studies) of spectral analysis is required.

## NSRR Approach

In order to the address the need for a computationally efficient spectral analysis program an analysis pipeline was developed that includes integrated artifact detection, provides a wide range of spectral parameters, and can automatically create spectral reports and figures. The objective of the spectral analysis project was to reduce the effort required to perform spectral analysis on scored PSG (polysomnogram) data by automating artifact detection, spectral analysis and results reporting with the final goal of allowing sleep researchers to efficiently analyze their own datasets. For this purpose [SpectralTrainFig](https://github.com/DennisDean/SpectralTrainFig) and [BlockEdfSummarizeFig](https://github.com/DennisDean/BlockEdfSummarizeFig) were developed at Brigham and Women's Hospital and validated as part of a configurable, computationally efficient and open source artifact detection and spectral analysis pipeline.

## Automated Artifact Detection and Spectral Analysis

EEG spectral analysis was applied according to published automated artifact detection (Buckelmuller at al.) and spectral analyses (Aeschbach et al.) methods for EEG data collected during sleep. Results from previous manual scoring of the SOF dataset (the "gold standard") were compared to results from automatic artifact detection of the SOF data generated using various artifact rejection thresholds to establish settings that coincided most with "gold standard" results. Agreement of these results was not based on identifying the same epochs as artifact, or the same number of artifacts, but rather overall spectral power results for Sleep, REM and NREM.

## Validation Methods and Results

Description of the SpectralTrainFig validation will be made available when the validation manuscript has been published.

## Limitations

Limitations to the application of SpectralTrainFig to data include inherent challenges associated with automated and large scale analysis, residual artifacts, the need for additional post processing tools, and the need for further validation studies. The complexity and time required to adjudicate, review and analyze results grows quickly as the number of analyzed studies. Additional post analysis tools are required and should be modeled after earlier efforts for analyzing large number of signals. We have presented a validation study with a population of older women that includes a large number of women with mild cognitive impairment and dementia. Additional validation studies with different populations, with different spectral parameters/methods and with different artifact detection parameters are required to better understand how the current analysis pipeline performs in relation to the spectral studies analyzed with manual artifact detection. We did not perform spectral studies with simulated data due to the lack of open source tools for simulating EEG signals during sleep. Studying the effect of spectral methods and parameters with simulated data could results in specific recommendations for setting spectral parameters for studying EEG dynamics that occur during sleep. There is a similar need to understand how different approaches to computing EEG spectral properties during sleep may affect physiological inference.

## Dataset Structure

[Two result datasets](:files_path:/datasets) have been posted for EEG spectral analysis.

- Datasets are keyed on `PDRID` and `signal`, e.g. Participant ID 123 and Signal C3.
- The `spectral-summary` dataset includes power density summarized in different frequency bins, broken down by NREM and REM sleep
- The `band-summary` dataset includes power density summarized by frequency bands (e.g. Delta, Theta), broken down by NREM and REM sleep

## References

1. Aeschbach, D., Lockyer, B. J., Dijk, D.-J. et al. Use of Transdermal Melatonin Delivery to Improve Sleep Maintenance During Daytime. Nature, 2000, 10: 378-82.
2. Buckelmuller J, Landolt H-P, Stassen HH, Acherman P. Trait-like individual differences in the human sleep electroencephlogram. Neuroscience 2006;351-356:351-6
3. Dean II DA, Goldberger AL, Mueller R, et al. Scaling up scientific discovery in sleep medicine: The National Sleep Research Resource. In. Boston, MA: (in Preparation), 2015:1-14.
4. Dean II DA, Tarokh L, Donlagic I, et al. Scaling up EEG spectral analysis while maintaining gold standard agreeement: The National Sleep Research Resource. (In Preparation), 2015:28.
5. [https://github.com/DennisDean/SpectralTrainFig/blob/master/README.md](https://github.com/DennisDean/SpectralTrainFig/blob/master/README.md)
