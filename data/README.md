# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, data dictionary, etc.

The data dictionary for your data file(s) using the following format.

## bll_data (final combined dataset)

| Variable  | Description               |
|:----------|:--------------------------|
| zip_code | California zip code (categorical) |
| city | California city (categorical) |
| num_bll | Total number of children in a zip code whose blood was tested for lead (numerical) |
| num_bll_indicator | The number of tested children in a zip code under 6 that have a blood lead level of 3.5mg or greater -- used as an indicator of blood lead levels of zip code (numerical) |
| perc_bll_indicator | The percentage of tested children in a zip code under 6 that have a blood lead level of 3.5mg or greater (numerical) |
| num_prison | The number of imprisoned people in a zip code (numerical) |
| total_pop_2020 | Population of a zip code in 2020 (numerical) |
| imprisonment_rt | Imprisonment rate per 100,000 people in a zip code (numerical) |
| median_age | Median age in zip code (numerical) |
| male | Proportion of males in zip code (%, numerical) |
| female | Proportion of female in zip code (%, numerical) |
| white | Proportion of white people in zip code (%, numerical) |
| black | Proportion of black people in zip code (%, numerical) |
| native_am | Proportion of Native Americans and Alaska Natives in zip code (%, numerical) |
| asian | Proportion of Asian people (%, numerical) |
| pac_islander | Proportion of Native Hawaiians and Pacific Islanders in zip code (%, numerical) |
| other_race | Proportion of all other unaccounted races in zip code (%, numerical) |
| age_0_to_19 | Proportion of 0-19 year olds in zip code (%, numerical) |
| age_20_to_44 | Proportion of 20-44 year olds in zip code (%, numerical) |
| age_45_to_64 | Proportion of 45-64 year olds in zip code (%, numerical) |
| med_income | Median income of zip code ($, numerical) |
| mean_income | Mean income of zip code ($, numerical) | 


Note: due to the large nature of the census data (over 360 columns) as well as the long original names, we have provided the data dictionary for the processed dataset, which contains only the pertinent variables renamed for clarity.
