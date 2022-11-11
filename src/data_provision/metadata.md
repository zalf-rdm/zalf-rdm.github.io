---
label: Metadata
order: 50
---
# Metadata

A key precondition to store and share data and to fulfil the FAIR data principles (see Introduction) is the proper
description of research data by metadata. When set-up an own interoperable metadata schema for a data repository it is
very important to use assignable elements of widespread and open metadata standards.

<br>

_Overview of existing standards_

Standards only dealing with metadata for diverse purposes and are published by ISO. Metadata for geographic information 
are regulated in **ISO 19115-1ff** series (Geographic information - Metadata). ISO 19115-1:2014 and -2:2009 contain many code
lists on identification information, geometry types and other relevant topics.

Requirements for metadata related to geographic information services are defined in **EN ISO 19119:2016**. 
A technical guideline for encoding of metadata using a XML-schema is provided by **ISO/TS 19139:2007** (XML schema implementation).
Regulations for metadata are also part of other standards that relate to soil data, for example **INSPIRE DS Soil** or **ISO 28258:2013**.

The German Infrastructure for Spatial Information (GDI-DE) requires the application of ISO 19115, 19119 and 19139
in the context of INSPIRE for acquisition and support of metadata. For such purposes the Drafting Team Metadata and
European Commission Joint Research Centre published a technical guideline with INSPIRE implementing rules for metadata (JRC, 2007). 

The Digital Curation Centre (DCC) provides a [list](https://www.dcc.ac.uk/guidance/standards/metadata/list) of common metadata standards.

The [BonaRes Metadata Schema ](https://tools.bonares.de/doi)(Specka et al. 2019)![](/static/img/two_star.png)   has been created by combining elements of the two schemes INSPIRE (EU)
and DataCite (DOI) since few relevant elements within these two standards have been found.

<br>

### INSPIRE (European Union) ![](/static/img/two_star.png)  

The INSPIRE directive contains metadata elements on dataset-level that should be applied for documenting metadata for an
entire dataset or a dataset series. Metadata can also be stored on object-level. This means that metadata can be described
for each individual spatial object. Due to the product-oriented approach of INSPIRE, metadata provide not only information
on data quality and validity, but also on conditions for accessibility, use of data, access restriction (including reasons) and charges. 

<br>

### DataCite ![](/static/img/two_star.png) 

The DataCite was developed to provide easy access to scientific data over internet. It provides domain agnostic services
which belongs to the concept of a long term or persistent identifier. DataCite is using Digital Object Identifiers (DOIs)
to register a resource associated with metadata. The objective of DataCite is to increase the acceptance of research data
as legitimate, citable contributions to the scientific record and to archive data for future study. Besides a wide range
of metadata elements, DataCite provides the opportunity to acknowledge contributions of disciplinary work. To enable an
accurate and consistent identification of a resource (e.g. for citation) the metadata scheme offers a list of essential
metadata properties. The da|ra is the DOI registration agency for social and economic research data.
The recent Metadata Scheme is 4.0 (Group, 2016).

<br>

### Dublin Core Metadata Element Set (Version 1.1)  ![](/static/img/one_star.png) 

This set is a vocabulary of fifteen properties to describe a resource. It is maintained by the Dublin Core Metadata Initiative
(DCMI). The Dublin Core metadata elements formally endorsed in **ISO 15836:2009, ANSI/NISO Z39.85-2012** and **RFC 5013** (Kunze and Baker, 2007).

<br>

### DDI 
#### (Data Documentation Initiative)

Open standard (metadata model) to describe social and economic research data and survey data. Basic concept is the description
of the complete Data Life Cycle with XML.

<br>

### GESIS 
#### (Leibniz-Institute for the Social Sciences)

In line with DDI, presentation of detailed metadata and standards for surveys and interviews, e.g. in the following
technical reports: [Zenk-Möltgen and Habbel 2012](https://www.gesis.org/fileadmin/upload/forschung/publikationen/gesis_reihen/gesis_methodenberichte/2012/TechnicalReport_2012-01.pdf),
Jensen and Schweers [2014](https://www.ssoar.info/ssoar/bitstream/handle/document/40297/ssoar-2014-jensen_et_al-Das_erweiterte_Metadatenschema_der_VFU.pdf?sequence=1).

<br>

### METS 
#### (Metadata Encoding & Transmission Standard) 

This is a standard for coding and management of metadata from digital or analogue sources of different formats
(picture, text, audio, video…). Precondition are beside others sections for the presentation of the internal structure
of a digital object, group related files, technical metadata, and information about the source.
METS documents can link and integrate different metadata (e.g. from PREMIS, Dublin CORE or MARC).

<br>

### PREMIS 
#### (PREservation Metadata: Implementation Strategies) 

Initiative for the development and maintenance of internationally recognized long-term archiving metadata standards.
PREMIS aims to develop recommendations, suggestions and best practices for implementing preservation metadata,
further development of the standards, as well as the connection to other standards.

<br>

### Quali-Service (University of Bremen)
Emerging [data service center ](https://www.qualiservice.org/de/)for qualitative primary data (focus on interviews) and provision of reports about metadata standards,
e.g. [Betancort Cabrera and Haake 2014](https://media.suub.uni-bremen.de/handle/elib/3020). 

<br>

### Conflicts and solutions 

### INSPIRE vs. ISO Metadata

The problematic issue of metadata and data is that almost any piece of data can be metadata in a more specific context.
In the application schema of ISO 28258 any piece of information that can be handled as data should at least be handled as data,
but can additionally be handled as metadata. According to ISO 28258 information e.g. on projects or soil maps can be described
as data (in the form of features) or metadata. In line with INSPIRE this information is metadata of a dataset (Gärtner et al.,
2017, DOI: 10.20387/BonaRes-5PGG-8YRP). 
