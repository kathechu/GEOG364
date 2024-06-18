# Biochar Production in Kenya
### GEOG 364: Spatial Analysis in R
### Fall 2023
## Introduction

The dataset is on the biochar produced by farmers connected with [PlantVillage](https://plantvillage.psu.edu/), which a Penn State lab that I’ve worked with. This dataset is collected by the PlantVillage team which has members in various countries such as Burkina Faso, Thailand, and Kenya. This data is important since the team is interested in increasing biochar production in countries with little arable land to help improve yield while also allowing farmers to take part in carbon offset schemes. In the case of carbon offset, ensuring the accuracy of biochar data improves the credibility of farmers participating in the carbon offset program.

For the purpose of this project I will be reviewing the data within Kenya. I am interested in reviewing the kinds of feedstock used for biochar, the amount of biochar produced, and the difference in time for collecting and uploading the information.

## Conclusions

Throughout the report, I have used biochar data in Kenya to better understand any patterns that may occur. First, I conducted an exploratory analysis by producing charts and maps of the data. When examining the types of feedstock used, the weed, P. juliflora is used the most by farmers, but ultimately corn stalk has a greater output of biochar. I also reviewed the frequency of biochar standard type, which is used for monitoring biochar quality for carbon credits. The majority of the biochar uses the stricter standard, Artisan Pro. As for the locations of biochar production, it occurs in five counties: Baringo, Bungoma, Homa Bay, Kakamega, and Siaya. Biochar is most frequently made in Baringo, with P. juliflora being the county’s main feedstock.

For my point pattern analysis I narrowed down my scope to Siaya county. I found that biochar production mainly occurs in northwestern Siaya, with points appearing more clustered than uniform. Points of biochar production in Siaya tend to be 0.589 km away from each other.

I looked into the potential connection between feedstock and the type of agricultural land. Due to the lack of more biochar data, I could not make a firm conclusion about whether there was a relationship between the two. However, it does appear that corn stalk as a feedstock is common in areas with a vegetation density ranging from 20-40%.

For the regression, I reviewed the relationship between total biochar production and the time of day biochar was made. I decided to use these variables since these were my only numeric marks from the biochar dataset. I did not expect to find a connection between the two, especially since there was little variation in the totals data. In the end, my initial beliefs remained the same, but it was still valuable practice for understanding how to use and interpret the regression functions.

I believe more can be done in future research. With a larger biochar dataset I believe I could do a more comprehensive analysis why certain patterns occur, such as why certain feedstocks occur in a particular region more than others or why a region makes more biochar than other. I can also take a closer look into what areas can produce biochar based on additional factors such as land type, population size, and poverty levels.

## Acknowledgments

* [Dr. Helen Greatrex](https://www.geog.psu.edu/directory/helen-greatrex), for guidance as the GEOG 364 professor.
* [PlantVillage](https://plantvillage.psu.edu/), for providing resources for the research.
