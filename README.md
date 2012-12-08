# wellcome-trust-hackathon

Visualisation of Intensive Care Unit flowsheet data at http://physionet.org/challenge/2012/

**Series** in 8 colours: #RGB
RG = redish for death in hospital greenish for survival (in [Outcomes-a.txt](http://physionet.org/challenge/2012/Outcomes-a.txt))
other hues/saturations = for ICU type:
1=Coronary (blood circulation)
2=Cardiac (heart muscle)
3=Medical
4=Surgery

**t-axis**: cadence 1m, 30m, 1h or 4h - so progress at 1m steps
**x-axis**: NIMAP
**y-axis**: HR
**z-axis** (bubble radius): Temp


Variables recorded:
* HR = heart bpm
* NIDiasABP = diastolic BP
* NIMAP = mean BP
* NISysABP = systolic BP
* RespRate = respiration bpm
* Temp = deg C
* Urine = mL output