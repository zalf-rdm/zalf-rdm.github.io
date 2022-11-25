---
label: Data Exchange and Formats
order: 20
---

# Data Exchange and Formats

<br>

_Overview of existing standards_

<br>

### AgroXML and ISO-XML  ![](/static/img/two_star.png)

Communication and data transmission between sensors and tools are indispensable in modern agricultural sector. 
On international level, the **ISO 11783-1:2017ff** series provides an uniform communication language between agricultural machinery,
e.g. operating supplies like fertilizers and pesticides, and office software. Applications and hardware (e.g. standardized plugs)
that operate with ISO 11783ff are referred to as “ISOBUS”. It focuses on the exchange of mobile and spatial data between both systems.
Within this standard the language ISO-XML is defined.

While ISO-XML mainly addresses communication between farm machineries and -orders, the data exchange language AgroXML has
also an interface via farm management information systems to external partners. AgroXML was developed by a German consortium
of agricultural software providers and industry under the leadership of the KTBL.

To enable consistent frameworks for data standards and the integration of spatial data into web services, both languages 
be bound for integration into GML specification [[1]](https://doi.org/10.1016/j.landusepol.2016.05.023).

<br>

### GeoSciML ![](/static/img/two_star.png)
Data transfer standard for geological data. GeoSciML is XML based and provides solution for the exchange of geoscientific
information, e.g. features from geological maps.

<br>

### OGC standards  ![](/static/img/two_star.png)

The Open Geospatial Consortium (OGC) develops open standards for different stages of geo-data management within a consensus process.
All OGC standards are based on XML language. 

-	**GML** (Geography Markup Language, EN ISO 19136:2020-12) is a XML grammar developed to express geographic features. 
GML is not only an open exchange format for geographic transactions on the internet, it also serves as a modeling language 
for geographic systems. The conceptual modelling framework of GML includes spatial and non-spatial properties of geographic features.
A GML document is described using a GML schema. This enables the user to describe generic geographic data sets. 
Specialized extensions of GML are developed to provide community-specific application schemas in order to facilitate data
exchange in a certain subject. The current version GML 3.3 was published in 2012 and extends the previous version with 
additional schema components and requirements. 

-	**KML** (Key Markup Language) is a XML grammar developed to express geo-objects in vector or raster graphics. Today it is often
used to visualize geo-data in Google Earth. 

-	**Observations and Measurements – XML Implementation** This standard specifies an XML implementation for the OGC and ISO
Observations and Measurements conceptual model. The XML schemas defined in this standard are specified for observations and
for features involved in sampling when making observations. Aim is to enable exchange of information describing observation
activities and their results within and between scientific and technical communities.

-	**WaterML** is a standard information model for representation and exchange of hydrological observation data. 
It aims to serve as an interoperable exchange format for transport of data sets across information systems. 
The current version WaterML2.0 is implemented as an application schema of GML 3.2.1 by the use if the 
OGC Observation & Measurement standards.

-	**Sensor Observation Service (SOS)** defines a web service interface to query sensor data including time series, 
sensor descriptions and encoding format

<br>

### UML (Unified Modeling Language, ISO/IEC 19501:2005)  ![](/static/img/two_star.png)

UML is the dominant graphical language for object-oriented modeling with a semantic specification, geographic notation,
interchange format, and a repository query interface. 

<br>

### XML (eXtended Markup Language)  ![](/static/img/two_star.png)
This widespread and simple markup language defines rules for encoding human- and machine readable documents. XML schemas 
(XSD) are used to define XML document structures. XML is a basic tool for multiple data management and exchange applications.  

<br>

### XMI (XML Metadata Interchange, OMG)  ![](/static/img/two_star.png)
XMI enables the metadata information exchange between software development tools. Based on XML-format, data can easily be
produced, processed, stored and exchanged via internet.

<br>

### ISO 28258:2013   ![](/static/img/one_star.png)
#### Soil quality - Digital Exchange of soil-related data (SoilML)

This standard provides a generic, conceptual schema for soil-related data and the structural framework for the interoperable
exchange of individually defined data. It contains a data model (following the rules of Unified Modeling Language UML) with (feature-)
types that are generally applicable types with the aim of covering most of the individual, country or data provider specific types.
Essential feature types included in the model are, e.g. Plot, Profile, Horizon or Layer. These feature types are defined in a feature catalogue,
which is non-extensible. Provider-specific feature types are only allowed to be used, if a taxonomic subtype relationship to at least one of the generic 
feature types defined in the catalogue is explicitly stated. ISO 28258 encodes soil data using XML that is encoded according
to the structure given in an XML schema definition file (XSD). The XSD file for SoilML data files is called “soilml.xsd”.
An amendment with editorial and conceptual modifications, such as renaming of feature types and improvement of the UML-data model, was published in 2019.

<br>

### SoTerML (Soil and Terrain Markup Language)   ![](/static/img/one_star.png)

For the exchange of soil and terrain data between various sources an XML schema was developed within the European FP7 project ‘e-SOTER’.
It comprises the existing SOTER database conceptual modelling, the WRB and FAO soil data structures and classifications.
In SOTER major soil and terrain databases as the European Soil Database (ESD) are covered. The principles of SoTerML are generic,
so that they should be applicable to other geo-scientific domains and not only to soil data [[2]](https://doi.org/10.1016/j.cageo.2011.11.026).

<br>

### INSPIRE Data Specification on Soil 

!!!secondary
(Soil, 2013)
!!!

Providing data according to [INSPIRE ](https://www.gdi-de.org/INSPIRE)is a legal obligation to public administration in the European Union. 
Due to this obligation no explicit recommendation is provided in this report.
INSPIRE is not only about data interoperability, but aims at data harmonization. In the INSPIRE data model real soil objects
were designed as feature types, and not features created to represent real objects. Thus soil maps were not introduced in
the model (handled as metadata, see following section). The INSPIRE model can be extended regarding the parameters for describing features.
Extensible parameter lists and code lists are kept in registries.
The INSPIRE data model differentiates between observed and derived soil profiles. An observed profile is directly linked
to a soil plot, whereas a derived soil profile describes a soil body without a connection to a certain plot.
Soil-related information can be provided as vector data by using the SoilDerivedObject feature type,
information structured as raster data is supplied by using the SoilThemeCoverage. 

<br>

### Investigation Study Assay Tabular (ISA-Tab)
Developed by ISA-Tools, this hierarchical structured file format focuses on the description of experimental metadata.

<br>

### GlobalSoilMap 
The GlobalSoilMap Specification provides an internationally agreed set of attributes and terminologies for soil data. 
It is the basis for the generic soil information model GSMML. Global soil map data is published as GSMML
compliant data service [[3]](https://www.researchgate.net/publication/265088316_Opportunities_for_information_model_driven_exchange_and_on-line_delivery_of_GlobalSoilMap_data_and_related_products).

_Other data formats of accompanying disciplines_

Geodata:
-	[GeoRSS](http://www.georss.org) (Geographically Encoded Objects for RSS feeds) is a geotagged RSS feed which describes the locations of a web 
feed, blog or any news. It is available in XML or GML format and provides meta information of a web content like authors,
date, title, narrative description, hypertext link and, at least, one location per feed.
-	GeoJSON and Esri-JSON are JavaScript notations to represent Simple-Feature-Access-Specifications e.g. for data exchange.
It is used to transform and safe structured data. 
-	Others: gdb, GeoTIFF, Feature Class

Beside geo-, soil- and agricultural data, other common data formats are widely used  
-	most important data formats for databases are based on the SQL language, such as the database engine SQLite
-	The query language SPARQL was developed by the RDF Data Access Working Group of W3C. It is compatible to RDF data model
and used as a data access protocol for the Semantic Web. 
-	GRIB (GRIdded Binary) format for meteorological data as well as historical and forecast weather data ([WMO](https://public.wmo.int/en))
-	[netCDF](https://docs.unidata.ucar.edu/netcdf-c/current/faq.html#whatisit) is a set of software libraries and self-describing, machine-independent data formats that support the creation,
access, and sharing of array-oriented scientific data.

<br>

_Table 8: Further standards on data exchange and languages_
<div class="table-wrapper scrollbar overflow-hidden">
<table class="comfortable">
<thead style="font-size: 24px; background-color: #A8A8A8">
<tr>
<th><strong>Content</strong></th>
<th><strong>Standard</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>Bibliographic data (sharing, access)</td>
<td>MARCXML</td>
</tr>
<tr style="background-color: #d3d3d3">
<td>Biochemistry, bioinformatics</td>
<td>FASTA</td>
</tr>
<tr>
<td>Conceptual schema language</td>
<td>ISO 19103:2015</td>
</tr>
<tr style="background-color: #d3d3d3">
<td>Data interchange between information systems in agriculture</td>
<td>BS ISO 11788 (1-3) </td>
</tr>
<tr>
<td>Format for information exchange (bibliographic information)</td>
<td>ISO 2709:2008 </td>
</tr>
<tr style="background-color: #d3d3d3">
<td>Functional standards</td>
<td>ISO/TR 19120:2001</td>
</tr>
<tr>
<td>Gene sequences, bioinformatics</td>
<td>Variant Call Format (VCF)</td>
</tr>
<tr style="background-color: #d3d3d3">
<td>Laboratory data</td>
<td>LIMS</td>
</tr>
<tr>
<td>Language to transform XML documents into other formats</td>
<td>XSLT</td>
</tr>
<tr style="background-color: #d3d3d3">
<td>Query language, developed by W3C</td>
<td>XPath</td>
</tr>
<tr>
<td>Statistical data and metadata exchange (SDMX)</td>
<td>ISO 17369:2013</td>
</tr>
<tr style="background-color: #d3d3d3">
<td>Vector data for Geographic Information Systems (GIS)</td>
<td>SHP (ESRI quasi-standard)</td>
</tr>
</tbody>
</table>
</div>



<br>

### Conflicts and solutions

<br> 

### ISO 28258 vs. INSPIRE DS Soil
The most significant difference between both models for soil-related data is, that the INSPIRE model provides two subtypes
for the soil profile feature type (observed and derived soil profile), which are missing in the ISO model. There is only
one type of soil profile in the ISO model that can be used in both ways, in so far as a connection between soil profile
and plot information is provided or the soil profile is directly linked to a soil mapping unit representing geometry in a soil map.
Furthermore, the INSPIRE model allows to specify from which observed soil profiles a derived soil profile was made what is
not feasible in ISO. Feature types for providing soil information as raster data are not included in the ISO model.
On the other hand, ISO provides feature types for project information and soil samples that are missing in INSPIRE.

These differences are due to the diverging approaches. INSPIRE focuses on data products and their use, as well as the delivery
of data to the users. ISO aims to data exchange in a wide range, even for scientific use. Both models need extension by
the data provider regarding definition of parameters, which is rather simple with ISO, whereas there are more formal procedures in INSPIRE. 

### Relation between OGC and ISO standards 

In the field of data exchange formats OGC and ISO developed standards in cooperation. As a result, these standards are double
branded or divided into different parts with regard to contents. These standards do not compete with each other and have a broad acceptance. 

- The XML encoding of the OGC standard GML is consistent with **EN ISO 19118:2011** and, more specifically, with **EN ISO 19136:2020-12**
in terms of transport and storage of geographic information. The basic concepts used by GML to model geographic information
are drawn from **the EN ISO 19101ff** series and the OpenGIS Abstract Specification. Current version GML 3.3 is backwards compatible
with the previous version 3.2, which is identical to EN ISO 19136:2009. 

-	Observations and Measurements Implementation Standard is published in two parts: the conceptual model (in UML) is published
as **EN ISO 19156:2013**, the XML implementation as an independent document by OGC.


:::bonares_reference

### Reference

[1] Toth, K. and A. Kucas (2016). Spatial information in European agricultural data management.
Requirements and interoperability supported by a domain model. Land Use Policy 57: 64-79.

[2] Pourabdollah, Amir, Didier G. Leibovici, Daniel M. Simms, Piet Tempel, Stephen H. Hallett and Mike J. Jackson (2012).
Towards a standard for soil and terrain data exchange: SoTerML. Computers & Geosciences 45: 270–283.

[3] Wilson, P., B. Simons and A. Ritchie (2014). Opportunities for information model driven exchange and delivery of
GlobalSoilMap data and related products. GlobalSoilMap. D. Arrouays, N. McKenzie, J. Hempel, A. Forges and A. McBratney, CRC Press: 473–476.

:::