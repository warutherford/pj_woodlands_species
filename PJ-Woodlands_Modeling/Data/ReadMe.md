Data provided in "All_Combined_PJ_Assoc_NoRH.csv" for random forest modeling of PJ Woodland ecosystems and their species irrespective of complete Interpreting Indicators of Rangeland Health data. Point table for variable extraction in Google Earth Engine not currently provided due to USDA NRCS-NRI point location confidentiality.

NRI data is available through a confidentiality agreement(email NRI@usda.gov).

Column-level metadata:

-All_Combined_PJ_Assoc_NoRH.csv
bd_depth_0_5 – Numeric: bulk density at 0–5 cm depth (g/cm³) from POLARIS, NA where nodata returned.
bd_depth_100_200 – Numeric: bulk density at 100–200 cm depth (g/cm³) from POLARIS, NA when missing.
bd_depth_15_30 – Numeric: bulk density at 15–30 cm depth (g/cm³), NA when missing.
bd_depth_30_60 – Numeric: bulk density at 30–60 cm depth (g/cm³), NA when missing.
bd_depth_5_15 – Numeric: bulk density at 5–15 cm depth (g/cm³), NA when missing.
bd_depth_60_100 – Numeric: bulk density at 60–100 cm depth (g/cm³), NA when missing.

ksat_depth_0_5 – Numeric: saturated hydraulic conductivity at 0–5 cm (log10 mm/hr) from POLARIS, NA when missing.
ksat_depth_100_200 – Numeric: saturated hydraulic conductivity at 100–200 cm (log10 mm/hr), NA when missing.
ksat_depth_15_30 – Numeric: saturated hydraulic conductivity at 15–30 cm (log10 mm/hr), NA when missing.
ksat_depth_30_60 – Numeric: saturated hydraulic conductivity at 30–60 cm (log10 mm/hr), NA when missing.
ksat_depth_5_15 – Numeric: saturated hydraulic conductivity at 5–15 cm (log10 mm/hr), NA when missing.
ksat_depth_60_100 – Numeric: saturated hydraulic conductivity at 60–100 cm (log10 mm/hr), NA when missing.

thetas_depth_0_5 – Numeric: saturated volumetric water content (porosity) at 0–5 cm (cm³/cm³), NA when missing.
thetas_depth_100_200 – Numeric: porosity at 100–200 cm (cm³/cm³), NA when missing.
thetas_depth_15_30 – Numeric: porosity at 15–30 cm (cm³/cm³), NA when missing.
thetas_depth_30_60 – Numeric: porosity at 30–60 cm (cm³/cm³), NA when missing.
thetas_depth_5_15 – Numeric: porosity at 5–15 cm (cm³/cm³), NA when missing.
thetas_depth_60_100 – Numeric: porosity at 60–100 cm (cm³/cm³), NA when missing.

om_depth_0_5 – Numeric: soil organic matter at 0–5 cm depth (%), NA when missing.
om_depth_100_200 – Numeric: soil organic matter at 100–200 cm depth (%), NA when missing.
om_depth_15_30 – Numeric: soil organic matter at 15–30 cm depth (%), NA when missing.
om_depth_30_60 – Numeric: soil organic matter at 30–60 cm depth (%), NA when missing.
om_depth_5_15 – Numeric: soil organic matter at 5–15 cm depth (%), NA when missing.
om_depth_60_100 – Numeric: soil organic matter at 60–100 cm depth (%), NA when missing.

ph_depth_0_5 – Numeric: soil pH in H₂O at 0–5 cm, NA when missing.
ph_depth_100_200 – Numeric: soil pH at 100–200 cm, NA when missing.
ph_depth_15_30 – Numeric: soil pH at 15–30 cm, NA when missing.
ph_depth_30_60 – Numeric: soil pH at 30–60 cm, NA when missing.
ph_depth_5_15 – Numeric: soil pH at 5–15 cm, NA when missing.
ph_depth_60_100 – Numeric: soil pH at 60–100 cm, NA when missing.

sand_depth_0_5 – Numeric: sand content at 0–5 cm (%), NA when missing.
sand_depth_100_200 – Numeric: sand content at 100–200 cm (%), NA when missing.
sand_depth_15_30 – Numeric: sand content at 15–30 cm (%), NA when missing.
sand_depth_30_60 – Numeric: sand content at 30–60 cm (%), NA when missing.
sand_depth_5_15 – Numeric: sand content at 5–15 cm (%), NA when missing.
sand_depth_60_100 – Numeric: sand content at 60–100 cm (%), NA when missing.

silt_depth_0_5 – Numeric: silt content at 0–5 cm (%), NA when missing.
silt_depth_100_200 – Numeric: silt content at 100–200 cm (%), NA when missing.
silt_depth_15_30 – Numeric: silt content at 15–30 cm (%), NA when missing.
silt_depth_30_60 – Numeric: silt content at 30–60 cm (%), NA when missing.
silt_depth_5_15 – Numeric: silt content at 5–15 cm (%), NA when missing.
silt_depth_60_100 – Numeric: silt content at 60–100 cm (%), NA when missing.

clay_depth_0_5 – Numeric: clay content at 0–5 cm (%), NA when missing.
clay_depth_100_200 – Numeric: clay content at 100–200 cm (%), NA when missing.
clay_depth_15_30 – Numeric: clay content at 15–30 cm (%), NA when missing.
clay_depth_30_60 – Numeric: clay content at 30–60 cm (%), NA when missing.
clay_depth_5_15 – Numeric: clay content at 5–15 cm (%), NA when missing.
clay_depth_60_100 – Numeric: clay content at 60–100 cm (%), NA when missing.

PrimaryKey – Categorical: unique plot identifier, NA when missing.
DBKey – Categorical: database key linking the record to its source dataset, NA when missing.
AssocKey – Categorical: association key connecting plot/species records, NA when missing.
dupe_count – Numeric (integer): number of duplicate records detected, NA when none.
county – Categorical: county name for the plot location, NA when missing.
ecositeID – Categorical: NRCS ecological site ID, NA when not assigned.
elevation_orig – Numeric: original source elevation (m), NA when missing.
source – Categorical: dataset origin (e.g., AIM/TerrADat), NA when missing.
species – Categorical: species code or name, NA when unidentified.
speciescount – Numeric (integer): count of individuals/occurrences, NA when missing.
state – Categorical: U.S. state abbreviation, NA when missing.

usgs_elevation – Numeric: elevation in meters from USGS 3DEP DEM, NA for nodata.
usgs_slope – Numeric: terrain slope in degrees, NA when missing.
usgs_aspect – Numeric: terrain aspect in degrees (0–360), NA when flat.
usgs_hillshade – Numeric: hillshade value (0–255), NA when missing.
dep_bedrock – Numeric: depth to bedrock (cm) from SoilGrids, NA when missing.

annualMeanTemperature – Numeric: annual mean temperature (°C × 10), NA when missing.
diurnalRange – Numeric: mean diurnal temperature range (°C × 10), NA when missing.
isotherm – Numeric: isothermality index (unitless), NA when missing.
tempseasonality – Numeric: temperature seasonality (SD × 100), NA when missing.
maxTempWarmMonth – Numeric: max temp of warmest month (°C × 10), NA when missing.
minTempColdMonth – Numeric: min temp of coldest month (°C × 10), NA when missing.
tempAnnualRange – Numeric: annual temp range (°C × 10), NA when missing.
meanTempWetQuart – Numeric: mean temperature of wettest quarter (°C × 10), NA when missing.
meanTempDryQuart – Numeric: mean temperature of driest quarter (°C × 10), NA when missing.
meanTempWarmQuart – Numeric: mean temperature of warmest quarter (°C × 10), NA when missing.
meanTempColdQuart – Numeric: mean temperature of coldest quarter (°C × 10), NA when missing.

annualPpt – Numeric: annual precipitation (mm), NA when missing.
pptWetMonth – Numeric: precipitation of wettest month (mm), NA when missing.
pptDryMonth – Numeric: precipitation of driest month (mm), NA when missing.
pptSeasonality – Numeric: precipitation coefficient of variation (%), NA when missing.
pptWetQuart – Numeric: precipitation of wettest quarter (mm), NA when missing.
pptDryQuart – Numeric: precipitation of driest quarter (mm), NA when missing.
pptWarmQuart – Numeric: precipitation of warmest quarter (mm), NA when missing.
pptColdQuart – Numeric: precipitation of coldest quarter (mm), NA when missing.

mod_lc_2001 – Categorical (integer): MODIS IGBP land‑cover class for 2001 (0–17), NA when unclassified.
mod_lc_2002 – Same as above for 2002.
mod_lc_2003 – Same as above for 2003.
mod_lc_2004 – Same.
mod_lc_2005 – Same.
mod_lc_2006 – Same.
mod_lc_2007 – Same.
mod_lc_2008 – Same.
mod_lc_2009 – Same.
mod_lc_2010 – Same.
mod_lc_2011 – Same.
mod_lc_2012 – Same.
mod_lc_2013 – Same.
mod_lc_2014 – Same.
mod_lc_2015 – Same.
mod_lc_2016 – Same.
mod_lc_2017 – Same.
mod_lc_2018 – Same.
mod_lc_2019 – Same.
mod_lc_2020 – Same.

severity – Numeric: burn severity index for the pixel, NA when unburned.
wildfire_freq – Numeric (integer): number of wildfire events affecting the pixel, NA when none.
prescribed_freq – Numeric (integer): number of prescribed burns detected, NA when none.

na_l1code – Categorical: NA Level‑1 ecoregion code, NA when missing.
na_l1name – Categorical: NA Level‑1 ecoregion name, NA when missing.
na_l2code – Categorical: NA Level‑2 ecoregion code, NA when missing.
na_l2name – Categorical: NA Level‑2 ecoregion name, NA when missing.
us_l3code – Categorical: US Level‑3 ecoregion code, NA when missing.
us_l3name – Categorical: US Level‑3 ecoregion name, NA when missing.
us_l4code – Categorical: US Level‑4 ecoregion code, NA when missing.
us_l4name – Categorical: US Level‑4 ecoregion name, NA when missing.
