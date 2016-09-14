## How Agreements affected Agents
![How Agreements affected Agents](https://github.com/nicholascar/agr-o/blob/master/examples/how-agreements-affected-agents.png)

To infer how Agreements affected Agents in the past, we find the Activities that the Agent was associated with.

In PROV-O, Agents can be associated with an Activity via *wasAssociatedWith* predicate and that association can be qualified by an Association such that the Agent followed some Plan (the Association *hadPlan*), as per Figure A. Thus, A Data Owner (Agent) could have Shared Data (Activity) in a manner defined by an Agreement to Share Data, as per Figure B.

The Activities that the Agent was associated with could have affected Entities in some way such as sharing a particular dataset. This would be indicated with a qualified Agent/Entity relationship: perhaps the Activity produced the Entity via *qualifiedGeneration*. Other qualified relationships can be made by subclassing *qualifiedInfluence*. 