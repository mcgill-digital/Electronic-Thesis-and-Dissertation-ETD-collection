# Electronic-Thesis-and-Dissertation-ETD-collection

## GENERAL INFORMATION

1. **Title of Dataset:** McGill Library Electronic Thesis and Dissertation (ETD) collection (1881-2018) 
2. **Source (URL):** [https://escholarship.mcgill.ca/collections/theses](https://escholarship.mcgill.ca/collections/theses) 
3. **Type of files:** .xml, html and .csv 
4. **Date of data collection/extraction:** 2017-2018 
5. **Information about funding sources that supported the collection of the data:** McGill Library innovation funds supported the Computational Research Fellowship during which this data was extracted 

## DATASET/COLLECTION DESCRIPTION

This dataset consists of metadata and (in some cases) full text of the McGill Thesis and Dissertation collections from 1881-2018. McGill holds theses and dissertations written by McGill students from 1881 to present day. The historical print collection is housed in the McGill University Library’s Rare Books and Special Collections. Since 2009, theses have been submitted electronically and are made available in our institutional repository. In 2016, a massive retrospective digitization project was completed, as a result of which the full text of the historical theses were also made available online in the institutional repository. All the digitized and born digital theses are now publicly available at  [https://escholarship.mcgill.ca/collections/](https://escholarship.mcgill.ca/collections/) theses.  For more information about the collection, please see: [https://www.mcgill.ca/library-theses/about](https://www.mcgill.ca/library-theses/about). 

The 2018 data set includes only the descriptive metadata and the information to retrieve the full text of the thesis if needed. This was done to make the data more useable.  

The 2017 download includes both ETDs and faculty eprints from the institutional repository.  To be able to isolate the ETDs we’ve included a correspondence .txt file that lists the PID (unique identifier) of the full-text HTML file with the PID of the corresponding XML file.   

Note: Because of the size and number of the files, we have the full data sets available via our public content server. Uploaded to this repo is smaller versions of the sets that can be pulled into data visualization programs. 

## SHARING/ACCESS INFORMATION

1. **Licenses/restrictions placed on the data:** 
Metadata files: [No copyright](https://creativecommons.org/publicdomain/zero/1.0/) 

Full text files: [Copyright Undetermined](http://rightsstatements.org/vocab/UND/1.0/)
Note: Given the time span of the collection, some items remain in copyright and some are in the public domain. Copyright of McGill theses remains with the author. It is the responsibility of the user to seek permissions required by law for any reproduction or distribution of theses that are in copyright. 

2. **Links to publications that cite or use the data or related publications:** [https://github.com/rajatbhateja/computational_research_fellowship_2017](ttps://github.com/rajatbhateja/computational_research_fellowship_2017)

3. **Links to other publicly accessible locations of the data:** see file list

4. **Recommended citation for this dataset:** McGill University Library (2018). McGill Library Electronic Thesis and Dissertation (ETD) collection (1881-2018). Physical collection held in McGill Rare Books and Special Collections. [https://github.com/mcgill-digital/Electronic-Thesis-and-Dissertation-ETD-collection](https://github.com/mcgill-digital/Electronic-Thesis-and-Dissertation-ETD-collection)

## DATA &amp; FILE OVERVIEW

1. **File List:**
a. Full 2018 data set. The most recent export contains 44,368 records in a single XML file and has only the descriptive metadata + the PID that can used to construct a URL to get the thesis full text. Download [http://public-content.library.mcgill.ca/digital-collections/2018-etd-data(http://public-content.library.mcgill.ca/digital-collections/2018-etd-data)
b. 2018-05-09-mcgill-etd-edit.csv Contains a cleaned-up CSV of a sub-set of descriptive metadata (Date, author, title, degree, department) + the URL to the full text. All ready to play with! 
c. Full 2017 data set has two parts. The first is a ZIP file - mcgill-etd-metadata.zip - that has a XML file with the complete metadata for each ETD that includes all the administrative data related to the uploading of the files. The second ZIP file in this folder - mcgill-etd-fulltext-html.zip - contains the full text HTML files. The html-pdf-correspondence.txt file contains the PID number for the metadata record and the corresponding HTML full text file. This set of files can be downloaded from [http://public-content.library.mcgill.ca/digital-collections/2017-etd-data](http://public-content.library.mcgill.ca/digital-collections/2017-etd-data). 
d. 2017-etd-parse.csv is a pared down CSV file with only the PID, Year, Department of each thesis that was used in the 2017 Computational Fellowship research project. 
2. **Are there multiple versions of the dataset?** Yes 
3. **If yes, name of file(s) that was updated:** See File list for details  
a. **When was the file updated?** May 09, 2018 

## METHODOLOGICAL INFORMATION

1. **People involved with sample collection, processing, analysis and/or submission:** Sarah Severson and Elizabeth Thomson
2. **Descriptive Metadata Application Profile**

| Element | Dublin Core &amp; refinement label | Document Information |
| ----------- | ----------- | ----------- |
| Title | dc:title | Title of document |
| Creator | dc:creator | Author of document |
| Contributor | dc: contributor | (Supervisor) |
| Date | dc:date | Year the document was created. YYYY |
| Description - Abstract | dc:description | Abstract of the thesis if available otherwise the introductory paragraph. |
| Description - Abstract fr | dc:description | French language version of abstract or introductory paragraph if available. If it is not available delete the field. |
| Subject LCSH |dc:subject | Library of Congress Subject Heading |
| Subject | dc:subject | General subject keywords |
| Language | dc:language |Language of the document ie: en or fr |
| Type | dc:type | Electronic Thesis or Dissertation |
| Format | dc:format | application/pdf |
| Publisher | dc:publisher | McGill University |
| Rights | dc:rights | All items in eScholarship@McGill are protected by copyright with all rights reserved unless otherwise indicated. |
| Degree | dcterms:localthesisdegreename | Bachelor of Arts. Doctor of Philosophy. |
| Department or School | dcterms:localthesisdegreediscipline | from Escholarship subject listing Department as listed in the original document ie: Department of History |
| Collection | dcterms:localcollectioncode | ETHESIS |
| Relation - Is Part Of | dcterms:isPartOf | Thesis scanned by McGill Library OR Theses scanned by UMI/ProQuest OR Electronically-submitted theses. |
| Filename | dcterms:localfilename | Filename of document |
| Relation | dc:relation | alephsysno:NNNNNNNNN referes to a unique identifer in the McGill classic catalogue.. proquestno: AAAAAAAAAA referes to the unique identifer given to thesese microfilmed or scanned by Proquest. |
| PID | dc:identifier | A unique identifier from the institutional repository and on the record referred to as the PID. The PID should always be a 6 digit number and can be used to create a URL to the PDF file of the full thesis text.http://digitool.library.mcgill.ca/webclient/DeliveryManager?&pid=XXXXXX |

Background: These files have been catalogued over a number of years by many different people so expect some variations. 
