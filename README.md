# Pinyon-Juniper Woodland Species Manuscript

## This work is submitted:

Journal: ***Ecosphere***

Manuscript type: Research Article

Title: **Distribution and ecohydrologic function of pinyon pine and juniper woodland communities and species using national longitudinal surveys**

## Abstract
Pinyon (Pinus spp.) - juniper (Juniperus spp.) woodlands are a common ecosystem type across the western USA that have historically and are actively experiencing expansion and contraction with risk of ecosystem alteration in ecohydrologic function. Excluding anthropogenic influences on ecosystem development (e.g., alterations to historical fire regimes), the specific bioclimatic and topo-edaphic determinants of PJ woodland establishment, especially the species that comprise them, are poorly understood. Assessment of species-level dynamics with on-the-ground (e.g., ≤ 30 m2) indicators of ecosystem functioning is difficult with available satellite remote sensing techniques. Using ground-based plot samples, we present current (2009-2021) PJ community and species regional domains modeled from multiple longitudinal assessment andmonitoring frameworks across the western USA with potential factors driving or controlling their presence. We further evaluated the interpreting indicators of rangeland health ecohydrological function of PJ communities relative to ecological site reference conditions as tree densities increase and those regions where rangeland conditions and function may be changing. Our PJ community/ecosystem random forest classification model had an accuracy of 61.6% with species-level models ranging from 52% to 99%. The top model determinants of PJ community ecosystems were wet-season temperature, precipitation seasonality, warm-season precipitation, seasonal drought temperature, and isothermality. Total warm-season precipitation, wet-season temperature, and precipitation seasonality were among the top discriminant variables between PJ species. High PJ densities were associated with reduced species richness and total perennial grass and forb cover with consequence of increasing bare ground cover, inducing the potential for soil surface erosion (e.g., reduced ecohydrologic function). Taken together, increasing PJ species density and cover can come at a risk of loss of plant understory richness, livestock and native herbivore forage, and surface soils in absence of prescribed management intervention or fire. The applied national longitudinal surveys provided valuable ecosystem- and species-level detail to assess trends in both natural and agricultural resources.

## Folder PJ-Woodlands_Modeling
R scripts for random forest classification modeling the occurance of PJ Woodland ecosystem types ("1_pj_clustering_spatial_12032023.R"), followed by species level models ("pj_clustering_rf_XXX.R" scripts) and subsequent PCAs ("pj_pca_biplots_XXX.R" scripts).

## Folder PJ_Woodlands_Organize_RangeHealth_GroundCover
R scripts for cleaning and organizing the AIM and NRI protocol data to include only PJ Woodland species of interest as well as Rangeland Health data ("1_data-clean-organize-PJ-Woodlands.qmd"), followed by analysis and figure creation of ground cover metrics with Rangeland Health data ("2_range_health_022024.R" scripts).

### File GEE_JavaScript_code_PJ_Extraction.txt
JavaScript code used in Google Earth Engine for bioclimatic and topo-edaphic variable extraction by AIM and NRI point samples.
