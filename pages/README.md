## About

The [Need For Sleep (NFS) study](https://www.needforsleep.org/) was a National Medical Research Council, Singapore National Research Foundation, Singapore and Far East Organization sponsored study that relied on a parallel group design which analyzed the effects of sleep restriction (7 nights of 5 hour time in bed [TIB]) on cognitive performance, subjective sleepiness, and mood in healthy 15-19 year-old adolescents. This study was conducted from 2010-2019 and included polysomnography, actigraphy, and questionnaire data collection.

The NFS dataset includes 4 protocols. All the protocols were conducted during the 15-day school vacation period. The NFS1 and NFS2 protocols were conducted from 2014 to 2015. NFS4 was conducted during the vacation period of 2017, and NFS5 was conducted during the same period in 2019. All protocols had similar participant counts: NFS1 had 60 participants, NFS2 had 57 participants, NFS4 had 58 participants, and NFS5 had 59 participants. During these 15-day study periods, a series of experimental studies aimed at characterizing adolescents' cognitive functions under different sleep manipulations were conducted.

The NSRR deposition only includes data on half of the subjects across the NFS protocols. The included subjects are: NFS (Control group); NFS2 (5h group); NFS4 (6.5h group); and NFS5 (8h group). Additional data are available upon request. Please contact Ju Lynn from the NFS team for more information.

## Methods

### Two-Week Study Protocol

One week prior to the study, participants were required to adhere to a sleep-wake schedule that provided a 9-hour nocturnal sleep opportunity (23:00–08:00). This was verified using wrist-worn actigraphy and was intended for circadian entrainment and for minimizing any effect of prior sleep restriction (SR) on sleep and cognitive performance.

### PSG Collection

Electroencephalography (EEG) was performed using a SOMNOtouch recorder (SOMNOmedics GmbH, Randersacker, Germany) from two channels (C3 and C4 in the international 10–20 system) referenced to the contralateral mastoids. The common ground and reference electrodes were placed at Cz and FPz. Electrooculography (EOG) and submental electromyography (EMG) were also used. Impedance was kept below 5 kΩ for EEG electrodes and below 10 kΩ for EOG and EMG electrodes. Signals were sampled at 256 Hz and filtered between 0.2 and 35 Hz for EEG and between 0.2 and 10 Hz for EOG.

### PSG Scoring

Trained technicians visually scored the sleep data, following criteria set by the American Academy of Sleep Medicine Manual for the Scoring of Sleep and Associated Events. PSG scoring analyses of EDF files were performed using the FASST toolbox (http://www.montefiore.ulg.ac.be/~phillips/FASST.html). EEG signals were band-pass filtered between 0.2 and 25 Hz. Scoring was performed visually by trained technicians following the criteria set by the American Academy of Sleep Medicine Manual for the Scoring of Sleep and Associated Events (2007).

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team.

## Data overview

### Polysomnography

[Raw signal data](:files_path:/original) are shared as EDF files using the European Data Format (https://www.edfplus.info/). 

Files are separated into folders by NFS protocol number. Files begin with the NFS subject identifier ([**subj_id**](:variables_path:/subj_id)). The arrangement of files within each protocol is described as follows:

- NFS1 Protocol: Figure 1A of https://academic.oup.com/sleep/article/39/3/687/2454041 (PSG (Control group) conducted on B1, B3, M1, M3, M5, R1, R3, corresponding to _D1 to _D7 of PSG dataset)
- NFS2 Protocol: Figure 1A of https://academic.oup.com/sleep/article/40/2/zsw042/2732007 (PSG (5h group) conducted on B1, B3, M11, M13, M15, R11, M21, M23, R21, corresponding to _(1) to _(9) of PSG dataset) 
- NFS4 Protocol: Figure 1A of https://academic.oup.com/sleep/article/42/5/zsz037/5316239 (PSG (6.5h group) conducted on B1, B3, M11, M13, M15, R11, M21, M23, R21 in corresponding PSG subfolder)       
- NFS5 Protocol: Figure 1 of https://academic.oup.com/sleep/article/43/12/zsaa129/5867089 (PSG (8h group) conducted on B1, B3, M11, M13, M15, R11, M21, M23, R21 in corresponding PSG subfolder)

Sleep staging...

### Covariate/phenotype datasets (CSV)

[Covariate CSV files](:files_path:/datasets) contain data on 110 subjects. The [**subj_id**](:variables_path:/subj_id) variable is the unique NFS subject identifier that can be linked with PSG signal filenames. The NFS protocol (NFS, NFS2, NFS4, NFS5) is indicated at the beginning of the **subj_id**.

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated "domain" (e.g., 1=Male, 0=Female), which are described in the **domains** data dictionary file. 

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/nfs-data-dictionary). 

The **harmonized-dataset** contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets.

<details>
  <summary>Expand to see the list of key harmonized variables:</summary>

  <table>
    <tr><td><b>Variable</b></td><td><b>Label</b></td></tr>
    <tr><td><a href=":variables_path:/nsrr_age">nsrr_age</a></td><td>Subject age</td></tr>
    <tr><td><a href=":variables_path:/nsrr_sex">nsrr_sex</a></td><td>Subject sex</td></tr> 
    <tr><td><a href=":variables_path:/nsrr_bmi">nsrr_bmi</a></td><td>Body mass index (BMI)</td></tr> 
  </table>

</details>  

## Access and usage restrictions

The NFS dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

When using data from NFS1, users must cite the following:

>[Lo JC, Ong JL, Leong RL, Gooley JJ, Chee MW. Cognitive Performance, Sleepiness, and Mood in Partially Sleep Deprived Adolescents: The Need for Sleep Study. Sleep. 2016 Mar 1;39(3):687-98. doi: 10.5665/sleep.5552. PMID: 26612392; PMCID: PMC4763363.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4763363/)

When using data from NFS2, users must cite the following:

>[Lo JC, Lee SM, Teo LM, Lim J, Gooley JJ, Chee MW. Neurobehavioral Impact of Successive Cycles of Sleep Restriction With and Without Naps in Adolescents. Sleep. 2017 Feb 1;40(2):zsw042. doi: 10.1093/sleep/zsw042. PMID: 28364507; PMCID: PMC5806570.](https://pubmed.ncbi.nlm.nih.gov/28364507/)

When using data from NFS4, users must cite the following:

>[Lo JC, Twan DCK, Karamchedu S, Lee XK, Ong JL, Van Rijn E, Gooley JJ, Chee MWL. Differential effects of split and continuous sleep on neurobehavioral function and glucose tolerance in sleep-restricted adolescents. Sleep. 2019 May 1;42(5):zsz037. doi: 10.1093/sleep/zsz037. PMID: 30753648; PMCID: PMC6519912.](https://pubmed.ncbi.nlm.nih.gov/30753648/)

When using data from NFS5, users must cite the following:

>[Lo JC, Leong RLF, Ng ASC, Jamaluddin SA, Ong JL, Ghorbani S, Lau T, Chee NIYN, Gooley JJ, Chee MWL. Cognitive effects of split and continuous sleep schedules in adolescents differ according to total sleep opportunity. Sleep. 2020 Dec 14;43(12):zsaa129. doi: 10.1093/sleep/zsaa129. PMID: 32619240; PMCID: PMC8061132.](https://pubmed.ncbi.nlm.nih.gov/32619240/)

Users must include the following text in any Acknowledgements:

> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*June 2024*

- Make NFS dataset available for data requests

## References

- Need For Sleep website: https://www.needforsleep.org/
- NFS GitHub Documentation: https://github.com/nsrr/nfs-documentation
- NFS GitHub Data Dictionary: https://github.com/nsrr/nfs-data-dictionary

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
