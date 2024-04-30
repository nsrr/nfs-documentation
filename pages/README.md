## About

The Need for Sleep Study (NFS) was a National Medical Research Council, Singapore National Research Foundation, Singapore and Far East Organization sponsored study that relied on a parallel group design which analyzed the effects of sleep restriction (7 nights of 5 hour time in bed [TIB]) on cognitive performance, subjective sleepiness, and mood in healthy 15-19 year adolescents. This study was conducted from 2010-2019 and included polysomnography data collection and actigraphy collection.

The NFS dataset includes 4 protocols. All the protocols were conducted during the 15-day school vacation period. The NFS1 and NFS2 protocols were conducted from 2014 to 2015. NFS4 was conducted during the vacation period of 2017, and NFS5 was conducted during the same period in 2019. All protocols had similar participant counts: NFS1 had 60 participants, NFS2 had 57 participants, NFS4 had 58 participants, and NFS5 had 59 participants. During these 15-day study periods, a series of experimental studies aimed at characterizing adolescents’ cognitive functions under different sleep manipulations were conducted.

Alongside the experimental studies, raw polysomnography data was collected. Raw PSG data was collected using a SOMNOtouch recorder (SOMNOmedics GmbH, Randersacker, Germany) from two channels (C3 and C4 in the international 10–20 system).

## Methods

### Two-Week Study Protocol

One week prior to the study, participants were required to adhere to a sleep-wake schedule that provided a 9 hour nocturnal sleep opportunity (23:00–08:00). This was verified using wrist-worn actigraphy and was intended for circadian entrainment and for minimizing any effect of prior sleep restriction (SR) on sleep and cognitive performance.

The two-week study protocol was conducted from 2014-2019 in a boarding school after the school year had ended. In the first 3 nights (B1–B3), both SR and control participants had a 9 hour nocturnal sleep opportunity (23:00–08:00) for adaptation and baseline characterization purposes. This was followed by a 7 night manipulation period (M1–M7) in which the SR group had 5 hour (01:00–06:00) and the control group had 9 hour (23:00–08:00) sleep opportunities. The protocol ended with 3 nights of 9 hour recovery sleep (R1–R3: 23:00–08:00) for both groups.

### PSG Collection

Electroencephalography (EEG) was performed using a SOMNOtouch recorder (SOMNOmedics GmbH, Randersacker, Germany) from two channels (C3 and C4 in the international 10–20 system) referenced to the contralateral mastoids. The common ground and reference electrodes were placed at Cz and FPz. Electrooculography (EOG) and submental electromyography (EMG) were also used. Impedance was kept below 5 kΩ for EEG electrodes and below 10 kΩ for EOG and EMG electrodes. Signals were sampled at 256 Hz and filtered between 0.2 and 35 Hz for EEG and between 0.2 and 10 Hz for EOG.

### PSG Scoring

Trained technicians visually scored the sleep data, following criteria set by the American Academy of Sleep Medicine Manual for the Scoring of Sleep and Associated Events. PSG scoring analyses of EDF files were performed using the FASST toolbox (http://www.montefiore.ulg.ac.be/~phillips/FASST.html). EEG signals were band-pass filtered between 0.2 and 25 Hz. Scoring was performed visually by trained technicians following the criteria set by the American Academy of Sleep Medicine Manual for the Scoring of Sleep and Associated Events (2007).

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team.

## Data overview

### Covariate/phenotype datasets (CSV)

The covariate dataset files (nfs-dataset-0.1.0.csv and nfs-harmonized-dataset-0.1.0.csv) contain 110 rows each. The first column (subj_id) is the unique NFS subject identifier that can be linked with PSG signal filenames. 

The dataset columns are described in the accompanying data dictionary files. The variables data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated "domain" (e.g., 1=Male, 0=Female), which are described in the domains data dictionary file. 

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/nfs-data-dictionary). 

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets. Key variables include:

-	nsrr_sex – Subject sex
-	nsrr_age – Subject age
-	nsrr_bmi – Body mass index (BMI)

### Polysomnography

Raw signal data are shared as EDF files using the European Data Format (https://www.edfplus.info/). 

## Access and usage restrictions

The NFS dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Lo JC, Ong JL, Leong RL, Gooley JJ, Chee MW. Cognitive Performance, Sleepiness, and Mood in Partially Sleep Deprived Adolescents: The Need for Sleep Study. Sleep. 2016 Mar 1;39(3):687-98. doi: 10.5665/sleep.5552. PMID: 26612392; PMCID: PMC4763363.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4763363/)
>
>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

Users must include the following text in any Acknowledgements:

> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*May 2024*

- Make NFS dataset available for data requests

## References

- NFS GitHub Documentation: https://github.com/nsrr/nfs-documentation
- NFS GitHub Data Dictionary: https://github.com/nsrr/nfs-data-dictionary

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
