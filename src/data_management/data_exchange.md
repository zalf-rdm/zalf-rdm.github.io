---
label: Data Exchange and Formats
order: 20
---

# Data Exchange and Formats

<br>

_Overview of existing standards_

<br>

### AgroXML and ISO-XML  ![](/static/img/two_star.jpg)

Communication and data transmission between sensors and tools are indispensable in modern agricultural sector. 
On international level, the ISO 11783-1:2007ff series provides an uniform communication language between agricultural machinery,
e.g. operating supplies like fertilizers and pesticides, and office software. Applications and hardware (e.g. standardized plugs)
that operate with ISO 11783ff are referred to as “ISOBUS”. It focuses on the exchange of mobile and spatial data between both systems.
Within this standard the language ISO-XML is defined.

While ISO-XML mainly addresses communication between farm machineries and -orders, the data exchange language AgroXML has
also an interface via farm management information systems to external partners. AgroXML was developed by a German consortium
of agricultural software providers and industry under the leadership of the KTBL.

To enable consistent frameworks for data standards and the integration of spatial data into web services, both languages 
be bound for integration into GML specification (Toth and Kucas, 2016).

### GeoSciML ![](/static/img/two_star.jpg)
Data transfer standard for geological data. GeoSciML is XML based and provides solution for the exchange of geoscientific
information, e.g. features from geological maps.

### OGC standards  ![](/static/img/two_star.jpg)

The Open Geospatial Consortium (OGC) develops open standards for different stages of geo-data management within a consensus process.
All OGC standards are based on XML language. 

-	**GML** (Geography Markup Language, EN ISO 19136:2009) is a XML grammar developed to express geographic features. 
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

### UML (Unified Modeling Language, ISO/IEC 19501:2005)  ![](/static/img/two_star.jpg)

UML is the dominant graphical language for object-oriented modeling with a semantic specification, geographic notation,
interchange format, and a repository query interface. 

### XML (eXtended Markup Language)  ![](/static/img/two_star.jpg)
This widespread and simple markup language defines rules for encoding human- and machine readable documents. XML schemas (XSD) are used to define XML document structures. XML is a basic tool for multiple data management and exchange applications.  

### XMI (XML Metadata Interchange, OMG)  ![](/static/img/two_star.jpg)
XMI enables the metadata information exchange between software development tools. Based on XML-format, data can easily be produced, processed, stored and exchanged via internet.

### ISO 28258:2013 Soil quality - Digital Exchange of soil-related data (SoilML)  ![](/static/img/one_star.jpg)
This standard provides a generic, conceptual schema for soil-related data and the structural framework for the interoperable exchange of individually defined data. It contains a data model (following the rules of Unified Modeling Language UML) with (feature-) types that are generally applicable types with the aim of covering most of the individual, country or data provider specific types. Essential feature types included in the model are, e.g. Plot, Profile, Horizon or Layer. These feature types are defined in a feature catalogue, which is non-extensible. Provider-specific feature types are only allowed to be used, if a taxonomic subtype relationship to at least one of the generic feature types defined in the catalogue is explicitly stated. ISO 28258 encodes soil data using XML that is encoded according to the structure given in an XML schema definition file (XSD). The XSD file for SoilML data files is called “soilml.xsd”. An amendment with editorial and conceptual modifications, such as renaming of feature types and improvement of the UML-data model, was published in 2019.

### SoTerML (Soil and Terrain Markup Language)   ![](/static/img/one_star.jpg)
For the exchange of soil and terrain data between various sources an XML schema was developed within the European FP7 project ‘e-SOTER’. It comprises the existing SOTER database conceptual modelling, the WRB and FAO soil data structures and classifications. In SOTER major soil and terrain databases as the European Soil Database (ESD) are covered. The principles of SoTerML are generic, so that they should be applicable to other geo-scientific domains and not only to soil data (Pourabdollah et al., 2012).

### INSPIRE Data Specification on Soil 

!!!secondary
(Soil, 2013)
!!!

Providing data according to INSPIRE is a legal obligation to public administration in the European Union. Due to this obligation no explicit recommendation is provided in this report.
INSPIRE is not only about data interoperability, but aims at data harmonization. In the INSPIRE data model real soil objects were designed as feature types, and not features created to represent real objects. Thus soil maps were not introduced in the model (handled as metadata, see following section). The INSPIRE model can be extended regarding the parameters for describing features. Extensible parameter lists and code lists are kept in registries.
The INSPIRE data model differentiates between observed and derived soil profiles. An observed profile is directly linked to a soil plot, whereas a derived soil profile describes a soil body without a connection to a certain plot. Soil-related information can be provided as vector data by using the SoilDerivedObject feature type, information structured as raster data is supplied by using the SoilThemeCoverage. 

### Investigation Study Assay Tabular (ISA-Tab)
Developed by ISA-Tools, this hierarchical structured file format focuses on the description of experimental metadata.

### GlobalSoilMap 
The GlobalSoilMap Specification provides an internationally agreed set of attributes and terminologies for soil data. It is the basis for the generic soil information model GSMML. Global soil map data is published as GSMML compliant data service (Wilson et al., 2014).

_Other data formats of accompanying disciplines_

Geodata:
-	GeoRSS (Geographically Encoded Objects for RSS feeds) is a geotagged RSS feed which describes the locations of a web feed, blog or any news. It is available in XML or GML format and provides meta information of a web content like authors, date, title, narrative description, hypertext link and, at least, one location per feed.
-	GeoJSON and Esri-JSON are JavaScript notations to represent Simple-Feature-Access-Specifications e.g. for data exchange. It is used to transform and safe structured data. 
-	Others: gdb, GeoTIFF, Feature Class

Beside geo-, soil- and agricultural data, other common data formats are widely used  
-	most important data formats for databases are based on the SQL language, such as the database engine SQLite
-	The query language SPARQL was developed by the RDF Data Access Working Group of W3C. It is compatible to RDF data model and used as a data access protocol for the Semantic Web. 
-	GRIB (GRIdded Binary) format for meteorological data as well as historical and forecast weather data (WMO)
-	netCDF is a set of software libraries and self-describing, machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data.

Table 8: Further standards on data exchange and languages


Conflicts and solutions
ISO 28258 vs. INSPIRE DS Soil
The most significant difference between both models for soil-related data is, that the INSPIRE model provides two subtypes for the soil profile feature type (observed and derived soil profile), which are missing in the ISO model. There is only one type of soil profile in the ISO model that can be used in both ways, in so far as a connection between soil profile and plot information is provided or the soil profile is directly linked to a soil mapping unit representing geometry in a soil map. Furthermore the INSPIRE model allows to specify from which observed soil profiles a derived soil profile was made what is not feasible in ISO. Feature types for providing soil information as raster data are not included in the ISO model. On the other hand ISO provides feature types for project information and soil samples that are missing in INSPIRE.
 These differences are due to the diverging approaches. INSPIRE focuses on data products and their use, as well as the delivery of data to the users. ISO aims to data exchange in a wide range, even for scientific use. Both models need extension by the data provider regarding definition of parameters, which is rather simple with ISO, whereas there are more formal procedures in INSPIRE. 

Relation between OGC and ISO standards 
In the field of data exchange formats OGC and ISO developed standards in cooperation. As a result, these standards are double branded or divided into different parts with regard to contents. These standards do not compete with each other and have a broad acceptance. 
-	The XML encoding of the OGC standard GML is consistent with EN ISO 19118:2011 and, more specifically, with EN ISO 19136:2009 in terms of transport and storage of geographic information. The basic concepts used by GML to model geographic information are drawn from the EN ISO 19101ff series and the OpenGIS Abstract Specification. Current version GML 3.3 is backwards compatible with the previous version 3.2, which is identical to EN ISO 19136:2009. 
-	Observations and Measurements Implementation Standard is published in two parts: the conceptual model (in UML) is published as EN ISO 19156:2013, the XML implementation as an independent document by OGC.