# README #

### Repository for: 

* Team Project 1: RDF
* Spatial Team Project
* Database 2 Course

### Spatial team members 
* Alberto Piva, alberto.piva.8@studenti.unipd.it;
* Gianmarco Prando, gianmarco.prando@studenti.unipd.it;
* Laura Menotti, laura.menotti@studenti.unipd.it.

# About this project 
**What is the domain that the ontology will cover?**  
European air traffic, in paricular we care about the flights, airports, airlines and their aircrafts.

**Who will use the system?**  
The system will be used by workers related in this specific field.

**Why they will use and maintain the ontology?**  
To seek the most convenient places and markets to expand.  

**Detailed composition of the scheme of the system:**  

* Airline  
* Aircraft  
* Aircraft Model  
* (Aircraft) Manufactuer  
* Flights  
* Airport  
* City  
* Country  

**For what type of questions the information in the ontology should provide answers?**  
A lot of answer can be retrieved from this air traffic control database, for example:  

* Airline: how much and what aircraft they own;  
* Manufacturer: who and where an aircraft model is built;  
* Aircraft: how much fligh hours it has done and how much city a specific aircraft has visited;  
* AircraftModel: how much aircrafts have been produced for every different model type;  
* Airport: what are the most trafficed city;  
* MarketSegment: what is the percentage of flights for each market segment;  
*  Use-case: some example of specific queries to a choosen airline: EasyJet.  

# How to use it

In this section we add a smart guide to explain how run the developed system.  

**1. Run the whole system**  
If you do not want to run the whole system and you want only import the serialized (ttl) files into GraphDB skip
 this section and go to section 2.  
 
* Unzip "data.zip" file into aritrafficDB folder to get all the csv files;
* Run the "populateAirtrafficRDFdb" Python Notebook (note: you need rdflib library installed).  
Note that you have to run the first 3 cells and then you can decide if you want to run all the section or only some of them.

**2. Run GraphDB database**  

* If you have skipped the section 1 you have to unzip "rdf.zip" file into aritrafficDB folder to get all the serialized files (ttl)
 otherwise they have been generated in section 1;  
* Open GraphDB and create a new database;  
* Import all the ttl files into the rdf folder and the ontology "airtrafficOntology" and enjoy!
