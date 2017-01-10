# AGR-O
The Agreements ontology

## Introduction
This Agreements ontology is designed to model 'agreements' which are social contracts that include: licenses, laws, contracts, Memoranda of Understanding, standards and definitional metadata. Its purpose is to support data sharing by making explicit the relationships between agreements and data and agreements and Agents (people and organisations). Eventually it will also help with the interplay between different classes of agreements.

We think of this ontology as a 'middle' ontology, that is one which specializes well-known, abstract, upper ontologies and is able to be used fairly widely but is expected to be used particular contexts in conjunction with detailed, domain-specific, lower ontologies. We have tried to rely on: existing agent, data manipulation, metadata and licence ontologies where possible. As such we specialise the [ORG](https://www.w3.org/TR/vocab-org/) and [FOAF](http://xmlns.com/foaf/spec/) ontologies; the [PROV](https://www.w3.org/TR/prov-o/) ontology;  the [Dublin Core Terms](http://dublincore.org/schemas/rdfs/) RDF schema & [DCAT](https://www.w3.org/TR/vocab-dcat/) ontology; and the [ODRS](http://schema.theodi.org/odrs/) vocabulary & [Creative Commons](https://creativecommons.org/ns) RDF data models for those areas, respectively.


## Ontology document
Turtle format: [agr.ttl](agr.ttl)  
RDF XML format: [agr.rdf](agr.rdf)  
HTML format: [agr.html](http://htmlpreview.github.io/?https://github.com/nicholascar/agr-o/blob/master/agr.html)


## Examples
Here are a series of examples of the ontology's use in relation to data, people (Agents) and so on.

### Defining Agreements
* [How Agreements are Entities](examples/how-agreements-are-entities.md)
* [Agreements and their relations](examples/agreements-and-their-relations.md)


### Agreements and Data
 
* [Indicating Agreement / data relationships](examples/indicating-agreement-data-relationships.md)
* How data is affected by Agreements *(coming)*


### Agreements and Agents
* [Indicating Agreement / Agent relationships](examples/indicating-agreement-agent-relationships.md)
* [What Agreements make Agents do](examples/what-agreements-make-agents-do.md)


### Agreements and other Agreements
* *coming* - a hierarchy of Agreement types hasn't been made yet.


### Specific Agreement examples
#### Data sharing agreements
* NSW State Government open data policy *(coming)*
* Australian national biosecurity data sharing agreement *(coming)*
* Future Australian National Data Custodian mandate *(coming)*

#### Licenses
* Creative Commons BY 4.0 *(coming)*
* A custom Australian government license *(coming)*
* A custom commercial data license *(coming)*


## References
An introduction to this ontology was first published at SciDataCon 2016:
* [paper online](http://www.scidatacon.org/2016/sessions/37/paper/185/) 
	* [local copy](references/Car2016h-Agreeing-about-Agreements.pdf)
* presentation
	* [local copy](references/Car-Box-Agreeing-about-agreements.pdf)


## Ontology publication

This ontology is developed jointly by [Geoscience Australia](http://www.ga.gov.au) (GA) and the [CSIRO](http://csiro.au) and it is catalogued in GA's main data catalogue, eCat, at: http://pid.geoscience.gov.au/dataset/103680 (note that this link will only work for parties outside of GA from February, 2017).


## Authors and Contact
Nicholas Car  
Geoscience Australia  
<nicholas.car@ga.gov.au>
  
Paul Box  
CSIRO  
<paul.j.box@csiro.au>