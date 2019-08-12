# Tools and related ontologies
A list of tools that use the LBD technologies and related ontologies


## How to add your own
1. Fork this repository
2. Add your tool/ontology and a description to the readme file
3. Make pull request

## List of tools using LBD ontologies
* [IFCtoLBD](https://github.com/jyrkioraskari/IFCtoLBD) by *[Jyrki Oraskari](https://www.researchgate.net/profile/Jyrki_Oraskari) and [Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel)*:
Converts an IFC file to a Turtle file described using [BOT](https://w3id.org/bot) and optionally PRODUCT, PROPS and GeoSPARQL (georeference of project only).

* [Revit BOT exporter](https://github.com/MadsHolten/revit-bot-exporter) by *[Mads Holten Rasmussen](https://www.researchgate.net/profile/Mads_Holten_Rasmussen)*:
Runs in Revit and exports native objects to a Turtle file described using [BOT](https://github.com/w3c-lbd-cg/bot)

* [ifcOWL to BOT with WKT](https://github.com/kmcglinn/fcOwl2IfcOwlGeo/tree/master/IfcOwl2IfcOwlGeo) by *[Kris McGlinn & Joseph O'Donavan]( http://linkedbuildingdata.net/ldac2019/files/LDAC2019_Joseph_ODonovan.pdf)*:
Runs in Java and exports ifcOWL geometries as BOT with WKT (or OBJ) 

* [LD-R for LBD](https://lbd-demo.herokuapp.com/) by *[Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel)*: a generic Linked Data Reactor (LD-R) web app to view, filter and modify LBD datasets. [Source code](https://github.com/mathib/ld-r)

* [FOG demo web visualizer](https://github.com/mathib/fog-demo-app) by *[Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel)*: conceptual web geometry viewer for geometry descriptions linked to building elements (BOT and PRODUCT) using [OMG](https://w3id.org/omg)/[FOG](https://w3id.org/fog) terminology. Uses three.js for the visualization

* [Revit-triplestore syncronizer](https://github.com/mathib/StardogRevit-synchronizer) by *[Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel)*: a Dynamo app to sync data between an existing RDF dataset in a Stardog triplestore and Revit

## Ontologies closely related to LBD technologies

* [OMG: Ontology for Managing Geometry](https://w3id.org/omg) by *[Anna Wagner](https://www.researchgate.net/profile/Anna_Wagner13) and [Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel)*: linking between concepts (e.g. a building element) and their geometry description(s), between related geometry descriptions and between geometry descriptions and related properties. 

* [FOG: File Ontology for Geometry formats](https://w3id.org/fog) by *[Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel) and [Anna Wagner](https://www.researchgate.net/profile/Anna_Wagner13)*: extension of OMG for geometry schema specific relations to geometry descriptions (e.g. OBJ, Revit geometry, E57, DWG, etc.)

* [BPO: Building Product Ontology](https://w3id.org/bpo) *[Anna Wagner](https://www.researchgate.net/profile/Anna_Wagner13)*

* [IFC-PROPS](https://github.com/maximelefrancois86/props) by *[Maxime Lefrançois](http://maxime-lefrancois.info/me#)*: list of properties extracted from IFC4 psets

* [IFC-PRODUCT](https://github.com/pipauwel/product) by *[Pieter Pauwels](https://www.ugent.be/ea/architectuur/en/contact/staff-members/pieter-pauwels)*: extended version of the minimal LBD PRODUCT ontology, based on IFC product definitions

* HVAC ontology

* PROJECT ontology

## Other tools developed by members of the LBD community

* [SPARQL-visualizer](https://madsholten.github.io/sparql-visualizer/) by *[Mads Holten Rasmussen](https://www.researchgate.net/profile/Mads_Holten_Rasmussen) and [Mathias Bonduel](https://www.researchgate.net/profile/Mathias_Bonduel)*: a tool to foster collaboration during design and dessimination of developed ontologies, by exchanging sample RDF data, explanatory notes and example SPARQL queries related to one or multiple ontologies. [Source code](https://github.com/MadsHolten/sparql-visualizer)
