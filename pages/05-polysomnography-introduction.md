# Polysomnography introduction

Data collection for PSG was standardized among various manufactured instruments by use of standardized collection and display montages. Each unit used for collection was certified before use to maximize signal quality integrity throughout the EDF conversion and import into Compumedics Profusion software used for scoring.

Notes:

- [Montage and Sampling Rate Information on SHHS1](:pages_path:/10-montage-and-sampling-rate-information-shhs1.md)
- [Montage and Sampling Rate Information on SHHS2](:pages_path:/11-montage-and-sampling-rate-information-shhs2.md)
- [Sleep Reading Center Manual of Operations](:pages_path:/mop/6-00-mop-toc.md)

## Signal and annotation files

[Raw polysomnography data](:files_path:/polysomnography) are available for 5,793 subjects at SHHS Visit 1 and 2,651 subjects at SHHS Visit 2. Each recording has a signal file (.EDF) and two versions of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from Compumedics Profusion.
2. **[XML (Profusion)](:files_path:/polysomnography/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion. ([Learn more...](https://github.com/nsrr/edf-editor-translator/wiki/Compumedics-Annotation-Format))
3. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/community/tools/12) tool.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://github.com/nsrr/edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

## Known issues

- Annotation file event counts may not always directly match the [core datasets](:files_path:/datasets). SHHS data are more than 15 years old and there may have been conversion issues in a limited number of cases.
- Oxygen desaturation events from the annotation files may be absent and/or may not line up as anticipated with respiratory events. Original scoring data were indelibly changed when converting to a newer version of the scoring software that allowed for the creation of EDF/XML files. Users may opt to derive new desaturation events from the SaO2 signal.

## History / changelog

*December 2016*
- Change EDF recording dates from "00.00.00" (invalid) to "01.01.85" (valid de-identified date)

*June 2014*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
