# Polysomnography introduction

Data collection for PSG was standardized among various manufactured instruments by use of standardized collection and display montages. Each unit used for collection was certified before use to maximize signal quality integrity throughout the EDF conversion and import into Compumedics Profusion software used for scoring.

Notes:

- [Montage and Sampling Rate Information on SHHS1](:pages_path:/5-montage-and-sampling-rate-information-shhs1.md)
- [Montage and Sampling Rate Information on SHHS2](:pages_path:/5-montage-and-sampling-rate-information-shhs2.md)
- [Sleep Reading Center Manual of Operations](:pages_path:/mop/6-00-mop-toc.md)

## Signal and annotation files

[Raw polysomnography data](:files_path:/) is available for 5,793 subjects at SHHS Visit 1 and 2,651 subjects at SHHS Visit 2. Each recording has a signal file (.EDF) and two versions of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from Compumedics Profusion.
2. **[XML (Profusion)](:files_path:/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion. ([Learn more...](https://www.sleepdata.org/tools/edf-editor-and-translator/pages/2-11-compumedics-format.md))
3. **[XML (NSRR)](:files_path:/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/tools/edf-editor-and-translator) tool.

## Known issues

- *Oxygen saturation value reaches 101 (300051 baseline) in sleep* - These extraneous values stem back from the original recording equipment and could not be fixed upon re-exporting. ([See list of studies with values >100 in wake.](:pages_path:/polysomnography-sao2-exceeds-100.md))
- *Referenced signals (300051 baseline) and bipolar collection (300927 baseline)* - Original data collection did not conform to official CHAT montage.
- *Pulse signal contains incorrect physical dimension (mbar) (301117 nonrandomized)* - Issue could not be fixed with re-exporting; other signals appear intact.

## History / changelog

*June 2014*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
