# McGill Library Electronic Thesis and Dissertation (ETD) collection (1881-2018)

With the conclusion of a massive retrospective digitization project in 2016, the Library has released the metadata of the full ETD collection in hopes of encouraging discovery and research. The collection is also accessible through our institutional repository http://escholarship.mcgill.ca/.

Note: Because of the size and number of the files, we have the full data asets available via our public content server. Uploaded to this repo is smaller versions of the sets that can be pulled into data visulization programs. 

1. Full 2018 data set. The most recent export containes 44,368 records in a single XML file and has only the descriptive metadata + the PID that can used to construct a URL to get the thesis full text. Download http://public-content.library.mcgill.ca/digital-collections/2018-etd-data

2. 2018-05-09-mcgill-etd-edit.csv Contains a cleaned up CSV of a sub-set of descriptive metadata (Date, author, title, degree, department) + the URL to the full text. All ready to play with!

3. Full 2017 data set has two parts. The first is a ZIP file - mcgill-etd-metadata.zip - that has a XML file with the complete metadata for each ETD that includes all of the administrative data related to the uploading of the files. The second ZIP file in this folder - mcgill-etd-fulltext-html.zip - contains the full text HTML files. The html-pdf-correspondence.txt file contains the PID number for the metadata record and the corresponding HTML full text file.  This set of files can be dowloaded from http://public-content.library.mcgill.ca/digital-collections/2017-etd-data.

4. 2017-etd-parse.csv is a pared down CSV file with only the PID, Year, Department of each thesis that was used in the 2017 Computational Fellowship research project. 


## Descriptive Metadata Application Profile 

| Element	| Dublin Core & refinement label	| Document Information | 
|--------| ------------------------------- | -------------------- |
Title	 | dc:title	| Title of document
Creator |	dc:creator	|Author of document
Contributor	|dc: contributor	|(Supervisor)
Date	|dc:date	| Year the document was created. YYYY
Description - Abstract	|dc:description	| Abstract of the thesis if available otherwise the introductory paragraph.
Description - Abstract fr	|dc:description	|French language version of abstract or introductory paragraph if available. If it is not available delete the field.
Subject LCSH	|dc:subject	|Library of Congress Subject Heading
Subject |	dc:subject	|General subject keywords
Language	|dc:language	|Language of the document ie: en or fr
Type|	dc:type	|Electronic Thesis or Dissertation
Format|	dc:format	 |application/pdf
Publisher	|dc:publisher	|McGill University
Rights|	dc:rights	|All items in eScholarship@McGill are protected by copyright with all rights reserved unless otherwise indicated.
Degree	|dcterms:localthesisdegreename	|Bachelor of Arts. Doctor of Philosophy.
Department or School	|dcterms:localthesisdegreediscipline |from  Escholarship subject listing	Department as listed in the original document ie: Department of History
Collection|	dcterms:localcollectioncode	|ETHESIS
Relation - Is Part Of|	dcterms:isPartOf	|Thesis scanned by McGill Library OR Theses scanned by UMI/ProQuest OR Electronically-submitted theses.
Filename	|dcterms:localfilename	|Filename of document 
Relation	|dc:relation	| alephsysno:NNNNNNNNN referes to a unique identifer in the [McGill classic catalogue.](https://catalogue.mcgill.ca/F/).  proquestno: AAAAAAAAAA referes to the unique identifer given to thesese microfilmed or scanned by Proquest. 
PID |dc:identifier | A unique identifier from the institutional repository and on the record referred to as the PID. The PID should always be a 6 digit number and can be used to create a URL to the PDF file of the full thesis text.http://digitool.library.mcgill.ca/webclient/DeliveryManager?&pid=XXXXXX

Background: These files have been catalogued over a number of years by many different people so expect some variations. 
