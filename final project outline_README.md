**Assignment: Final project outline (draft).**
Caitlin Traver (cjt2162)
April 7, 2026

**Background**: This project supports my Disaster Research Methods project on the 2014–2016 Ebola outbreak in Liberia, which examines how forest fragmentation and human behavior influenced disease transmission risk. That research finds that communities near forest–savannah boundaries and areas of environmental change experienced higher exposure to Ebola due to increased human–wildlife interaction. In this climate data science project, I extend that framework by investigating whether climate variability (temperature and precipitation anomalies) acted as an additional environmental driver that influenced where and when Ebola outbreaks occurred. By integrating climate data with land use change and outbreak records, this project aims to better understand how climate and environmental change together shape disease risk.

**Research Question**: How do climate variability (temperature and precipitation anomalies) and land-use change (forest loss and fragmentation) interact to influence Ebola outbreak clustering in Liberia?

**Hypothesis**: Regions experiencing both significant forest loss and climate anomalies (higher temperature variability and abnormal precipitation) will exhibit greater Ebola outbreak clustering than regions experiencing only one or neither of these factors.

**Analysis**: The analysis will integrate climate, land-use, and epidemiological datasets to examine how environmental factors relate to Ebola outbreak clustering in Liberia. Using xarray, I will process gridded climate data to calculate temperature and precipitation anomalies relative to a pre-outbreak baseline period. Forest loss data will be used to quantify land-use change and identify high and low deforestation regions. These datasets will be spatially aligned with Ebola case data, allowing extraction of climate conditions and land-use characteristics at outbreak locations. Using NumPy and matplotlib, I will compare climate anomalies and forest loss between outbreak and non-outbreak regions and analyze their combined effects on case clustering through correlations, grouped comparisons, and visualization of spatial and statistical relationships.

**Datasets**:
1.  Climate Data: **CRU TS Dataset**
    Monthly gridded climate data (temperature and precipitation) from the Climate Research Unit, used to calculate climate
    variability and anomalies during the Ebola outbreak period.
    https://crudata.uea.ac.uk/cru/data/hrg/

2.  Land Use Data: **Hansen Global Forest Change Dataset**
    High-resolution global forest cover and forest loss data used to quantify deforestation and identify areas of forest 
    fragmentation prior to and during the outbreak.
    https://earthenginepartners.appspot.com/science-2013-global-forest

3.  Ebola Case Data: **Humanitarian Data Exchange (HDX)**
    Open-access epidemiological datasets providing Ebola case counts by location and time, used to analyze spatial clustering of
    outbreaks in Liberia.
    https://data.humdata.org/dataset/ebola-cases-2014

**Potential Plot Ideas:**
1.	Map of Ebola cases overlaid on forest–savannah transition zones
2.	Map of forest loss and climate anomalies
3.	Time series of temperature and precipitation anomalies during the outbreak
4.	Scatter plot: precipitation anomaly vs Ebola case density
5.	Scatter plot: forest loss vs case density (colored by temperature anomaly)
6.	Grouped bar chart comparing Ebola incidence across combined deforestation and climate anomaly categories
7.	2D density plot of temperature vs precipitation anomalies with case density
