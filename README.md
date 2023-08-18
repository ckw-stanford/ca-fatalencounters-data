# California Fatal Encounters Data
This is a list of fatal encounter victims which all died as a result of interaction with California law enforcement agencies. This particular set of data only includes records for Afician Americans.

These are incident and victim datasets that document African Americans killed through encounters with police. We started with the data collected and shared on the Fatalencounters.org website. We added webarchive links to the websites that document these incidents. The webarchive links are available thanks to [Archive.org's Wayback Machine](https://archive.org/).

## Sources

Burghart, D.B. (2020). Fatal Encounters: 
A step toward creating an impartial, comprehensive and searchable national database of people killed during interactions with police [data file and codebook]. [https://fatalencounters.org/](https://fatalencounters.org/)

## CA-Fatal-Encounters-final.csv headings
**unique ID** this is the index number used to disambiguate the victims within the Know Systemic Racism Project.
**full name** the full name of the victim include first name, last name, middle name/initial, and suffix
**victim wikidata page qid** the wikidata identifier for victim's page - this identifier is based on the victim's full name
**significant event name** this field was created to link to another wikidata page. the naming conventing is 'death of [victim's full name]' example: death of Troy Smith
**significant event qid** the wikidata identifier for significant event name page 
**first name** first name of the victim
**first name qid** the wikidata identifier for the first name
**middle name** *field not used* middle name of the victim
**last name** last name of the victim
**last name qid** the wikidata identifier for the last name
**suffix** *field not used* suffix of the victim
**alias** any nickname or aka's of the victim
**age** age of the victim at the time of their death
**gender** the gender of the victim
**race** *field not used*
**race with imputation** the race of the victim - all victims of the dataset are African American
**race qid** the wikidata identifier for African American
**imputation probability** *field not used*
**url image** *field not used* an image of the victim
**date of death (YYYY-MM-DD)** the date the victim died
**street address** *field not used* the street address where the victim died. example 123 main st
**city** the city where the victim died
**city qid**the wikidata identifier for the city
**state** *field not used* all records are for California
**zip code** *field not used* zip code where victim died
**county** the county where the victim died
**county qid** the wikidata identifier for the county
**full address** address where the victim died, includes street addess, city, state, zip and county
**lat_lon** geographical coordinates of where the victim died. If a full address is not available the coordinates point to the city where the victim died.
**lea** the CA law enforcement agency that was involved with the death of the victim
**lea qid** the wikidata identifier for the law enforcement agency
**lea 2** the CA law enforcement agency that was involved with the death of the victim - this field was added because there are records where two seperate law enforecement agencies where involved.
**lea 2 qid** the wikidata identifier for the law enforcement agency
**lea 3** the CA law enforcement agency that was involved with the death of the victim - this field was added because there are records where three seperate law enforecement agencies where involved.
**lea 3 qid** the wikidata identifier for the law enforcement agency
**manner of death** how the victim died
**manner of death qid** the wikidata identifier for the manner of death
**armed/unarmed** *field not used* notates if the victim was armed at the time of their death
**alleged weapon** *field not used* notates if the victim had an alleged weapon at the time of their death
**aggressive physical movement** *field not used* notates if the victim displayed aggressive physical movement at the time of their death
**fleeing/not fleeing** *field not used* notates if the victim was fleeing at the time of their death
**description temp** *field not used* description of the incident
**url temp** *field not used*
**brief description** *field not used* description of the incident
**dispositions/exclusions internal use, not for analysis** *field not used*
**intended use of force (developing)** *field not used* 
**foreknowledge of mental illness? internal use, not for analysis** *field not used* notates if victim was suffering from mental illness at the time of their death
**supporting link** url news link to the incident
**archived supporting link** archived url of supporting link

## Incident_Schema.json
This is the schema to be used with OpenRefine to populate Wikidata significant entries based on the CA-Fatal-Encounters-final.csv.csv above.

## Victim_Schema.json
This is the schema to be used with OpenRefine to populate Wikidata victim entries based on the CA-Fatal-Encounters-final.csv.csv above.
