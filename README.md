# Semantic Web Project
This project aims to exploit the technologies of Semantic Web.
For this project we used geospatial data and displays in a web application,
For the GeoSpatial data that we have to consider, we have to consider the TGVStations.
So for that we convert raw data (csv) from Gare des Train to graph data (RDF) / FromCSVTORDF
You can find data that we extract to RDF data in the files, like TGVStations.ttl, TrainStations.ttl StasStations ...
These data to generate use an ontology SGTO.ttl (Special GeoThing Ontology) which is designed to better define geo-spatial data (Like TGV stations), moreover you can consult this data which will be used in our Triplestore / TGVStations



Regarding the FrontEnd part we have to develop a Web application that allows to exploit this RDF data, in fact:
We can display this data in a table and also in a Maps. (SELECT querry)
We can manipulate this data by adding new TGV stations or removing stations (UPDATE querry)
You can display specific TGV stations (SELECT querry)

This web application also uses RDFa in the data tables of TGV stations.

## Our team contains 2 members:


|Name|  Domain |  Master |  
|---|---|---|
|Morad BENKARAACHE |  CPS2 |  M2 | 
|Fares DABBEK| DSC  | M2  |

## Project structure

```
.
├── DynamicWebSiteForRDF
│   ├── DynamicWebSiteForRDF
│   | ├── src
│   | ├── serverEC2.py
│   └── V2 
│     ├── client.py
│     └── serverEC2.py
├── SemanticWebProject-Morad-and-Fares
├──  README.md 

└── Image process
    ├── ProcessingImageDirectory
    ├── client.py
    ├── Moon.jpg
    └── serverEC2.py

```

# Requirments

## Configuration Apache Jena Fuseki 

You have to install fuseki [Click here](https://jena.apache.org/download/index.cgi)


## The ontology:

You can found the ontology ine the file (SGTO.ttl):

## Java:
you have to install java, for this:

-windows:
follow the insructions here [Click here] (https://www.java.com/fr/download/help/windows_manual_download.html)

-linux:
you have to run this line  ``` $ sudo apt-get install default-jre to install java ``` in the command line 


## Tomcat
You have to install tomcat [Click here] (https://tomcat.apache.org/download-90.cgi):

## Apache
You have to install appache [Click here] (https://httpd.apache.org/):

## IDE eclipse JEE 

You have to install an IDE to open the project (we used eclipse version JEE) 


## How run the application

-You have to clone the project from this adress "https://github.com/", you can clone it using the command line or download it directly from the website in a zib format
-You have to install an IDE to open the project (we used eclipse version JEE) 
-You have to run fuseki, you should be able to test Fuseki by running ./fuseki-server --mem /TGVStations (TGVStations is the name of the dataset)
-You have to run fuseki inteface  http://localhost:3030/
-You have to upload into the dataset TGVStations the file (the name of the file) contains the rdf graph 


you can test the fonctionilities of the project:

1/ see all the train stations (with the map)
-add a new train station
-select a train station
-delete a train station






-Run the project by 
-You have to access to localhost:8080 to display the project




