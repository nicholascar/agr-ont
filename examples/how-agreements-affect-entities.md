## How Agreements affect Entities
![How Agreements affecte Entities](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-affect-entities.png)

Unlike Agreements that did affect data, Agreements affecting data (i.e continuing to have an affect) are not a provenance scenario since it is not in the past, thus PROV-O relationships cannot be used. The simplest construct is given in Figure A which is the same as a provenance scenario except that the data is not *wasAttributedTo* but continues to be related to an Agent (best represented as a foaf:Agent, not a prov:Agent to avoid confusion) through a relationship with currency, such as a *dct:publisher*. Of course, many other data/Agent relationships with currency can be used.

#### Namespaces
Prefix | URI
------ | ---
foaf | http://xmlns.com/foaf/0.1/#
org | http://www.w3.org/ns/org#
agr | http://promsns.org/def/agr#