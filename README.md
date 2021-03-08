README.md
MSDS 6306: Doing Data Science - Case Study 01
***

# Group Members
***
* Kebur Fantahun
* Ricco Ferraro

# Introduction 

## Restatement of problem
With the beer data given by Budweiser, this report will depict the apparent relationship between alcohol by volume(ABV) and international bitterness units(IBU) for a myriad of beers across the United States. The report also provides summary statistics such as minimums, medians and maximums with respect to ABV and IBU, as well as a deeper look in to the difference between IPA's and "Other Ale's"(any beer with Ale in the name) with respect to ABV and IBU. The research group reveals information that could be useful to Budweiser concerning the ounces of beers as they relate to each state of the US.

## Dataset
The beers and breweries datasets provdided by Anheuser-Busch InBev contain information about 2410 US craft beers and 558 US breweries. The datasets descriptions are as follows. 

**Beers.csv**
- list of 2,410 craft beers and their attributes.
- Name: Name of the beer
- Beer ID: Unique identifier of the beer
- ABV: Alcohol by volume of the beer
- IBU: International Bitterness Units of the beer
- Brewery ID: Brewery id associated with the beer
- Style: Style of the beer
- Ounces: Ounces of beer

**Breweries.csv**
Breweries.csv list of 558 breweries within the United States and their attributes.
- Brew_ID: Unique identifier of the brewery.
- Name: Name of the brewery.
- City: City where the brewery is located.
- State: U.S. State where the brewery is located

## Folder & File Information
- `/Data` contains the beers and breweries data
- `/CodeBook` contains the generated codebooks for our beers and breweries data
- `/Html` contains the knit Html Report for our Analysis
- `/Presentation` contains our powerpoint slide deck
- `/src` contains our R-Markdown (RMD) source code

## Instructions to Run our code locally
1. Clone this repository to the directory of choice
2. Make sure that you have installed R and RStudio. 
3. Open `BeersAndBrews.Rmd` in RStudio
4. Use the RStudio Package installer to install the following packages from CRAN AND ensure that you are running the same version of R (4.0.2)
![image](https://user-images.githubusercontent.com/13544830/110293890-fdd62a00-7fa3-11eb-8305-94bd48167a3a.png)
5. Run All chunks in R-Studio. 


