# Environmental Justice in Kern County: The Effects of Oil Drilling Operations on Communities
**Group Members**: Nick Stewart-Boch, Melody Ng, Dinah Dominguez, Yesenia Becerra

[Group Github Repo](https://github.com/ybecerra29/up221groupproject)

# PROPOSAL

## Problem Summary
We are examining how oil drilling in Tulare and Kern Counties impacts the surrounding physical environment and the health of those in close proximity to drilling sites. Tulare and Kern Counties constitute large portions of the Central Valley, one of the key centers for agricultural production in the US. It is also the site of extensive oil drilling in the state, often on oil fields that overlap with agricultural land. This raises questions we hope to answer about how oil drilling in this environment affects water and soil quality, and by extension, the produce that is eaten throughout the country. Furthermore, we hope to also examine how this affects nearby residents and farmworkers who might work in close proximity to these drilling sites. 

Oil drilling not only contributes to carbon emissions but increases the health risks for those in close proximity to drilling sites. In Los Angeles County, this has become abundantly clear by the disproportionately higher rates of respiratory illness in areas such as Wilmington and West Adams among residents close to oil derricks. It is also important to note that these areas tend to also be populated by predominantly low-income communities of color. The detrimental health impacts of drilling has catalyzed a sustained local environmental justice movement, led by actors such as Stand Together Against Neighborhood Drilling (STAND), to halt drilling within the region and remediate idle wells which also emit toxic fumes. Their efforts have led to policy that phases out oil drilling within the city of Los Angeles. With an increase in development and population growth in the Central Valley, we seek to interrogate the negative health effects of similar drilling sites.

Much of the recent success of environmental justice organizers has been concentrated in the LA region, so we turn our sights instead to oil drilling in the Central Valley where it is the most concentrated: the contiguous Kern and Tulare Counties. 

## Question of Interest
How does the presence of oil drilling operations in an area affect soil quality/health and public health outcomes for residents in nearby communities?
Update: We may narrow our research on health to focus on specific health outcomes (based on available health data for CalEnviroScreen), given that good quality data that is available at the census tract level for Kern County seems to only be found in CalEnviroScreen. We are also likely to expand our research on the more envirommental impacts -- looking at water health and watershed boundaries (proximity to cropland and oil wells) to see how the waste from extraction activities might be traveling throughout the county, and at other extraxtion infrastructure like the location of refineries and major roads where freight transportation (which also impacts health in the same way that oil and gas operations do).

## Scope
We will likely be comparing variables of interest in both counties at the census tract level. We are waiting until we've had more time to explore what data is available to answer our question(s) of interest to decide whether there is enough complete data to do comparisons across years (likely within a decade), or whether we will need to limit our inquiry to a "snapshot in time" (likely a given year between 2017 to 2022).
Update: We're just focusing on the most recent data for one year (~2020, ~2021)

## Data
We will be analyzing well data from the California Department of Conservation using their [Inland District](https://www.conservation.ca.gov/calgem/maps/Pages/GISMapping2.aspx) data to capture Tulare and Kern County sites. We will be using data downloaded from [CalEnviroScreen 4.0](https://oehha.ca.gov/calenviroscreen/report/calenviroscreen-40) to identify direct and proxy variables for "environmental risk exposure and outcomes", including levels of water contamination, respiratory illness rates, exposure to hazardous waste, and other socioeconomic variables including housing burden and poverty rates within both counties. We will likely complement these data with data from U.S. Census on occupational and income distributions within certain census tracts using [Social Explorer](https://www.socialexplorer.com/explore-maps). We are still searching for comprehensive soil quality data. Lastly, we will be using [Kern](https://geodat-kernco.opendata.arcgis.com/datasets/ef97f3180f214f798bf188e160ccce3c_0/explore?location=35.364986%2C-118.976816%2C12.33) and [Tulare](https://tularecounty.ca.gov/rma/planning-building/zoning-entitlements/gis-data/) County land use data. 

## Objectives
We hope to better understand the relationship between oil drilling, environmental risk exposure, and land and community health outcomes for the residents in Kern and Tulare Counties. Kern and Tulare are top agriculture producing counties in areas of the state that are simultaneously known as "the breadbasket of the world" and yet often adjacent to/bounded by oil drilling operations. These counties are home to a large population of farmworkers, and we hope to understand the different ways that oil drilling has impacted them and potentially the community at large.



# ROLES
Yesenia (occupation, health outcomes, income): I’ll be working on pulling income, and occupation from the census tract data and seeing how that correlated with  

Dinah (demographic data): I'll be working on income data and census tract data.

Melody (Ag, Oil Well, and Health Data Wrangler): I've been exploring the CalEnviroScreen data to identify what kind of health and environmental risk/impact measures we can pull from it. I’ll be working on pulling usable health from CalEnviroScreen to create maps, helping Nick parse and map oil well data, and identifying, exploring, and attempting to map any usable agricultural data for Kern County (e.g. crop land boundaries) in case there is any opportunity to do some analysis about distances between oil wells and agricultural lands in the county.

Nick (oil, water, land use) I have been mapping oil data in interactive maps by well status. I have been trying to merge oil well data with social explorer census data but it is hard to tell if it is working given computer issues. I did merge oil data with CalEnviroScreen but the dataset became too big for Jupyter. Ideally, if there is a way of making it work, it would be great to provide spatial statistics of oil wells with health outcomes and environmental issues like poor quality.

# PRE-MIDTERM STATUS UPDATE
Yesenia: I am personally having trouble working through data errors while coding, and seeing how data is not directly demonstrating or translating into the maps that I was hoping to showcase for our project. Since most of us in the group are having similar issues, we’ve spent some time troubleshooting and are still working through those issues on our own. I think we’d benefit from having a standing call for check in and troubleshooting together. 

Dinah: I am personally having trouble working on coding on my own. Office hours are helpful but I get discouraged when I can’t troubleshoot issues on my own. Meeting weekly with the team to get updates and check in is helpful. 

Melody: I think we’re all feeling a bit disconnected, and it’s personally been difficult to see how some of the pieces we’re working on now as individuals will fit together. Would like some group efforts to improve communication, so we know what our expectations are, where we’re all at, and maybe create space to share concerns about coding so that those concerns can be addressed and we can move more effectively as a team together toward the finish line. Also would like to check in about being more strategic about how we're using our individual assignments to support what we'll have to produce for the mideterm and final.

Nick: I think I am getting the hang of coding a bit more for subsetting but am similarly feeling like our parts are a bit disconnected and am getting pretty frustrated with being unable to move to the mapping process because of computer issues, so am feeling somewhat stuck currently. 

# DATA UPDATE
1. Oil wells data has been subsetted to include just idle, active, and new wells in the county. This still is around 70,000 values so there is a lot of point data there. 
2. CalEnviroScreen seems to have all the health/environmental data we need for this project, but we are still working on making it mergeable with our other data.
3. Currently, discussing which other demographic data to incorporate in our project (and potentially agricultural). *https://data.census.gov/all?q=kern+county+income*
*https://geodat-kernco.opendata.arcgis.com/datasets/139e0aecdb274d55ba41dccd12c5f929_0/explore?location=35.290957%2C-118.838175%2C8.98*

Our group is looking at the effects of oil drilling operations like refineries and oil drilling on the health of communities and sensitive receptors located near to these operations. We identified some areas of particular interests like occupational health hazards of workers like farm workers and racial, socio-economic vulnerabilities that highlight risk for environmental injustice in communities in Kern County.

# CONCERNS
**Major:** 
1. Oil Wells data is huge and diffic
2. Familiarity with CalEnviroScreen and Census data that can help generate helpful maps that address our major research questions. Troubleshooting coding errors with data that is available. 

**Minor:** Honing in on our research questions based on the data that we have worked through in our jupyter notebooks. 

We have identified several research questions to help us answer the big question: How do oil wells affect health in Kern County?
1. How do occupations of residents in the county relate to health outcomes? Does working near oil wells make you more vulnerable to negative health impacts?
2. How do income/poverty rates in the county relate to health outcomes? How might they impact the relationship between oil wells and health? How are they related to occupational environmental health risks?
3. Do the location of oil wells relate to the occupation of residents in nearby areas?
4. What kind of relationship is there between zoning (agricultural or otherwise) in the county and oil well locations? How might this affect local and largerscale health outcomes?



