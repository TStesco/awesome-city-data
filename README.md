# Awesome Open City Data

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of open data sources to analyze and compare cities in a 
holistic way à la data science and empower citizens.

### Topics

##### 1. Economy 
* Cost of living
* Salary
* Businesses

##### 2. Infrastructure
* Transportation
* Energy
* Health
* Water
* Waste/recycling and sanitation
* Internet
* Heavy industry
* Agriculture

##### 3. Demographics
* Population
* Workforce
* Education
* Crime
* Immigration/emigration

##### 4. Environment
* Climate
* Air quality
* Soil quality
* Noise
* Waterways
* Parks/forests/Conservation areas
* Natural disasters
* Pollution

##### 5. Development
* Residential planned/new/stock
* Commercial planned/new/stock
* Real estate market
* Zoning and Land use
* Energy demand

##### 6. Life Style
* Happiness
* Culture
* Communities

## How to use this list

This list is for anyone looking to get a quantitative perspective on a specific 
place. This is not a database, it is a list of data sources. 
Based on the geographically distributed nature of this data and my personal 
interests the availability of data is going to be biased. It is my intention that
you add data sources from your geographic areas of interest via pull requests to 
grow open data usage and improve diversity and detail. Once a significant amount 
of data sources exist for several places good analysis and comparisons can be made.

### Structure

The idea is to curate an alphabetical list of data sources by geographic level from macro to 
micro scale, in descending subsets, following as closely as possible:

1. Nation
2. state/province/canton
3. city/metropolitan area
4. district/neighbourhood

| Level | Topics | Status | Description | Format | Source | link |
|---|---|---|---|---|---|---|

#### Level column

Example of Levels column:

| Level | meaning |
| --- | --- |
| \* | datasets at **nation level** for **multiple nations** |
| Switzerland/\* | datasets at **canton level** for **multiple cantons** in **Switzerland** |
| \*/\* | datasets at **state/province/canton level** for **state/province/canton cantons** in **multiple nations** |
| United States/Illinois/Chicago/ | datasets at **city level** for **Chicago, Illinois** |
| United States/Illinois/*/ | datasets at **city level** for **multiple cities in Illinois** |

While including so many levels many seem confusing it allows for greater specification,
and with the increasing socio-economic links between a city and 
its metropolitan area this specification is worthwhile.

#### Format column

The main distinction is whether there is a provided API, raw data downloads, (in
.csv/.xml/.json/etc.), or aggregate stats. The aggregate stats are calculated on 
data that is not made available directly.

### Aggregators

Many data sources are themselves data services/bases/warehouses operated by governments or institutions.
These sources are listed in a similar fashion to stand-alone data sets, but contain
multiple topics and levels. These sources are also more likely to provide an API.
Individual data sets of particular interest within these collections can be listed separately to make best usage of this list.

# Contents

| Level | Topics | Status | Description | Format | Source |
|---|---|---|---|---|--- |
| \* | Health | up | Disease burden, Health | raw | [Institute for Health Metrics and Evaluation (IHME)](http://ghdx.healthdata.org/ihme_data)|
| \* / \* / \* / \* | Economics | up | Cost of living user contributed data about cities | aggregate stats (paid API) | [Numbeo](https://www.numbeo.com/cost-of-living/) |
| Africa / \* / \* / \* | * | up | Independent data from African continent | raw | [openAfrica](https://africaopendata.org/) |
| European Union / \* / \* / \* | * | up | EU government open data | API and raw | [EU Open Data Portal](http://data.europa.eu) |
| Canada / \*/ \* | Development | up | National Bank House Price Index | aggregate stats | [Teranet-National Bank](https://housepriceindex.ca) |
| Canada / \* / \* / \* | * | up | Canadian Open Data Inventory | raw | [Open Government Canada](https://open.canada.ca/en/open-data) |
| Canada / Alberta / Edmonton / * | * | up | Edmonton City data | raw | [City of Edmonton Open Data](https://data.edmonton.ca/browse) |
| Canada / Ontario / Brampton / * | * | up | Brampton City data | raw | [OpenGov Brampton](http://www.brampton.ca/EN/City-Hall/OpenGov/Pages/Welcome.aspx) |
| Canada / Ontario / Toronto / * | * | up | Toronto City data | raw | [City of Toronto Open Data](https://www.toronto.ca/open/) |
| Canada / Ontario / Waterloo / * | * | up | Waterloo City data | raw | [City of Waterloo Open Data](https://www.waterloo.ca/en/government/opendata.asp) |
| Canada / Ontario / Waterloo / * | Infrastructure | up | Trails pedestrian and cyclist counts | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/5d41afff252e45b5b5fe7fc3fd5df3ab_0) |
| Canada / Ontario / Waterloo / * | Infrastructure | up | Traffic Closures (1/16/2017-7/10/2018) | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/4af7c514f77b48db93ce0d0649a31aa9_0) |
| Canada / Ontario / Waterloo / * | Infrastructure | up | Road Traffic Volumes | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/426089c5166c4f8f8f4000acb2fef840_0) |
| Canada / Ontario / Waterloo / * | Infrastructure | up | Sidewalks | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/01031a7c9b5a4aac96c69bb7cb168971_0) |
| Canada / Ontario / Waterloo / * | Infrastructure | up | Bridges | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/dbf3911099e44e18aecec1b564abf518_0) |
| Canada / Ontario / Waterloo / * | Development | up | Buildings | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/22a535f4d8ca4b0da4eb7432ddefe815_0) |
| Canada / Ontario / Waterloo / * | Development | up | Community Gardens | raw | [City of Waterloo Open Data](https://hub.arcgis.com/datasets/b35d2d768bbb4abb84bf4cef61e43e2c_0) |
| Canada / Ontario / Waterloo / * | Development | up | Libraries | raw | [City of Waterloo Open Data](https://opendata-city-of-waterloo.opendata.arcgis.com/datasets/d137da7d38c14b3aa0fd42ab3a4cebad_0) |
| Canada / Ontario / York Region / * | * | up | York Region data | raw | [York Region Open Data](http://www.york.ca/wps/portal/yorkhome/yorkregion/yr/statisticsanddata/opendata/opendata/) |
| Germany / ? / ? / | Development | up | energy consumption of 107 municipal buildings | raw | https://im.iism.kit.edu/sciber.php |
| Switzerland / Zürich / Zürich / * | * | up | City of Zürich open data | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/) |
| Switzerland / Zürich / Zürich / * | Development | up | Social housing construction | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/gemeinnuetzigerwohnungsbau) |
| Switzerland / Zürich / Zürich / * | Development | up | Construction activities since 2009 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/bau_neubau_whg_bausm_rinh_geb_projstatus_quartier_seit2009_od5011) |
| Switzerland / Zürich / Zürich / * | Development | up | Completed and demolished apartments since 2009 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/bau_neubau_whg-abbr-neu_eigart_quartier_seit2009_od5021) |
| Switzerland / Zürich / Zürich / * | Development | up | Completed and demolished apartments since 2009 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/bau_neubau_whg-abbr-neu_eigart_quartier_seit2009_od5021) |
| Switzerland / Zürich / Zürich / * | Development | up | Residences by property type and age group since 2008| raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/bau_best_whg_pers_alter_quartier_neubauart_gemeinnuetzig_seit2008) |
| Switzerland / Zürich / Zürich / * | Development | up | Cinema locations 1907-2018 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/kinostandorte-zwischen-1907-und-2018) |
| Switzerland / Zürich / Zürich / * | Environment | up | Air quality 1983-2012 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/luftqualitaet-historisierte-messungen) |
| Switzerland / Zürich / Zürich / * | Infrastructure | up | City energy consumption 1990-2016 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/ugz_endenergiebilanz) |
| Switzerland / Zürich / Zürich / * | Infrastructure | up | City primary energy balance 1990-2016 | raw | [Stadt Zürich](https://data.stadt-zuerich.ch/dataset/ugz_primaerenergiebilanz) |
| United States / \* / \* / \* | * | up | US Federal government open data | API and raw | [Data.gov](https://www.data.gov) |
| United States / \* / \* / \* | Development | up | MicroSoft US Building Footprints | raw | Links on Github [Microsoft/USBuildingFootprints](https://github.com/Microsoft/USBuildingFootprints) |
| United States / Massachusetts / Cambridge / * | * | up | City of Cambridge data | raw | [www.cambridgema.gov](http://www.cambridgema.gov/departments/opendata) |
| United States / Massachusetts / Cambridge / * | Development | up | Cambridge property database | raw | [www.cambridgema.gov](https://data.cambridgema.gov/Assessing/Cambridge-Property-Database-FY2017/u7pm-vxas) |

## Sources to look through

- http://www.pewinternet.org/datasets/
- https://www.openicpsr.org/openicpsr/search/studies
- https://datahub.io/search
- https://github.com/awesomedata/awesome-public-datasets
- https://github.com/datasciencemasters/data
- https://www.reddit.com/r/datasets/
- https://github.com/CityofToronto/vz_challenge
- https://www.icpsr.umich.edu/icpsrweb/ICPSR/search/studies
- https://github.com/City-Bureau/city-scrapers
- https://github.com/citygram/citygram-services
- http://dataportals.org/
- https://www.openicpsr.org/openicpsr/search/studies
- https://registry.opendata.aws/
- http://www.economagic.com/

# City Data Collection Projects

- https://www.citygram.org/
- http://budgetpedia.ca/
- http://www.greenbuttondata.org

# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Thomas Stesco has waived all copyright and 
related or neighboring rights to this work.
