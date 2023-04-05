# FAME-hackathon_2023
This is a record of my contribution to the FAME Hackathon held in Adelaide in March 2023. The hackathon consisted of teams working on different aspects of a metagenomic dataset of sputum samples from cystic fibrosis patients. [FAME](https://fame.flinders.edu.au/people/) is a microbiome lab at Flinders University.

I was on the clinical metadata team. The attached .csv is not the final data table to be used in publications by the FAME lab, but the one I used to make summary plots.


![age_dist_cf](https://user-images.githubusercontent.com/16071029/229977559-b14fe234-666f-40f6-9060-6ebfdd0fb176.png)

![sample_dist_cf](https://user-images.githubusercontent.com/16071029/229977695-471b2876-380f-4127-b051-35d38ef762e1.png)

- Basic age distribution and sampling distribution for the data
- About half of the samples are the only sample for each patient (i.e., not longitudinal)

![long_clin_final](https://user-images.githubusercontent.com/16071029/229977748-9b70f5f2-0075-43af-b5b9-14965fa844cc.png)

- Important clinical data showed longitudinally for individual patients
- Methane to hydrogen ratio is indicative of the metabolism of anaerobic bacteria...
- FEV1 is forced expiratory volume over 1 second, the most commonly used clinical indication of lung health for cystic fibrosis patients (i.e., a sharp decrease shows an exacerbation)
- Patients are coloured by sex, point shapes indicate inpatient or outpatient at the time of collection
- Only samples with sequencing data available are included in the plot
- The metadata table also has information on culture results (relevant for assessing if sequencing data would have affected clinical decisions), on the antibiotics each patient was taking at different times, the particular cystic fibrosis mutation present, some immunological data, and some other basic information
- Other people on the clinical metadata team worked on creating a rating scale for the antibiotics and connecting this information with metagenomic findings from other teams
