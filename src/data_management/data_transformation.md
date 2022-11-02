---
label: Data Transformation
order: 30
---

# Data Transformation

A data transformation is the process of reorganizing or restructuring data from the source format into destination data
format in order to enhance data usability. When data are obtained by national standard methods or classified by national 
systems they may need to be transferred into international classification systems. Gaps in data-sets could preclude the 
direct use within models and thus require gap-filling methods.

<br>

_Overview of existing standards and tools_

<br>

### Transformation tool for the 5th edition of the German Soil Survey Guidelines (KA5)  ![](/static/img/two_star.jpg)

The revision of the German Soil Survey Guidelines resulted in a modified data encoding and classification of soils. 
For the transformation of soil data from a previous towards the following edition of the German Soil Survey Guidelines
a software tool has been developed by the Federal Institute for Geosciences and Natural Resources (BGR) in cooperation
with the Geological Surveys of the German federal states. It enables the translation of horizon symbols and derivation
of soil systematic units based on the horizon data, as well as translation of substrate types and substrate systematic units. This software tool is available for the transformation of data recorded according to the 3rd edition of the German Soil Survey Guideline (KA3) towards its 4th edition (KA4) and KA4 towards KA5. The function for derivation of soil systematic units according to the German soil classification is only implemented in the last-mentioned version (KA4/KA5). A free download for both versions is provided on the homepage of BGR.

<br>

### Derivation tool - KA5 (2005) to WRB (2007)  ![](/static/img/two_star.jpg)
The BGR devised a software tool to derivate international common soil notations (WRB 2006, update 2007) from soil data,
which were acquired according to the German Soil Survey Guidelines. However, criteria for the determination of distinct
diagnostic and naming elements of the WRB classification system are very complex. For each of these elements a graphic algorithm
has been developed that refers directly to parameters of the KA5-nomenclature and selective laboratory values. 
Feasible input data (arrays of KA5- and laboratory parameters) are interrogated in order of decreasing reliability. 
If less appropriate arrays have to be used for derivation of WRB-names, this is documented in a report for the user in order
to prove the results’ quality. The application is currently in further development: The next edition is aimed to derive soil 
notation according to WRB 2014, update 2015. 

<br>

### Transformation tool for Soil Assessment data ![](/static/img/two_star.jpg)
A software tool for the transformation of Soil Assessment data (”Bodenschaetzungsdaten”) into the nomenclature of
the German Soil Survey Guidelines (4th edition) has been developed by the Geological Survey of Lower Saxony (LBEG). 
It is also used by some other federal states. This software tool enables transformation of certain soil features
(substrate type, soil color, humus content) into KA4-nomenclature. Horizon symbols and soil types are derived on basis
of the transformed features. For further information see Bartsch et al. (2003), Engel and Mithöfer (2003) and (Hangen and Förster, 2013) 

<br>

_Other transfer functions_

-	a taxotransfer scheme allows to estimate missing soil properties based on taxon information (Batjes, 2016). 
Such a tool was developed for the SOTER database and is used to fill gaps by a defined procedure (Batjes, 2003).
-	numerous pedotransfer functions (PTFs) using basic soil properties such as pH, texture and/or bulk density to model
non-measured soil properties or soil functions. Van Looy et al. (2017) evaluate PTFs and outline perspectives for their development and applications
