# McGill Library Electronic Thesis and Dissertation (ETD) collection (1881-2018)

With the conclusion of a massive retrospective digitization project in 2016, the Library has released the metadata of the full ETD collection in hopes of encouraging discovery and research. The collection is accessible through http://escholarship.mcgill.ca/.

1. 2018-05-08-mcgill-etd.xml The most recent export containes 44,368 records in a single XML file and has only the descriptive metadata + the PID that can used to construct a URL to get the thesis full text. 
2. 2018-05-09-mcgill-etd-edit.csv Contains a cleaned up CSV of a sub-set of descriptive metadata (Date, author, title, degree, department) + the URL to the full text. All ready to play with!
3.


## Metadata Application Profile 

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
