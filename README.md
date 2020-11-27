# 2020 Presidential Election County Level Analysis and Predictor

As I watched the results of the 2020 election roll in and saw news anchors frantically scribbling on big touch screen maps, I started to wonder why some counties in states went for Trump and others for Biden. There are obvious trends that people who pay attention to politics are familiar with, such as the fact that counties with big cities tend to vote for Democrats and rural areas tend to vote Republican, but I wanted to know more about the characteristics of each of these counties. The big question I wanted to answer was ‘What characteristics of a county were most predictive of whether that county voted for Trump or Biden?’
  
To answer this question I collected data from a number of different sources, from the Bureau of Labor Statistics to the US Census, and centralized it in a single dataset. I then created some interactive maps displaying information about each county, created some plots, and finally built a random forest model to learn which features were most important in determining whether a county voted for Biden or Trump.

The accompanying notebooks contain the code I used to merge and clean my data and the code I used for my analysis, visualizations, and model building. I have also included a Data folder with the the datasets I used for this project. The original datasets I downloaded from sources such as the US Census are not included because these datasets contained more information than I needed which made them very large. However, I have included cleaned versions of those datasets.

#### Data Sources:
Covid data collected from USAFacts: https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/

County level unemployment data collected from The Bureau of Labor Statistics: https://www.bls.gov/lau/#tables

Median Income and Poverty data collected from The US Census SAIPE Program (2018 Estimates): https://www.census.gov/data/datasets/2018/demo/saipe/2018-state-and-county.html

Education data collected from The USDA Economic Research Service: https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/

Racial and gender demographics data collected from the US Census: https://www.census.gov/data/tables/time-series/demo/popest/2010s-counties-detail.html

County land area data collected from the US Census: https://www.census.gov/library/publications/2011/compendia/usa-counties-2011.html#LND

Median Age data collected from the US Census: https://data.census.gov/cedsci/table?q=median%20age&g=0100000US.050000&tid=ACSST1Y2019.S0101&hidePreview=false

Veterans data collected from the US Census: https://data.census.gov/cedsci/table?q=Veterans&g=0100000US.050000&tid=ACSST1Y2019.S2101&hidePreview=false

Population change data collected from the US Census: https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/

County-level election results collected from GitHub repo: https://github.com/tonmcg/US_County_Level_Election_Results_08-20/blob/master/2020_US_County_Level_Presidential_Results.csv
