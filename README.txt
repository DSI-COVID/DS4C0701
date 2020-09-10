DS4C0701
This repository contains data sets used in the research article "Diagnostic serial interval as a novel indicator for contact tracing effectiveness exemplified with the SARS-CoV-2/COVID-19 outbreak in South Korea" by Sofia K. Mettler, Jihoo Kim and Marloes H. Maathuis (https://doi.org/10.1016/j.ijid.2020.07.068).

# Data sets and variables
1) PatientInfo_encrypted.csv
patient_id: encrypted patient ID
province: location of residence
infection_case: infection route
infected_by: infector's ID (encrypted as in patient_id)
contact_number: the number of identified contacts the patient had
symptom_onset_date: date of symptom onset
confirmed_date: date of diagnostic confirmation by PCR testing

2) Time.csv
date: date of government briefing
time: either 16:00 pm or 00:00 am (cut-off time of case inclusion in government briefing)
test: the total number of tests performed by the date
negative: the total number of negative test results by the date
confirmed: the total number of confirmed cases by the date
released: the total number of patients discharged from a hospital or a quarantine center by the date
deceased: the total number of patients who died by the date

3) TimeProvince.csv: 
Time.csv by province (the meanings of variables are the same as in Time.csv)

4) Region.csv
code: the code of the region
province: Special City / Metropolitan City / Province(-do)
city: City(-si) / Country (-gun) / District (-gu)
latitude: the latitude of the visit (WGS84)
longitude: the longitude of the visit (WGS84)
elementary_school_count: the number of elementary schools
kindergarten_count: the number of kindergartens
university_count: the number of universities
academy_ratio: the ratio of academies
elderly_population_ratio: the ratio of the elderly population
elderly_alone_ratio: the ratio of elderly households living alone
nursing_home_count: the number of nursing homes
Source of the statistic: KOSTAT (Statistics Korea)

5) COSIb_DS4C0701.csv
Observed clinical onset serial intervals (Data set B, 102 pairs). Please refer to the supplementary material of our article at doi:https://doi.org/10.1016/j.ijid.2020.07.068 for detailed information.

6) DSIb_DS4C0701.csv
Observed diagnostic serial intervals (Data set B, 102 pairs). Please refer to the supplementary material of our article at doi:https://doi.org/10.1016/j.ijid.2020.07.068 for detailed information.

7) DSI_DS4C0701.csv
Observed diagnostic serial intervals (Data set A, 1235 pairs). Please refer to the supplementary material of our article at doi:https://doi.org/10.1016/j.ijid.2020.07.068 for detailed information.
