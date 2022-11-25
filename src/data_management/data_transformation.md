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

### Transformation tool for the 5th edition of the German Soil Survey Guidelines (KA5) [[1]](https://www.schweizerbart.de/publications/detail/isbn/9783510959204/Bodenkundliche_Kartieranleitung_5_Aufl)  ![](/static/img/two_star.jpg)

The revision of the German Soil Survey Guidelines resulted in a modified data encoding and classification of soils. 
For the transformation of soil data from a previous towards the following edition of the German Soil Survey Guidelines
a software tool has been developed by the Federal Institute for Geosciences and Natural Resources (BGR) in cooperation
with the Geological Surveys of the German federal states. It enables the translation of horizon symbols and derivation
of soil systematic units based on the horizon data, as well as translation of substrate types and substrate systematic units. This software tool is available for the transformation of data recorded according to the 3rd edition of the German Soil Survey Guideline (KA3) towards its 4th edition (KA4) and KA4 towards KA5. The function for derivation of soil systematic units according to the German soil classification is only implemented in the last-mentioned version (KA4/KA5). A free download for both versions is provided on the homepage of BGR.

<br>

### Derivation tool - KA5 (2005) to WRB (2007)  ![](/static/img/two_star.jpg)
The BGR devised a software tool to derivate international common soil notations ([[2]](https://www.fao.org/3/a0510e/A0510E.pdf) update 2007) from soil data,
which were acquired according to the German Soil Survey Guidelines. However, criteria for the determination of distinct
diagnostic and naming elements of the WRB classification system are very complex. For each of these elements a graphic algorithm
has been developed that refers directly to parameters of the KA5-nomenclature and selective laboratory values. 
Feasible input data (arrays of KA5- and laboratory parameters) are interrogated in order of decreasing reliability. 
If less appropriate arrays have to be used for derivation of WRB-names, this is documented in a report for the user in order
to prove the results’ quality. The application is currently in further development: The next edition is aimed to derive soil 
notation according to WRB 2014 [[3]](https://www.fao.org/3/i3794en/I3794en.pdf), update 2015. 

<br>

### Transformation tool for Soil Assessment data ![](/static/img/two_star.jpg)
A software tool for the transformation of Soil Assessment data (”Bodenschaetzungsdaten”) into the nomenclature of
the German Soil Survey Guidelines (4th edition) has been developed by the Geological Survey of Lower Saxony (LBEG). 
It is also used by some other federal states. This software tool enables transformation of certain soil features
(substrate type, soil color, humus content) into KA4-nomenclature. Horizon symbols and soil types are derived on basis
of the transformed features. For further information see Bartsch et al. (2003) [[4]](https://www.schweizerbart.de/publications/detail/artno/185042100),
Engel and Mithöfer (2003) [[5]](https://www.schweizerbart.de/publications/detail/artno/185042100) 
and Hangen and Förster (2013) [[6]](https://doi.org/10.1002/jpln.201300021).

<br>

_Other transfer functions_

-	a taxotransfer scheme allows to estimate missing soil properties based on taxon information (Batjes, 2016) [[7]](https://doi.org/10.1016/j.geoderma.2016.01.034). 
Such a tool was developed for the SOTER database and is used to fill gaps by a defined procedure (Batjes, 2003) [[8]](https://www.isric.org/sites/default/files/isric_report_2003_03.pdf).
-	numerous pedotransfer functions (PTFs) using basic soil properties such as pH, texture and/or bulk density to model
non-measured soil properties or soil functions. Van Looy et al. (2017) [[9]](http://dx.doi.org/10.1002/2017rg000581)
evaluate PTFs and outline perspectives for their development and applications


:::bonares_reference

### References

[1] Boden, Ad-hoc-AG (2005). Bodenkundliche Kartieranleitung (German Soil Survey Guideline). Hannover.

[2] WRB, IUSS Working Group (2006). World reference base for soil resources 2006: A framework for international
classification, correlation and communication. World Soil Resources Reports(103): 145.

[3] WRB, IUSS Working Group (2014). World reference base for soil resources 2014: International soil classification
system for naming soils and creating legends for soil maps: Update 2015. World Soil Resources Reports No. 106: 203.

[4] Bartsch, H.-U., I. Benne, E. Gehrt, J. Sbresny and A. Waldeck (2003). Aufbereitung und Übersetzung der Bodenschätzung.
Arbeitshefte Boden 2003(1): 45–95.

[5] Engel, N. and K. Mithöfer (2003). Auswertung digitaler Bodenschätzungsdaten im Niedersächsischen Landesamt für
Bodenforschung (NLfB): Ein Überblick für den Nutzer. Arbeitshefte Boden 2003(1): 5–43.

[6] Hangen, E. and H. Förster (2013). Investigating translated data of the German soil‐quality assessment using pinpoint
field validation. Journal of Plant Nutrition and Soil Science 176(5): 680-687.

[7] Batjes, N.H. (2016). Harmonized soil property values for broad-scale modelling (WISE30sec)
with estimates of global soil carbon stocks. Geoderma 269: 61-68.

[8] Batjes, N.H. (2003). A taxotransfer rule-based approach for filling gaps in measured soil data in primary SOTER
database (ver. 1.1; GEFSOC Project). TEchnical Report 2003/03, ISRIC - World Soil Information, Wageningen.

[9] Van Looy, K., J. Bouma, M. Herbst, J. Koestel, B. Minasny, U. Mishra, C. Montzka, et al. (2017). Pedotransfer
Functions in Earth System Science: Challenges and Perspectives. Reviews of Geophysics 55(4): 1199-1256.

:::