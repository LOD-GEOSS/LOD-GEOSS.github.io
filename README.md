# LOD-GEOSS.github.io
## Using Linked Open Data and the Global Earth Observation Systems of System in Energy Systems Analysis

![LOD-GEOSS Logo](images/LOD-GEOSS_Logo_small.png)

[https://lod-geoss.github.io/](https://lod-geoss.github.io/) is the open dissemination channel for the LOD-GEOSS project. 
## Documents and Code


Our githup repostiroy can be found here [https://github.com/LOD-GEOSS/](https://github.com/LOD-GEOSS/). 

- Architecture Condept [https://github.com/LOD-GEOSS/LOD-GEOSS.github.io/blob/master/documents/LOD-GEOSS%20M1%20Archtecture%20Concept_v0.9.2_Second_public_draft.pdf](https://github.com/LOD-GEOSS/LOD-GEOSS.github.io/blob/master/documents/LOD-GEOSS%20M1%20Archtecture%20Concept_v0.9.2_Second_public_draft.pdf)
- Deliverable D4.2 Best-Practice Guide GEOSS/Copernicus [https://lod-geoss.github.io/documents/LOD_GEOSS_D4_2_final.pdf](https://lod-geoss.github.io/documents/LOD_GEOSS_D4_2_final.pdf). 
- Our Paper about the Open Energy Ontology [https://www.sciencedirect.com/science/article/pii/S2666546821000288](https://www.sciencedirect.com/science/article/pii/S2666546821000288)

## Content
### Challenges

Modeling in energy systems analysis needs a lot of data from a variety of different sources: 
* Meteorological time series for renewable power generation, 
* Electricity demand from the transparency platforms, 
* Technology data, 
* Socio economic data, 
* Geographical land use data, 
* etc. 
There are a lot different sources available, but they are sometimes hard to find and each has different ways of accessing the data and different ways how data fields are defined. 

### Learning from Earth Observation and Linked Open Data
Similar problems arose in earth observation about two decades ago. The answer was the development of a distributed data infrastructure for Earth Observation data, the Global Earth Observation Systems of Systems (GEOSS). Data could be found through data catalogs, where providers registered their metadata and ways of data access could be discovered though standardized interface descriptions as e.g. WSDL (Web Service Description Language). 
As the data stayed within the hosting institutions, these institutions stay responsible for the data and data maintenance, which eases legal questions and updates of the data. The idea is the development of a networked data base concept based on the ideas of linked open data and the semantic web for input and output data of energy system models in energy systems analysis. 

### Development of a Distributed Data Architecture

![Architecture](images/database-provenance-tracking.02.png)

Based on the [DBpedia Databus](https://databus.dbpedia.org/about) we want to create an infrastructure to share data in the domain of energy systems analysis. The idea is to share the metadata on the Databus which contains links to the acutual repositories of the shared data. The databus creates a persistent data id which can be used to link data sets. These will be enriched by provenance information, which tracks the information who has been modifying or creating the data by which tools. In the end, all published data should be tracable back to its originating data sets.  

The project keeps its public results in [this Wiki](https://github.com/LOD-GEOSS/LOD-GEOSS.github.io/wiki).

## Project Partners

![DLR](images/DLR_Logo_engl_small.png) 

German Aerospac Center, [Institute of Networked Energy Systems](https://www.dlr.de/ve) (Co-ordiination), [Institute of Software Technology](https://www.dlr.de/sc)

![RLI](images/RLI_logo_small.png) 

[Reiner Lemoine Institute](https://www.rl-institut.de)

![Inf_AI](images/InfAI_logo_ENG_small.png) 

[Leipzig University - Institute of Applied Informatics](https://infai.org)

[Potsdam Insitute for Climate Impact Research](https://www.pik-potsdam.de)

[Forschungszentrum Jülich](https://www.fz-juelich.de)

![IER](images/IER_Logo.png) 

[Stuttgart University - Institute for Energy Economics and Rational Energy Use](https://www.ier.uni-stuttgart.de/en/)

## Contact

contact: carsten.hoyer-klick@dlr.de 

## Funding

This project is supported by the BMWi - Federal Ministry for Economic Affairs and Energy

![BMWi_Funding](images/supported_by_BMWi.png)

Research Grant 03EI1005A-G

## License

* All software in the git repository is licensed under MIT
* All content in the wiki is licensed under CC-BY 4.0

## Imprint

Imprint according to Section 5 Telemediengesetz (German Telemedia Act) and Section 18 Medienstaatsvertrag (German State Media Treaty)

Deutsches Zentrum fuer Luft- und Raumfahrt e. V.
German Aerospace Center (DLR)
Linder Höhe
51147 Köln (Cologne)
Germany

Tel: +49 2203 601-0
Fax: +49 2203 67310

email: contact-dlr [at] dlr.de

https://www.dlr.de/en

DLR's Executive Board is empowered to act as DLR's representative. It consists of Prof. Dr.-Ing. Anke Kaysser-Pyzalla (Chair of the DLR Executive Board), Klaus Hamacher (Vice Chairman of the Executive Board), Prof. Dr.-Ing. Karsten Lemmer and Dr.-Ing. Walther Pelzer.

Seat of the Executive Board

The Executive Board's seat is located at DLR, Executive Board, Linder Hoehe, D-51147 Cologne.

The Executive Board can also authorise DLR employees to act on behalf of DLR. The head of DLR's legal department, Linder Hoehe, 51147 Cologne, can provide information about the extent of this authorisation.

Court of registration/registration number
District court of Bonn, VR 2780.

Value added tax identification number
DE 121965658

Responsible in the sense of Section 18 2nd paragraph of Medienstaatsvertrag (German State Media Treaty)
Carsten Hoyer-Klick
Institute of Networked Energy Systems
Curiestr. 4
70563 Stuttgart
Germany

Liability

According to section 7 first paragraph of the German Telemedia Act, DLR as the content provider is responsible for its own content which it provides for use on this website lod-geoss.github.io, in accordance with the general laws. Cross-references ("links") to content provided by other content providers must be distinguished from DLR´s own content. By means of the cross-reference DLR provides third-party content for use which is marked accordingly by the indication "[external]" or by a link. Before setting the link DLR checks this third-party content if it causes possible civil or criminal liability. However, it cannot be excluded that the third-party content providers change their content afterwards. DLR does not constantly check the third-party content it refers to for changes made by the third-party content providers which could engender DLR´s civil or criminal liability. If you believe that the linked external sites violate applicable laws or otherwise have inappropriate content, please let us know.
