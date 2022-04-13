# dis18_graph_analysis
Graph analysis of a Wikidata graph

In this folder we are taking a first look at the data, returned from Awena. Furthermore we are going to create a data basis for further elaboration on the topic.

## Used tools

For extracting data from Wikidata, we use the inbuild Wikidata Query Service.

https://query.wikidata.org/

## Documentation

### First Step:

Information ressources:
* Run some queries to get a feeling for how SPARQL works
* Get the relevant Data and save it into the according csv files

The queries are saved in the txt file:
* 20220218_WikiAbfrage.txt


### Goal:
* Next meeting: **23.03.2022**
* Being able to start querying with Awena
* Creating a dataframe and collecting all necessary data

## Results
We were able to query for the relevant data and save it into the csv file

Names of the csv files:
* 20220218_AbfrageAcademic.csv
* 20220218_AbfrageMom.csv
* 20220218_AbfragePa.csv

### Update 13.04.22
Merged the SPARQL-Queries into one, using the "OPTIONAL" function.

Created the new file:
* 20220413_SPARQL_ExportV2.csv with around 82.5k entries for the timespan of 1900 to 2000.
* In the next step we will start examining the data and check, if it is sufficient for our requirements.
