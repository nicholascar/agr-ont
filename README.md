# AGR-O
The Agreements Ontology

## Introduction
This Agreements Ontology is designed to model 'agreements' which are social contracts that include licenses, laws, contracts, Memoranda of Understanding, standards and definitional metadata. Its purpose is to support data sharing by making explicit the relationships between agreements and data and agreements and Agents (people and organisations). Eventually it will also help with the interplay between different classes of agreements.

We think of this ontology as a 'middle' ontology, that is one which specializes well-known, abstract, upper ontologies and is able to be used fairly widely but is expected to be used particular contexts in conjunction with detailed, domain-specific, lower ontologies. We have tried to rely on: existing agent, data manipulation, metadata and licence ontologies where possible. As such we specialise the [ORG](https://www.w3.org/TR/vocab-org/) and [FOAF](http://xmlns.com/foaf/spec/) ontologies; the [PROV](https://www.w3.org/TR/prov-o/) ontology;  the [Dublin Core Terms](http://dublincore.org/schemas/rdfs/) RDF schema & [DCAT](https://www.w3.org/TR/vocab-dcat/) ontology; and the [ODRS](http://schema.theodi.org/odrs/) vocabulary & [Creative Commons](https://creativecommons.org/ns) RDF data models for those areas, respectively.


## Ontology document
Turtle format: agr.ttl  
HTML format: *coming soon*


## Examples
Here are a series of images with notes explaining how this ontology can be used for particular relationships. These examples are all described in the SciDataCon publications listed below.

### Agreements <--> Data
In PROV-O, data is a type of prov:Entity.
####[How Agreements are Entities](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-are-entities.md)
####[How Agreements make data or [How Agreements affected Entities](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-affected-entities.md)
####How data is affected by Agreements or [How Agreements affect Entities](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-affect-entities.md)

### Agreements <--> Agents
#### How Agents make Agreements
Since Agreements are a subclass of Entity, the normal PROV-O Entity/Agent relationships apply
#### How Agreements make Agents
Agents are able to be viewed as Entities thus see [How Agreements make Entities](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-make-entities.md)
#### [How Agents are affected by Agreements](https://github.com/nicholascar/agr-o/blob/master/examples/how-agents-are-affected-by-agreements.md)


### Agreements <--> Agreements
*coming - a hierarchy of Agreement types hasn't been made yet*


## Publications
An introduction to this ontology was first published at SciDataCon 2016:
* [paper](http://www.scidatacon.org/2016/sessions/37/paper/185/) 
	* and PDF in references folder: Car2016h-Agreeing-about-Agreements.pdf
* presentation
	* references folder: Car-Box-Agreeing-about-agreements.pptx


## Authors and Contact
Nicholas Car  
Geoscience Australia  
<nicholas.car@ga.gov.au>
  
Paul Box  
CSIRO  
<paul.j.box@csiro.au>