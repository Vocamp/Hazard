# HazardousSituation
Description: Original [WOP2015 submission](http://ceur-ws.org/Vol-1461/WOP2015_pattern_abstract_7.pdf) "The Hazardous Situation Ontology Design Pattern" by
Agnieszka Lawrynowicz and Ilona Lawniczak.

## Competency Questions
The list of competency questions for the pattern is as follows:
- What object (person, organization, equipment etc.) is exposed to a hazard?
– To which hazard is exposed an object (person, organization, equipment etc.)?
– Which hazardous events are associated with a hazardous situation?
- What is the cause of a hazardous event?
- What is the consequence of a hazardous event?
- What is the value of exposure of an object being exposed to a hazard?

## Axioms
[//]: # (\mathrm{HazardousSituation} &\sqsubseteq \exists \mathrm{participantIn}.\mathrm{HazardousEvent})
[//]: # (\mathrm{HazardousEvent} &\equiv \exists \mathrm{hasParticipant}.(\mathrm{Object}\sqcap \exists)
[//]: # (\mathrm{exposedTo.Hazard})
[//]: # (\mathrm{HazardousEvent} &\sqsubseteq \exists \mathrm{hasQuality.Exposure})
[//]: # (\mathrm{HazardousEvent} &\sqsubseteq \exists \mathrm{hasDuration.TimeInterval})
[//]: # (\mathrm{HazardousEvent} &\sqsubseteq \exists \mathrm{causallyFollows.Cause})
[//]: # (\mathrm{Consequence} &\sqsubseteq \exists \mathrm{causallyFollows.HazardousEvent})
[//]: # (\mathrm{Cause} &\sqsubseteq \mathrm{Event})
[//]: # (\mathrm{HazardousEvent} &\sqsubseteq \mathrm{Event})
[//]: # (\mathrm{Consequence} &\sqsubseteq \mathrm{Event}))

[Original Axioms](http://mathurl.com/h39tbeg)
![equation](http://mathurl.com/h39tbeg.png)
