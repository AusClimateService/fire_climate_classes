# fire_climate_classes
Information on the creation and generation of fire climate classes (initial version), and the associated code and data.
- Latest data update: 28/06/2024
- Projections data location: /g/data/ia39/ncra/bushfire/
- Figues available: /g/data/ia39/ncra/bushfire/figures
- Past data location - generated from operational AGCD products (Jones, et al., 2009; Evans, et al., 2020): /g/data/ia39/ncra/bushfire/past_data
- Data status can be found here: https://github.com/AusClimateService/hazard_data_release/blob/main/README.md 

## Description
GitHub repository for ACS Hazard Team on Bushfires to store, track and develop code.

## Fire climate classes summary
The _fire climate classes_ provide a framework through which we can assess the changing bushfire risk for Australia, bringing together knowledge to create reliable, national data which can support planning and action towards more resilient communities. The fire climate classes are _defined_ using meteorological information (temperature and rainfall, which are available from climate projection models, allowing us to look into the future), but results from ecology research _characterise_ the fire climate classes. In examining how these classes have evolved through the past and are expected to evolve with climate change, we seek to provide more clarity about future bushfire risk. 

Below is the summary of the climate influences on fire for each of the five fire climate classes. The full description of the class creation and characteristics can be found in the full report [link here].

### Tropical Savanna
-	**Main influence on fire activity:** Rainfall – increases in rainfall result in increased biomass productivity and therefore load and connectivity of fuels. This increases the risk of bushfire when the fuels dry (in the reliable dry season).
-	Increased rainfall: Rainforest will encroach on savanna if mean annual rainfall increases, but the development of rainforest more likely to occur on fertile substrates for any given rainfall regime.
-	Decreased rainfall or drought: Reduces risk of fire due to limiting biomass productivity, may alter the savanna structure, a long-term reduction in rainfall may lower tree density.
-	Fire has a substantial effect on rainforest development within a relatively narrow band of mean annual rainfall.
-	The occurrence of rainforest at the dry end of the rainfall spectrum is greatly enhanced with fire protection on rocky landforms.
-	Increasing fire weather severity with climate change, might reduce the length of the early dry season (prescribed burning season).

### Arid grasses and woodlands
-	**Main influence on fire activity:** to varying extents rainfall and fuel moisture. Rainfall in typically dry regions will promote biomass production in otherwise highly disconnected fuels. Extended dry periods are required for sufficient reduction of fuel moisture to enable fire activity. 
-	The ecological dynamics in temperate southern Australia (under projected drier and warmer conditions) are likely to be increasingly driven by the interactions between drought, plant growth, and fire (Enright, et al., 2012).
-	Decreased fuel moisture, increased fire intensity, decreased species survival (Enright, et al., 2012).
-	Episodic peaks in biomass and connectivity of fuels follows wet years (Enright, et al., 2012).

### Wet forest
-	**Main influence on fire activity:** drought, and extreme fire weather. Usually, these ecosystems are too wet to burn but prolonged dry periods make the vegetation widely available to fire. 
-	Reduced rainfall (long term) may reduce productivity and fuel loads, reducing fire risk. Reduced fine litter associated with declining canopy leaf biomass over Australian forests.
-	Heathland and wet forests generally increase in flammability with age (time since fire) (McColl-Gausden & Penman, 2018).
-	Increasing presence of invasive species/weeds increases fire risk in dry rainforest (Berry, et al., 2011).
-	There is positive feedback of higher susceptibility to fire in rainforest systems due to drying after a fire. Dried forest is more susceptible to burn. Fire opens the canopy and allows more sunlight to penetrate to the lower levels of the rainforest, which dries surface fuels, further increasing the risk of fires. 

### Dry forest
-	**Main influence on fire activity:** drought, heatwave, extreme fire weather. Drought is a precursor to megafires as it increases the area of available (low fuel moisture) and connected fuel.  Increased frequency of heatwaves increases the chance of overnight fire activity and therefore more widespread fire activity.
-	Using satellite imagery, (Caccamoa, et al., 2014) showed (and verified within the study area, mix of dry forest and grass in the fire climate) that eucalypt forests recover rapidly after ﬁre (spectral indices values returned to pre-ﬁre levels three to six years after ﬁre). The inﬂuence of fire severity was limited to the ﬁrst two years after ﬁre.
-	Increased fire frequency may change the understory fuel ratios (Gordon, et al., 2024).
-	Increased frequency of heatwaves may increase dryness and fire risk.
-	Potential decline in fine fuels, but increased dryness as suggested by proxy data, which led to decreased and increased fire risk, respectively.

### Grassland and crops
-	**Main influence on fire activity:** biomass productivity/fuel load. In cropping or grazing areas, fuel loads can be quite low (or prior to harvest, too wet to burn). In more arid, unfarmed areas, lower rainfall generally limits productivity. Unusually high rainfall which triggers growth is then a precursor for fire.
-	While drought in isolation can lower the risk of fire due to reduced biomass productivity and therefore fuel (Ellis, et al., 2004), high rainfall followed by drought leads to an elevated fire risk.

## Example application
![image](https://github.com/user-attachments/assets/3958e7f3-5303-4544-b6a6-0afe64379688)
![image](https://github.com/user-attachments/assets/447f02b2-41ad-49fd-91dc-470bda16e3ac)
![image](https://github.com/user-attachments/assets/ea5c884c-1503-41bc-9189-67fcfc1e6975)


### References
- Berry, Z. C., Wevill, K. & Curran, T. J., 2011. The invasive weed Lantana camara increases fire risk in dry rainforest by altering fuel beds. Weed Research, 51(5), pp. 525-533.
- Caccamoa, G. et al., 2014. Using MODIS data to analyse post-fire vegetation recovery in Australianeucalypt forests. Journal of Spatial Science.
- Ellis, S., Kanowski, P. & Whelan, R., 2004. National Inquiry on Bushfire Mitigation and Management , Canberra: Commonwealth of Australia.
- Enright, N. J., Keith, D. A., Clarke, M. F. & Miller, B. P., 2012. Fire regimes in Australian sclerophyllous shrubby ecosystems: heathlands, heathy woodlands and mallee woodlands.. In: R. A. Bradstock, A. M. Gill & R. J. Williams, eds. Flammable Australia: Fire regimes, biodiveristy and ecosystems in a changing world.. s.l.:CSIRO, pp. 215-234.
- Evans, A., Jones, D., Smalley, R. & Lellyet, S., 2020. An enhanced gridded rainfall analysis scheme for Australia. Bureau Research Report – 41., Melbourne, Australia: Bureau of Meteorology.
- Gordon, C. E. et al., 2024. Severe and Short Interval Fires Rearrange Dry Forest Fuel Arrays in South-Eastern Australia. Fire, 7(4).
- Jones, D., Wang, W. & Fawcett, R., 2009. High-quality spatial climate data-sets for Australia. Australian Meteorological and Oceanographic Journal, Volume 58, p. 233–248.
- McColl-Gausden, S. C. & Penman, T. D., 2018. Pathways of change: Predicting the effects of fire on flammability. Journal of environmental managemen, Volume 232, p. 243–253.



