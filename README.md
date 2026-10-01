# Contact-Microphone Tidal Volume Estimation — Bench Validation Data

Data and calibration coefficients supporting the manuscript:

**"A Contact-Microphone-Based Non-Invasive Tidal Volume Estimation Framework: Bench Validation on a Mechanical Lung Model"**

## Contents

| File | Description |
|---|---|
| `conditions.csv` | Per-condition bench data for 17 analyzable conditions: ventilator VT/RR settings, reference expired tidal volume (VTe), median envelope amplitude, breath counts, measured respiratory rate, coefficient of variation, attachment period |
| `calibration_coefficients.csv` | Log–log flow-model calibration coefficients (Models A and B, by attachment period) and sensitivity analysis (post-attachment settling excluded) |
| `results_summary.csv` | Bland–Altman agreement (bias, SD, limits of agreement), MAPE, and Pearson r for the primary and sensitivity analyses |

## Experimental Setup

A MEMS contact microphone (INMP441) was attached over the rubber neck of a mechanical test lung (Dräger SelfTestLung) ventilated in volume-controlled mode by an anesthesia machine (Dräger Primus) across 18 randomized VT/RR combinations (200–800 mL, 10–20 /min, I:E 1:2). The envelope was computed on an ESP32-S3 (20 Hz RMS) and logged continuously for 77.2 minutes with zero data gaps.

## Provenance

All values are derived from the timestamped acquisition logs recorded during the bench session. One condition (condition 6) was excluded due to a protocol transcription deviation, as documented in the manuscript.

## License

Data and scripts are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Status

Raw audio logs and full analysis scripts will be added upon manuscript acceptance.
