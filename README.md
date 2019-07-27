# EU_Unemployment_2007_2018
Project where we take a tsv provided by the EU an we create a map for each year from 2007 to 2018 with the unemployment rates in each country and build a gif file with it. We use folium especially choropleth for maps, pandas to manage data, selenium to open each html file and save it as png and imageio to turn those images into a gif file. #Python #folium #pandas #selenium #imageio #unemployment #EU

All you have to do currently is execute the file "UnemploymentInEU.py" in the folder "code"
This will look for the tsv file to get the data and get the json file. Both are in the folder "data": "eu-countries.geo.json" contains the information for folium to highlight all European countries and "tps00203.tsv" will provide the data with the unemployment rate in each country from 2007 yo 2018.

