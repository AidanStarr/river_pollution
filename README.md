# Are English rivers becoming more polluted?
I wanted to investigate the recently reported decline in British river quality further. Are rivers getting more polluted? Are there regional or even local differences in the state and trends of our rivers? Luckily for me, the UK government has been quietly measuring hundreds of water quality indicators at sites across the country for over 20 years. Something like 58 million measurements made on nearly 4 million samples taken from over 58 thousand locations are now available between the years 2000 and 2016. This data is freely available through the [Water Quality Data Archive](https://environment.data.gov.uk/water-quality/view/doc/reference#Introduction), either as `.csv` files or through a `REST` style API. 

### This workbook
In this exploratory analysis, I wanted to use the government's Water Quality Data Archive to better understand what's really happening to our waterways. To do so, I access the entire dataset and then group the measurements by region and area. I also chose to only look at every 4 years between 2000 and 2016.

In addition to the water quality measurements, I also accessed some shapefiles for UK river catchments and some useful regional boundaries from [the Ordinance Suvery Open Rivers dataset](https://www.data.gov.uk/dataset/dc29160b-b163-4c6e-8817-f313229bcc23/os-open-rivers). That way, I can characterise the data based on regiona and drainage basin.

### Next steps
There are clearly some interesting trends underlying this data, and the take-home conclusions are regionally and temporally nuanced. The plan is to use this initial exploratory analysis to better classify which rivers are getting worse, and which rivers are improving in terms of pollution. 
