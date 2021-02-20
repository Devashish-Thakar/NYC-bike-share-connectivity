# NYC-bike-share-connectivity
Analysis of impact of subway connectivity and station network on bike share metrics in NYC
This a performance analysis of the NYC bike share system operated by CITI in cooridination with LYFT
The goal of this project was to udnestand if the connectivity of bike stations to other bike stations (in terms of the number and distance from each other) as well as connnectivity with existing standard transportation (subway stations) has an impact on the usage patterns of bikes
It includes data gathered from a variety of sources such as CITI bike operated bike share platform, Open Bus Project, Metropolitan Transportation Authority, Weather Channels etc.
Includes several interesting application of useful python packages such as:
- sklearn.neighbours for calculating the distance between bike stations and between bike and subway stations to calculate distance related agglomeration
- statistical modelling techniques for impact of stockouts on the demand. Utilizes various canonical techniques lile PLS regressions, Negative binomial regressions, Boosted Tree regressions, random forests etc.
- includes a comparative analysis of the various techniques mentioned above
- econometric modelling to understand the impact of the connectivity measures on the bike stockouts
- various interesting ways of slicing and dicing data to understand the overall bike share system's performance!
- cool visualizations to simultaneously understand the performance (a sort of statistical/econometric model-free-evidence!)
