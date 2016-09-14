## How Agreements affected Entities
![How Agreements affected Entities](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-affected-entities.png)

To make data is a specialised case of affecting data. Once it is made, the data was affected. In PROV-O, data (and Entity) is affected by an event (an Activity).

PROV-O has the simplest relationship between Entities and Activities being *influenced* (inverse: *wasInfluencedBy*) where Entities *influenced* Activities and Activities *influenced* Entities, see Figure A. Thus an Agreement, being a subclass of Entity, can *influenced* an Activity which, in turn *influenced* data (another Entity or subclass of it, perhaps a dcat:Dataset).  

Since *influenced* is generic, more specific subproperties of it should be used thus a likely construct is where an Agreement is *used* by an Activity to *generate* something, such as an Agreement to Publish Data is *used* by an Activity, Publishing Data to make (*generated*) a Published Data Dataset, as per Figure B. Of course, like almost all relationships in PROV, this influence can be qualified with a prov:qualifiedInfluence to say something specific about the relationship rather than an *influence* subproperty being used.

![How Agreements affected Entities 2](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-affected-entities-2.png)
Another way to see how an agreement affected an Entity is to who or what the Entity is attributed to (an Agent) and then to see if an Agreement affected that Agent through it's membership of a Group that is affected by the Agreements, as per Figure C. The Agreement/Group relationship (*inScope* (inv:*scope*)) an AGR-O extension to PROV-O. A specific example of this is given in Figure D.

#### Namespaces
Prefix | URI
------ | ---
prov | http://www.w3.org/ns/prov#
agr | http://promsns.org/def/agr#