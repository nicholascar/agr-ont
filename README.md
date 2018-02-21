# AGR-O
The Agreements ontology

## Introduction
This Agreements Ontology is designed to model 'agreements' which are social contracts that include licenses, laws, contracts, Memoranda of Understanding, standards and definitional metadata.

Agreements' purposes are to effect the behaviour of Agents that use Entities or undertake Activities. This ontology defines those effects as further actions (Requirment Resolutions) that satisfy stated Requirements articulated within the Agreement. The Requirement Resolutions can compelled to be performed with one of a number of different Imperatives such as MUST, SHOULD etc.

This ontology's purpose is to support data sharing by making explicit the relationships between agreements and data, agreements and actions and agreements and Agents (people and organisations). Eventually it will also help with the interplay between different classes of agreements.

We think of this ontology as a 'middle' ontology, that is one which specializes well-known, upper and other middle ontologies and is able to be used fairly widely but is expected to be used particular contexts in conjunction with detailed, domain-specific, lower ontologies. We have tried to rely on existing agent, data manipulation, metadata and licence ontologies where possible. As such we specialise the [FOAF](http://xmlns.com/foaf/spec/), [PROV](https://www.w3.org/TR/prov-o/) and [Creative Commons](https://creativecommons.org/ns) ontologies.


## Ontology document
Turtle format: [agr.ttl](agr.ttl)  
RDF XML format: [agr.rdf](agr.rdf)  
OWL XML format: [agr.rdf](agr.owl)  
HTML format: [agr.html](agr.html) and presented online at it's namespace URI location: <http://promsns.org/def/agr>


## Examples
Here are a series of examples of the ontology's use in relation to data, people (Agents) and so on.

**NOTE**: these examples are for v1.2 and some classes and properties have been renamed in v1.3 These examples will shortly be updated to align with v1.3.

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
*Senior Experimental Scientist*  
CSIRO Land & Water    
<nicholas.car@csiro.au>  
<http://orcid.org/0000-0002-8742-7730>
