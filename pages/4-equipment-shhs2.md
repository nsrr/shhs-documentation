# Technical Notes on SHHS2

Compumedics P-series Sleep Monitoring system, version 3, as used for SHHS1 some units were new, version 4. The system consisted of a main unit that held a flashcard (20 MB), interfaced to an oximeter as well as to a Patient Interface Box (PIB) in to which electrode ends were attached via Harwin connectors. The PIB had 6 switch banks with toggle switches which would control the amplifiers (on/off). An analog cable connected the PIB to the main unit. The unit was powered by a rechargeable Nickel Metal Hydride battery (typically). After the collection the study would be downloaded to computer via serial lead, Battery recharged and flashcard reformatted.

The SHHS1 units were all re-conditioned before SHHS2 by Compumedics which included updates to the PIB design.  Sites performed monthly calibration checks.   A loaner pool for SHHS2 sites was established by Compumedics for equipment sent for repairs.  The Compumedics software used to score the sleep studies was also updated from the DOS Replay system to a Windows based version of Replay.

The P- series was not a truly digital system, the EEG inputs were hardwired into the amplifier interface and called EEG (C4-A1) and EEG2 (C3-A2) instead of all being collected to a common reference. These signals were collected without additional filtering but the high-pass hardware filters for the instrument were 0.15 Hz for EEG, EOG, EMG and ECG channels and 0.05 Hz for all respiratory signals. For SHHS1 the sampling rate for EEG and ECG was set to 128 Hz but the sampling rate for ECG (only) was bumped up to 250 Hz for the SHHS2 collection, EEGs and EMG maintained sampling at 128, EOGs were sampled at 64, Respiratory signals were sampled at 8, Position, light and oximetry were sampled at 1Hz.

## EEG surface electrodes
Grass brand gold disk surface electrodes were used for GND, REF, EOGs, Chin EMG, A1,A2, centrals, and ECG. GND was placed at Cz, REF was on mid-forehead. ECG: 2 leads placed R subclavicle-L lower rib. Occasional modesty issues necessitated altering placement to right subclavicle- left subclavicle.

## Oximeter
Nonin XPOD Model 3011, proprietary attachment to recording unit. Finger sensor 8000J. Some sites employed re-usable sensors with flexi-fit sensor covers, some sites (Tucson) used disposable finger sensors. Both sensors had identical circuitry boards.

## Thermistry
ProTech  thermister M325.  This thermocouple  used the "auxiliary" channel as designated on the PIB (Channel 17)

## Effort Belts
Belts for SHHS2 were the same as used for SHHS1: White Respitrace Inductance Plethysmography; there was no SUM signal generation. Respitrace no longer produced the belts so Compumedics refurbished the original bands used in SHHS1, and continued to provide repair service when needed.

## Nasal Pressure
No Nasal Pressure in SHHS2

## Capnography
No Capnography in SHHS2

## Light sensor
There was a Compumedics external light sensor interfaced to the PIB. The hook-up tech would calibrate this sensor in the home to ambient room light and darkness to collect a signal for lights off. This was not always reliable.

## Leg EMG
No leg EMG sensors for SHHS2. Limiting possible injury to participants was desired since some participants were prepped outside of the home (clinic or medical trailer) hours prior to bedtime.

## Position
External Compumedics position sensor with 4 positions.

## Snore
Sound channel not used.

## Other
The participant wore a vest on the torso with the recording unit placed in the center pocket.

## Montage and Sampling Rate Information [on SHHS2]

The settings below represent the standards set at the beginning of the project. There may be a small proportion of studies and signals that do not match these standards exactly. Please review the settings at the individual sleep study level as you proceed with any analyses.

<b>SHHS2v3</b>

|  Channel  |   Channel Derivation  |  Sampling Rate (Hz)  |  Hardware Filters (Hz)  |              Sensor Type                 |
|:---------:|:---------------------:|:--------------------:|:-----------------------:|:----------------------------------------:|
| SaO2      |                       |    1                 |                         | Nonin XPOD 3011, 8000 sensor             |
| PR        |                       |    1                 |                         | Nonin XPOD 3011, 8000 sensor             |
| EEG (sec) | C3/A2                 |  125                 |  High pass 0.15         | Gold cup electrode                       |
| ECG       | ECG1/ECG2             |  250                 |  High pass 0.15         | Ag/AgCl patch                            |
| EMG       | EMG1/EMG2             |  125                 |  High pass 0.15         | Gold cup electrode                       |
| EOG(L)    | EOG(L)/PG1            |   50                 |  High pass 0.15         | Gold cup electrode                       |
| EOG(R)    | EOG(R)/PG1            |   50                 |  High pass 0.15         | Gold cup electrode                       |
| EEG       | C4/A1                 |  125                 |  High pass 0.15         | Gold cup electrode                       |
| Airflow   |                       |   10                 |  High pass 0.05         | Compumedics thermistor                   |
| Thor RES  |                       |   10                 |  High pass 0.05         | Respitrace Inductance Plethysmography    |
| Abdo RES  |                       |   10                 |  High pass 0.05         | Respitrace Inducatnce Plethysmography    |
| Position  |                       |    1                 |                         | Compumedics external sensor              |
| Light     |                       |    1                 |                         | External ambient light sensor            |
| OX STAT   |                       |    1                 |                         | Nonin XPOD 3011, 8000 sensor             |

<b>SHHS2v4</b>

|  Channel  |   Channel Derivation  |  Sampling Rate (Hz)  |  Hardware Filters (Hz)  |              Sensor Type                 |
|:---------:|:----------------------|:--------------------:|:-----------------------:|:----------------------------------------:|
| SaO2      |                       |    1                 |                         | Nonin XPOD 3011, 8000 sensor             |
| PR        |                       |    1                 |                         | Nonin XPOD 3011, 8000 sensor             |
| EEG (sec) | C3/A2                 |  128                 |  High pass 0.15         | Gold cup electrode                       |
| ECG       | ECG1/ECG2             |  256                 |  High pass 0.15         | Ag/AgCl patch                            |
| EMG       | EMG1/EMG2             |  128                 |  High pass 0.15         | Gold cup electrode                       |
| EOG(L)    | EOG(L)/PG1            |   64                 |  High pass 0.15         | Gold cup electrode                       |
| EOG(R)    | EOG(R)/PG1            |   64                 |  High pass 0.15         | Gold cup electrode                       |
| EEG       | C4/A1                 |  128                 |  High pass 0.15         | Gold cup electrode                       |
| Airflow   |                       |    8                 |  High pass 0.05         | Compumedics thermistor                   |
| Thor RES  |                       |    8                 |  High pass 0.05         | Respitrace Inductance Plethysmography    |
| Abdo RES  |                       |    8                 |  High pass 0.05         | Respitrace Inductance Plethysmography    |
| Position  |                       |    1                 |                         | Compumedics external sensor              |
| Light     |                       |    1                 |                         | External ambient light sensor            |
| OX STAT   |                       |    1                 |                         | Nonin XPOD 3011, 8000 sensor             |


<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
<div class="btn-group">
  <a href=":pages_path:/4-equipment-shhs1.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    Technical Notes on SHHS1
  </a>

  <a href=":pages_path:/mop/6-00-mop-toc.md" class="btn btn-success">
    Manual of Operations
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
