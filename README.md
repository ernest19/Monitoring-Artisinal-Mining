

## MAPPING AND MONITORING ARTISANAL MINING USING REMOTE SENSING TECHNOLOGIES IN GHANA.

![MONITORING ARTISANAL MINING](https://img.shields.io/static/v1?label=ARTISANAL&message=MINING%&color=blue)



### Project Area Brief

The project area encompasses the major gold belt and the most designated forest reserves in the moist and wet tropical forest zones of Ghana. It includes all of the Western North and Western Regions and large parts of the Central, Ashanti, Eastern, and Ahafo Regions. Most of this area had been covered by forest, but is now mostly covered by secondary growth vegetation, with subsistence farming and in recent times, illegal mining activities. There are seventy (70) districts and municipal (local government) areas in the project area with forty-eight (48) of these districts affected by illegal mining activities. The local government authorities are vested with the administrative and planning mandates at the local level, with the responsibility for the overall development of their areas of jurisdiction.


### Project Area Brief

The main earth observation data chosen for identifying the galamsey sites was the European Space Agency’s Sentinel-1 platform which provides data from a dual-polarization C-band Synthetic Aperture Radar (SAR) instrument. This platform was selected because SAR instruments can acquire useful data in all weather conditions (including clouds), obviating considerable cloud masking effort during the image processing stage, given the cloudy weather conditions over the project area most of the time. 
Therefore, the SAR data is suitable for detecting alluvial gold mining sites under cloudy or rainy conditions. Like all Sentinel data provided under the European Commission's Copernicus Programme, Sentinel-1 data products are provided free of charge to all data users and therefore useful for data-poor countries that are developing monitoring systems for environmental accounting and measuring progress towards the sustainable development goals (SDGs). 
Illegally mined areas are usually characterized by patches of bare soil and pools of stagnant water created during the mining process. While these areas are easily identified in high-resolution images, the spectral similarity with other bare surfaces confuse actual mined areas with unmined bare surfaces such as settlement extent, gravel pits and areas prepared for cultivation. In order to discriminate actual mined areas from unmined bare surfaces, annual median composites produced from the Sentinel-2 optical image collection was used to produce normalized difference vegetation index (NDVI) bands, and subsequently used to create ‘unmined bare surface’ masks.
The output was further refined by using GIS data layers such as road networks, settlement extent and legal mining concessions to retain only ‘illegal mining’ (i.e. galamsey) pixels. All the image processing tasks were carried out in Google Earth Engine (GEE). The final output can be queried in GEE to obtain monthly or quarterly footprints. Additionally, different images can be computed with two consecutive footprints to highlight new galamsey sites that have sprung up as well as areas left inactive with time.



<img src="https://github.com/ernest19/Monitoring-Artisinal-Mining/blob/main/img/image.png"

