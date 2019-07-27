# EU_Unemployment_2007_2018
Project where we take a tsv provided by the EU an we create a map for each year from 2007 to 2018 with the unemployment rates in each country and build a gif file with it. We use folium especially choropleth for maps, pandas to manage data, selenium to open each html file and save it as png and imageio to turn those images into a gif file. #Python #folium #pandas #selenium #imageio #unemployment #EU

All you have to do currently is execute the file "UnemploymentInEU.py" in the folder "code"
This will look for the tsv file to get the data and get the json file. Both are in the folder "data": "eu-countries.geo.json" contains the information for folium to highlight all European countries and "tps00203.tsv" will provide the data with the unemployment rate in each country from 2007 to 2018.

With folium and its library choropleth we generate a html file with a map where the unemployment rate for eatch country in the EU is represented in different colours for each year in folder htmlFiles. After the html file for each year is generated, we open it in a browser and get a png screenshot using selenium and save them in folder pngFiles.

We get all these png files and generate a gif file using the library imageio in our project folder

