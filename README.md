## High alpine burrow-sharing mammals and birds show similar population-level vulnerability to climate change

### DATA & FILE OVERVIEW

1. We used three species in our study.

2. **data.zip** contains location records used in ecological niche models and climate data used in genotype-environment association.

3. **code.zip** contains 6 R scripts for relevant analyses, including:

   - R-script-for-GEBVs.R

   - R-script-for-genotype-climate-associstions.R

   - R-script-for-GF.R

   - R-script-for-GDM.R

   - R-script-for-ENM.R

   - R-script-for-landscape-connectivity.R

4. The version of R software and how to install them can be found on each script. R version 4.1.0 was used to conduct all R analyses.

### SPECIFIC INFORMATION FOR: data.zip

1. **Tibet_species_locations.csv**: location records used in ecological niche models, variables information is described as following.
	Species: species' scientific name
	x: longitude
	y: latitude

2. **Tibet_species_env.csv**: 3 bioclimatic variables were used in our study, the first two columns are species' scientific name and samples ID, and the rest columns are the 3 bioclimatic variables.
	Species: species' scientific name
	ID: samples ID
	bio5: Max Temperature of Warmest Month
	bio6: Min Temperature of Coldest Month
	bio15: Precipitation Seasonality (Coefficient of Variation)
