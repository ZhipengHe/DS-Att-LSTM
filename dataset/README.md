### Dataset Library

#### Sepsis

> Information provided by the dataset publisher

DOI: [doi:10.4121/uuid:915d2bfb-7e84-49ad-a286-dc35f063a460](https://doi.org/10.4121/uuid:915d2bfb-7e84-49ad-a286-dc35f063a460)

##### Description

This real-life event log contains events of sepsis cases from a hospital. Sepsis is a life threatening condition typically caused by an infection. One case represents the pathway through the hospital.  The events were recorded by the ERP system of the hospital. There are about 1000 cases with in total 15,000 events that were recorded for 16 different activities. Moreover, 39 data attributes are recorded, e.g., the group responsible for the activity, the results of tests and information from checklists.  Events and attribute values have been anonymized. The time stamps of events have been randomized, but the time between events within a trace has not been altered.

##### Attributes

|Name			| Description|
|---------------|-------------------------|
|Age			| Age in 5-year groups|
|Diagnostic*	| Various checkboxes on the triage document|
|DisfuncOrg		| Checkbox: Disfunctional organ|
|Hypotensie		| Checkbox: Hypotension |
|Hypoxie 		| Checkbox: Hypoxia |
|InfectionSuspected 	| Checkbox: Suspected infection |
|Infusion 		| Checkbox: Intravenous infusion required |
|Oligurie		| Checkbox: Oliguria |
|SIRSCritHeartRate	| Checkbox: One of the SIRS criteria |
|SIRSCritLeucos		| Checkbox: One of the SIRS criteria |
|SIRSCritTachypnea	| Checkbox: One of the SIRS criteria |
|SIRSCritTemperature	| Checkbox: One of the SIRS criteria |
|SIRSCriteria2OrMore	| Checkbox: Two or more of the SIRS criteria |
|Leucocytes		| Leucocytes measurement |
|CRP			| CRP measurement |
|LacticAcid		| Lactic-acid measurement |

---

> Information discovered by Disco

##### Process Map (100% Activity 0% Path)

![sepsis-map](/img/dataset/Sepsis.png)

##### Dynamic Attributes

|Name			| Description|
|---------------|-------------------------|
|Activity| |
|Complete Timestamp| |
|org:group||
|Leucocytes		| Leucocytes measurement |
|CRP			| CRP measurement |
|LacticAcid		| Lactic-acid measurement |


##### Static Attributes

|Name			| Description|
|---------------|-------------------------|
|Age			| Age in 5-year groups |
|Diagnostic*	| Various checkboxes on the triage document|
|DisfuncOrg		| Checkbox: Disfunctional organ|
|Hypotensie		| Checkbox: Hypotension |
|Hypoxie 		| Checkbox: Hypoxia |
|InfectionSuspected 	| Checkbox: Suspected infection |
|Infusion 		| Checkbox: Intravenous infusion required |
|Oligurie		| Checkbox: Oliguria |
|SIRSCritHeartRate	| Checkbox: One of the SIRS criteria |
|SIRSCritLeucos		| Checkbox: One of the SIRS criteria |
|SIRSCritTachypnea	| Checkbox: One of the SIRS criteria |
|SIRSCritTemperature	| Checkbox: One of the SIRS criteria |
|SIRSCriteria2OrMore	| Checkbox: Two or more of the SIRS criteria |


Diagnostic*

|Name			| Description|
|---------------|-------------------------|
|Diagnose| Label |
|DiagnosticArtAstrup| CheckBox|
|DiagnosticBlood| CheckBox|
|DiagnosticECG |CheckBox|
|DiagnosticIC	|CheckBox|
|DiagnosticLacticAcid	|CheckBox|
|DiagnosticLiquor |CheckBox|
|DiagnosticOther    |CheckBox|
|DiagnosticSputum |CheckBox|
|DiagnosticUrinaryCulture	|CheckBox|
|DiagnosticUrinarySediment	|CheckBox|
|DiagnosticXthorax |CheckBox|

---

##### Clean Method for Sepsis