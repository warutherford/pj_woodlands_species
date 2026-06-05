Data provided in "All_Combined_PJ_Assoc_NoRH.csv" for random forest modeling of PJ Woodland ecosystems and their species irrespective of complete Interpreting Indicators of Rangeland Health data. Point table for variable extraction in Google Earth Engine not currently provided due to USDA NRCS-NRI point location confidentiality.

NRI data is available through a confidentiality agreement(email NRI@usda.gov).


Column-level metadata
-All_Combined_PJ_Assoc_NoRH.csv
bd_depth_0_5 – Numeric: bulk density at 0–5 cm depth (g/cm³) from POLARIS bd_mean, NA where nodata returned.
bd_depth_100_200 – Numeric: bulk density at 100–200 cm depth (g/cm³) from POLARIS, NA when missing.
bd_depth_15_30 – Numeric: bulk density at 15–30 cm depth (g/cm³), NA when not available.
bd_depth_30_60 – Numeric: bulk density at 30–60 cm depth (g/cm³), NA when missing.
bd_depth_5_15 – Numeric: bulk density at 5–15 cm depth (g/cm³), NA when missing.
bd_depth_60_100 – Numeric: bulk density at 60–100 cm depth (g/cm³), NA when missing.
ksat_depth_0_5 – Numeric: saturated hydraulic conductivity at 0–5 cm (log10 mm/hr) from POLARIS ksat_mean, NA when missing.
ksat_depth_100_200 – Numeric: saturated hydraulic conductivity at 100–200 cm, NA when missing.
ksat_depth_15_30 – Numeric: saturated hydraulic conductivity at 15–30 cm, NA when missing.
ksat_depth_30_60 – Numeric: saturated hydraulic conductivity at 30–60 cm, NA when missing.
ksat_depth_5_15 – Numeric: saturated hydraulic conductivity at 5–15 cm, NA when missing.
ksat_depth_60_100 – Numeric: saturated hydraulic conductivity at 60–100 cm, NA when missing.
thetas_depth_0_5 – Numeric: saturated water content (porosity) at 0–5 cm (cm³/cm³) from POLARIS theta_s_mean, NA when missing.
thetas_depth_100_200 – Numeric: porosity at 100–200 cm, NA when missing.
thetas_depth_15_30 – Numeric: porosity at 15–30 cm, NA when missing.
thetas_depth_30_60 – Numeric: porosity at 30–60 cm, NA when missing.
thetas_depth_5_15 – Numeric: porosity at 5–15 cm, NA when missing.
thetas_depth_60_100 – Numeric: porosity at 60–100 cm, NA when missing.
om_depth_0_5 – Numeric: soil organic matter at 0–5 cm (%), POLARIS om_mean, NA when nodata.
om_depth_100_200 – Numeric: soil organic matter at 100–200 cm (%), NA when missing.
om_depth_15_30 – Numeric: soil organic matter at 15–30 cm (%), NA when missing.
om_depth_30_60 – Numeric: soil organic matter at 30–60 cm (%), NA when missing.
om_depth_5_15 – Numeric: soil organic matter at 5–15 cm (%), NA when missing.
om_depth_60_100 – Numeric: soil organic matter at 60–100 cm (%), NA when missing.
ph_depth_0_5 – Numeric: soil pH in H₂O at 0–5 cm from POLARIS ph_mean, NA when missing.
ph_depth_100_200 – Numeric: pH at 100–200 cm, NA when missing.
ph_depth_15_30 – Numeric: pH at 15–30 cm, NA when missing.
ph_depth_30_60 – Numeric: pH at 30–60 cm, NA when missing.
ph_depth_5_15 – Numeric: pH at 5–15 cm, NA when missing.
ph_depth_60_100 – Numeric: pH at 60–100 cm, NA when missing.
sand_depth_0_5 – Numeric: sand percent at 0–5 cm (%) from POLARIS sand_mean, NA when missing.
sand_depth_100_200 – Numeric: sand percent at 100–200 cm (%), NA when missing.
sand_depth_15_30 – Numeric: sand percent at 15–30 cm (%), NA when missing.
sand_depth_30_60 – Numeric: sand percent at 30–60 cm (%), NA when missing.
sand_depth_5_15 – Numeric: sand percent at 5–15 cm (%), NA when missing.
sand_depth_60_100 – Numeric: sand percent at 60–100 cm (%), NA when missing.
silt_depth_0_5 – Numeric: silt percent at 0–5 cm (%) from POLARIS silt_mean, NA when missing.
silt_depth_100_200 – Numeric: silt percent at 100–200 cm (%), NA when missing.
silt_depth_15_30 – Numeric: silt percent at 15–30 cm (%), NA when missing.
silt_depth_30_60 – Numeric: silt percent at 30–60 cm (%), NA when missing.
silt_depth_5_15 – Numeric: silt percent at 5–15 cm (%), NA when missing.
silt_depth_60_100 – Numeric: silt percent at 60–100 cm (%), NA when missing.
clay_depth_0_5 – Numeric: clay percent at 0–5 cm (%) from POLARIS clay_mean, NA when missing.
clay_depth_100_200 – Numeric: clay percent at 100–200 cm (%), NA when missing.
clay_depth_15_30 – Numeric: clay percent at 15–30 cm (%), NA when missing.
clay_depth_30_60 – Numeric: clay percent at 30–60 cm (%), NA when missing.
clay_depth_5_15 – Numeric: clay percent at 5–15 cm (%), NA when missing.
clay_depth_60_100 – Numeric: clay percent at 60–100 cm (%), NA when missing.
PrimaryKey – Categorical: unique plot/visit identifier with no units, NA when missing.
DBKey – Categorical: database key linking the record to its source table, NA when missing.
AssocKey – Categorical: identifier linking species and plot records, NA when missing.
dupe_count – Numeric (integer): count of duplicate occurrences of the record, NA when none.
county – Categorical: county name, NA when missing.
ecositeID – Categorical: NRCS ecological site ID (e.g., R028BY010NV), NA when unknown.
elevation_orig – Numeric: original elevation attribute (m), NA when missing.
source – Categorical: origin dataset identifier (e.g., TerrADat), NA when missing.
species – Categorical: species code or scientific name, NA when unidentified.
speciescount – Numeric (integer): observation count for the species, NA when missing.
state – Categorical: two‑letter U.S. state abbreviation, NA for missing entries.
usgs_elevation – Numeric: elevation in meters from USGS 3DEP DEM, NA for nodata.
usgs_slope – Numeric: slope in degrees from DEM terrain analysis, NA when missing.
usgs_aspect – Numeric: aspect in degrees (0–360), NA when flat.
usgs_hillshade – Numeric: hillshade (0–255 grayscale) from DEM illumination model, NA when missing.
dep_bedrock – Numeric: estimated depth to bedrock (cm) from SoilGrids, NA when unavailable.
annualMeanTemperature – Numeric: annual mean temperature (°C × 10) from WorldClim/PRISM, NA when missing.
diurnalRange – Numeric: mean diurnal temperature range (°C × 10), NA when missing.
isotherm – Numeric: isothermality index (unitless), NA when missing.
tempseasonality – Numeric: temperature seasonality (SD × 100), NA when missing.
maxTempWarmMonth – Numeric: maximum temperature of warmest month (°C × 10), NA when missing.
minTempColdMonth – Numeric: minimum temperature of coldest month (°C × 10), NA when missing.
tempAnnualRange – Numeric: annual temperature range (°C × 10), NA when missing.
meanTempWetQuart – Numeric: mean temperature of wettest quarter (°C × 10), NA when missing.
meanTempDryQuart – Numeric: mean temperature of driest quarter (°C × 10), NA when missing.
meanTempWarmQuart – Numeric: mean temperature of warmest quarter (°C × 10), NA when missing.
meanTempColdQuart – Numeric: mean temperature of coldest quarter (°C × 10), NA when missing.
annualPpt – Numeric: annual precipitation (mm) from PRISM/WorldClim, NA when missing.
pptWetMonth – Numeric: precipitation of wettest month (mm), NA when missing.
pptDryMonth – Numeric: precipitation of driest month (mm), NA when missing.
pptSeasonality – Numeric: coefficient of variation of precipitation (%), NA when missing.
pptWetQuart – Numeric: precipitation of wettest quarter (mm), NA when missing.
pptDryQuart – Numeric: precipitation of driest quarter (mm), NA when missing.
pptWarmQuart – Numeric: precipitation of warmest quarter (mm), NA when missing.
pptColdQuart – Numeric: precipitation of coldest quarter (mm), NA when missing.
mod_lc_2001 … mod_lc_2020 – Categorical (integer): MODIS MCD12Q1 IGBP land‑cover class for each year 2001–2020 (0–17 categories), NA when unclassified.
severity – Numeric: burn severity index for the pixel (dataset‑specific), NA when unburned.
wildfire_freq – Numeric (integer): number of wildfire events detected at the pixel over the analysis period, NA when none.
prescribed_freq – Numeric (integer): number of prescribed burns affecting the pixel, NA when none.
na_l1code / na_l1name – Categorical: North America Level‑1 ecoregion code/name, NA when missing.
na_l2code / na_l2name – Categorical: North America Level‑2 ecoregion code/name, NA when missing.
us_l3code / us_l3name – Categorical: U.S. EPA Level‑3 ecoregion code/name, NA when missing.
us_l4code / us_l4name – Categorical: U.S. EPA Level‑4 ecoregion code/name, NA when missing.
