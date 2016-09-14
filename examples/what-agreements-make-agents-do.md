## What Agreements make Agents do
![What Agreements make Agents do](https://github.com/nicholascar/agr-o/blob/master/examples/what-agreements-make-agents-do.png)

Agreements, like Creative Commons' Licenses, require Requirements (subclass of skos:Concept) which ask actions of an Agent. Unlike CC Requirements which ["may or may not be requested of you"](http://labs.creativecommons.org/demos/ns/), the level of the Requirement (the extent to which it is imparative) is qualified by the value of an Imperative (also subclass of skos:Concept) class instance that is related to the Requirement. The Imperative instances given in this AGR-O match the keywords given in [RFC2119](http://www.ietf.org/rfc/rfc2119.txt).

Every Agreement must have at least one Requirement and every requirement can have one and only one Imperative.

All of these relationships and restrictions are indicated in Figure A.


#### Namespaces
Prefix | URI
------ | ---
agr | http://promsns.org/def/agr#