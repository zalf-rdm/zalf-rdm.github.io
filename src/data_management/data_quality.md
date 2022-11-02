---
label: Data Quality and Statistics
order: 40
---
# Data Quality and Statistics

In this chapter quality assurance is provided by standardized methods of data acquisition, e.g. in laboratories, processing,
and management. Databases with scientific data should provide statements on data quality features. Database clients, 
in particular modeler, need to get information on the quality level of a data set and information on completeness and consistency.
Therefore, quality checks should be carried out when research data are uploaded to the database.

Helpful features of data quality analysis are (automated) validation and statistical data checks. Workflows including 
statistical test algorithms, accuracy of estimation, number of replication, outlier test, Gaussian normal distribution, 
and peakedness (single or multiple), data gaps, systematic errors, syntactical checks, data integrity, and data plausibility
are relevant for data quality evaluation and systematic data error identification. Data assessment needs also additional 
information on the quality criteria of the data set.

_Overview of existing standards_

### EN ISO 19157:2013 - Data quality  ![](/static/img/two_star.jpg)

Information about the quality of available geo-data is vital to the process of selecting a data set 
because the value of data is directly related to its quality. ISO 19157 provides:

-	a classification schema for data quality and data errors, which are categorized into different elements, depending on their nature, 
-	principles how geo-data can be described and guidance on assessing the quality of actual datasets, and 
-	a framework of procedures for determining and evaluating data quality that is applicable to digital geographic datasets.

### Conformity key for KA5  ![](/static/img/two_star.jpg)
BGR developed a quality assurance tool for soil data according to the KA5. With this database application users can check 
their soil data for conformity according to the rules of the KA5. Complex algorithms test soil and substrate types as well
as horizon symbols. The enumeration of horizons and depth information is tested for validity, and missing profile or horizon
datasets are identified. Correction of errors can be performed by the user and KA5-compliant data can be exported. 
This application helps to improve data quality of either newly acquired data or already existing databases.

### Core Trust Seal  ![](/static/img/two_star.jpg)
Best practices for high data quality and interoperability for data repositories are given by the “Core trustworthy
data repository requirements”. A checklist with mandatory repository requirements helps to proof the data repository
if it fulfills all the necessary quality standards. Repository operator can apply for the Core Trust Seal via an
Application Management Tool (AMT).

### DIN ISO 11843-1:2004ff series - Capability of detection  ![](/static/img/two_star.jpg)
This norm has five parts including terms (1), linear calibration of data (2), determination of the critical value for the
response variable (3), comparing the minimum detectable value with a given value (4) and linear and non-linear calibration cases (5).

### ISO 3534-1/-2:2006 - Statistics and terms  ![](/static/img/two_star.jpg)
Define statistical terms and terms used in probability. They provide also rules on probability calculations, random sampling,
correlations, and estimation functions. 

### ISO 16269 series - Statistical interpretation of data ![](/static/img/two_star.jpg)
This ISO series provides descriptions of sound statistical testing procedures and graphical data analysis methods. 
In different parts statistical procedures are defined, such as detection of outliers ( -4:2010) or confidence interval (-7:2001).
Other standards are under development, e.g. test of normal distribution (ISO/DIS 16269-3).

_National standards on data quality and statistics_

### DIN 66270:1998 - Software document evaluation, Quality characteristics  ![](/static/img/two_star.jpg)
The German standard defines requirements of documents according to its identification, content (completeness, adequacy, correctness, and consistency),
and representation (comprehensibility and clarity).

_Table 7: National standards on statistic evaluation and tests_ ![](/static/img/two_star.jpg)

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
<td></td>
</tr>
<tr style=" background-color: #d3d3d3">
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr style=" background-color: #d3d3d3">
<td></td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>

_Quality management system and Measurement management systems_

The quality management system (QMS) is closely coupled to **ISO 9000ff** and **ISO 10000ff** series 
(e.g. EN ISO 9000:2015, 9001:2015, 9004:2009, ISO 10005:2005, 10006:2003) and **DIN 55350-100:2017** which are mainly 
focusing on the management aspect to achieve costumer’s satisfaction. The **DIN 55350** series describes concepts and definitions
in quality and statistics. Examples are:

**EN ISO 9001:2015** contains the general requirements for the competence to carry out tests and / or calibrations, including sampling. It refers to tests and calibrations that are based on specified in normative documents methods of methods that are not defined in normative documents, and those that were developed in the laboratory (ISO/IEC 17025:2005). ISO 9001 specifies requirements for a QMS. 
**EN ISO 9004:2009** gives guidance on a wider range of objectives of a QMS, for long-term success and improved performance. These standards can be applied to support organizations to develop a coherent quality management system. Guidelines for technical subjects in support of QMS are provided by e.g. ISO 10005, 10006, 10007, 10014, and 19011.    
**EN ISO 10012:2003** defines measurement processes and emphasizes the requirement of suitable equipment for an effective measurement management system. It aims to control risks of wrong data and results. Other management systems are given in the EN ISO 14001ff (Environmental management systems) and EN ISO 50001 (Energy management system).
