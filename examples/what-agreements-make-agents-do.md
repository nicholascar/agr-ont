## What Agreements make Agents do
![What Agreements make Agents do](https://github.com/nicholascar/agr-o/blob/master/examples/what-agreements-make-agents-do.png)

Agreements, like Creative Commons' Licenses, require Requirements (subclass of skos:Concept) which ask actions of an Agent. Unlike CC Requirements which ["may or may not be requested of you"](http://labs.creativecommons.org/demos/ns/), the level of the Requirement (the extent to which it is imparative) is qualified by the value of a RequirementLevel (also subclass of skos:Concept) class instance that is related to the Requirement. The RequirementLevel instances given in this AGR-O match the keywords given in [RFC2119](http://www.ietf.org/rfc/rfc2119.txt).

Every Agreement must have at least one Requirement and every requirement can have one and only one RequirementLevel.

All of these relationships and restrictions are indicated in Figure A.

### Satisfying Requirements
![What Agreements make Agents do 2](https://github.com/nicholascar/agr-o/blob/master/examples/what-agreements-make-agents-do-2.png)  
In order to indicate that a Requirement has been satisfied, an Agent must generate a RequirementResolution class object. Like a Requirement, a RequirementResolution is subclass of both skos:Concept and of prov:Entity and the latter subclassification means one can be produced (*prov:generated*) by a prov:Activity. In order to know which Requirement a RequirementResolution applies to, the RequirementResolution must have an *agr:satisfies* predicate indicating a particular Requirement class instance. Different Requirements many be satisfied by different RequirementResolutions but no Requirement can require multiple RequirementResolutions simultaneously in order to be satisfied. This is indcated in Figure B.


#### Namespaces
Prefix | URI
------ | ---
agr | http://promsns.org/def/agr#
skos | http://www.w3.org/2004/02/skos/core#
prov | http://www.w3.org/ns/prov#