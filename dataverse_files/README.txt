This README file was generated on 2023-11-27 by Palumbo Loïc
Last updated: 2023-11-27.
 
# GENERAL INFORMATION
 
## Dataset title: 2023_11_27_IAHP_wildlife_surveillance_France_2016_to_2022
 
## DOI: 10.57745/QWZV94 
 
## Contact email: loic.palumbo@ofb.gouv.fr 
 
# METHODOLOGICAL INFORMATION 
 

## Description of sources and methods used to collect and generate data:
 
The SAGIR network is an event-based surveillance network for wildlife health in which local stakeholders (naturalists, hunters, etc.) report the discovery of dead animals to the network.
Depending on the local representative of the network judgement, signaled carcasses are collected and sent to the local veterinary laboratory where a necropsy is carried out. 
Regarding HPAI surveillance, tracheal and cloacal swabs are sampled and analyzed with PCR.
A sequenced framework is used for this analysis, first presence of avian influenza A is tested via PCR for the M gene; then positive samples are tested for H5 or H7 avian virus (distinct PCR), 
and finally positive samples are tested by PCR by the French national reference laboratory for the clade 2.3.4.4b lineage if H5 positive and tested by molecular tools for HP characteristics if H7 positive. 
Samples are then characterized as HP if positive to gene M / H5 / clade 2.3.4.4b or to gene M / H7 / H7HP test (but no such samples were collected). 
All other samples are considered as negative. Individuals of same species found dead in the same commune in less than 24 hours, were collected and tested together in one or more pools (no more than 5 birds each). 
No individual results were available when samples from various individuals were pooled. A positive event (to highly pathogenic avian virus H5 of clade 2.3.4.4b, since no H7 AI were detected in the period studied) means that least one bird in at least one pool of the event was positive to HPAI.

Between 2016 and May 2022, the specific surveillance protocol implemented by the SAGIR network for HPAI monitoring was basic: events of at least three birds of the same species that were found dead at the same site (1km²) over a short period (24 hours) were collected. 
Swans were subject to enhanced surveillance at all times and in all places, and were collected and tested as soon as the first bird was found dead (sentinel species). On the other hand, for risky periods (regulated by ministerial ruling and based on the active circulation of HPAI in neighboring countries or in France) 
and in particular areas of concern (again regulated by ministerial ruling, including wetlands on migratory routes), an enhanced protocol was carried out including sampling and analysis of any mortality of Laridae, Rallidae, Anatidae, waders, raptors and vultures. 
The data collection protocol changed in May 2022: from this date, the same basic rule  applied, but if a bird was collected and tested positive for HPAI in a given area, a regulatory infected zone was established, 
and no further specimens of the same species were collected for the 10 following days within this zone (regulated by regional ruling and including all communes within 5km from the detected positive case). 


## Methods for processing the data: 
For all data precise GPS coordinates of the events’ collection points were not available, the local collector assigned the event to the name of the commune, then INSEE's code was paired and we therefore assigned each event at the centroid location of the commune in which they were discovered.  We used Lambert93 as projection system.

## Quality -assurance procedures performed on the data: COFRAC accreditation for lab analysis
 
# DATA-SPECIFIC INFORMATION 

## Variable/Column List:
For each variable or column name, provide: 
- uid: unique numeric id for each event
- id: id from the source database (for correspondence if needed)
- results_of_analysis: HP for pools that tested positive to all PCR : M gene, H5 and H5 clade 2.3.4.4.b. Negative for others (uninterpretable events were removed)
- Bird_species_FR: french name of the bird species 
- CD_nom : unique numeric id of the species (0 when no species was identified or for exotic species not liste in the INPN TaxRef)
- Bird_family_latin: latin name of the bird family
- Bird_species_LAT: latin name of the species
- Code_INSEE: French unique geographic code of the commune
- Obs_date: date of the observation of the mortality event (DD/MM/YYYY)
- Zone_of_enhanced_surveillance_ZRP: zone (listed by national decree) with applicable enhanced IAHP surveillance of wild birds
- Name_ZRP: name of the enhanced surveillance zone
- Nb_birds_lab_pools: number of birds pooled in the same analysis
- X_municipality_centroid_Lambert93 & Y_municipality_centroid_Lambert93 : the centroid location of the commune (X and Y) in which the event was collected.  We used Lambert93 as projection system.

 
## Missing data codes: 
Codes used to indicate missing data : NA
 
## Additional information: 
for more information on SAGIR : https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiPyPzyquSCAxUhRaQEHVoICGYQFnoECBAQAQ&url=https%3A%2F%2Fprofessionnels.ofb.fr%2Ffr%2Freseau-sagir&usg=AOvVaw0BwpA-Dx7R-8GnzWoIdj0Q&opi=89978449 