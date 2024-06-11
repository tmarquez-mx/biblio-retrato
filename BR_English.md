# Biblio-retratos. Visualizing academic identities.

A reinterpretation from Digital Humanities of Zotero as an artifact to document academic identities in literacy.


### Scheme
• Narrative description
• Operative description
• Keywords
• Enabled features
• Future features
• Development
• Security
• Register Guide
• Query Guide
• Visualization Guide
• History
• Design and image trademark
• Credits
• Thanks



### Narrative description

Biblio-retratos is a web application that allows Zotero (an open source reference manager heavily extended in academic communities worldwide) users to get various analytics and visualizations regarding their "literacy". Meaning, regarding their abilities, work, and trajectory in bibliographic reference collecting and processing. All of them, apart from consuming a tremendous ammount of time in the span of an academic career, are practices that reflect belonging, dispositions and theorical-methodological frontiers, making them an important part of an academic identity. Biblio- retratos (also known as Zotero-BR) is a project of Digital Humanities. In 2023, it received financing from Dirección de Investigación y Posgrado of Universidad Iberoamericana, Mexico City.


### Operative description


• Biblio-retratos (BR) links the user with their database stored by default in the Zotero server via Zotero Web API v3. If the database is in another server, communication won't be possible.

• BR is going to request (typo en el original) during registration for the first and only time Zotero's ID User and Private key. See instructions.

• Queries are performed by item type (i.e., book, book section, journal, and so on) or by sub-collection. The whole database can be queried if no item or sub-collection is selected.[^1]

• Fields that can be selected to visualize are: author, place, date, date added, tag and item type.

(Queries can be set temporarily). Possibilities are: anually (every registered year since the beginning of the database), every 5 years, every decade, every X number of years or a period of years. If no option is specifies, query will be done in all the registers.


### Keywords
Academic identities, visual analytics, literacy, Digital Humanities, Zotero

[^1]:  Note: Due to BR getting information from a remote database, query results by tags, may not match what the user visualizes in the Zotero desktop app. To verify and filter tags, go to the web version.
    

### Enabled features

Phase 1. 
Concluded and operational. No installation required. Web-based operation. Currently in public beta. (03.2024)
	• Linked to Zotero
	• Queries
	• Information deployed
	• Export .CVS
	• Visualization
	• Export .PNG

### Future features

Phase 2.
	• Uploading of image or photograph (portrait)
	• Layout gallery
	• Biblio-retrato generation
	• Export

### Development

• Frontend : Framework Vue.js Javascript (open source)

• Backend : Java

### Security
• Biblio-retratos does not store content from any user database in Zotero. It only eases communication between both.
• Email, Zotero User ID and Zotero Private key are protected by la. See Privacy Notes.
• Safe password and captcha validation standard
• Free of vulnerabilities Apache server

### Registry Guide
1. Go to Biblio-retratos webpage
2. The first time you must get your username clicking "Register here".
3. In the next screen, type your email and a 10 character password, using small and caps
4. Next screen wil request for one time only your Zotero User ID and the Private Key. To get those, you can go to https://www.zotero.org/settings/keys or follow the next instructions

### Query Guide

Biblio-retratos allows you to obtain metadata analyrics from your references database. You will be able to know, for instance, which authors you registered more frequently in Zotero in a determined number of years (i.e. when you are doing some dissertation, working on certain methodologies, when you were teaching certain courses).
You could also know from which years and places your sources come from more frequently. Or what library sub-collection use the wider variety of items or formats. Once you enter BR, after identification (it will not be necessary to write email or password again, since the system stores them) a screen shows up with the "Start query" button. When you click it, you must follow the following steps for a query.


![598b3bc6958e137fe5efc71a21a57eda.png](./598b3bc6958e137fe5efc71a21a57eda.png)



Step 1. Query filters
To start a query, you must choose through a check in the left side boxes, which item type AND/OR collection will be processed.

Step 2. Visualization fields.

Here you must choose through a check the field  by which the item type or sub-collection selected in the previous step must be searched.

Step 3. Periods of time.

After setting the query, click in "Query". It can take some time, since it is done remotely using your data stored in the Zotero Server. Duration will depend in connection speed, size of the database, number of search parameters, among others. Results will be shown in a frequency table that can be exported to Excel.

### Visualization Guide

To generate visualizations of charts or analytics, you must point the cursor to the 3 dots in the upper left side (typo en el original)  next to the time intervals and choose the appropiate graphic from the menu. Resulting visualiztion can be exported in .PNG

This example is a word cloud where the frequency of the authors captured in a whole database appear.

IMG. Demo of the complete visualization and query process.

### History

#### 2023: (re) design and development

| April     | Financial approval DINVP, Ibero                                                        |
|:---------:|----------------------------------------------------------------------------------------|
| May       | Work team formation                                                                    |
| June      | Analysis and redesign: from plugin to web application. Academic Computer Coordination. |
| July      | Feature catalogue. Logistical and financial management.
                               |
| August    | Database communication tests                                                           |
| September | Design and development of query                                                        |
| October   | Tests, assessment, approval of query module                                            |
| November  | Designs
and development of visualizations                                              |
| December  |                                                                                        |


#### 2024: beta and production

| January   | Completion of first phase, delivery and preliminary public presentation |
|-----------|-------------------------------------------------------------------------|
| February  |                                                                         |
| March     |                                                                         |
| April     |                                                                         |
| May       |                                                                         |
| June      |                                                                         |
| July      |                                                                         |
| August    |                                                                         |
| September |                                                                         |

### Design and trademark register

In process. All rights reserved to Universidad Iberoamericana, A.C.

### Credits

Teresa Márquez, researcher / Xavier Tortolero, developer

### Thanks
• Dirección de Investigación y Posgrado, Ibero
• Coordinación de Computo 
• Andrés Tortolero, Ingeniería de Datos, Ibero
• Jorge Angel González, INIAT, Ibero
• Sonia Montes, Dpto. de Letras, Ibero
• Dirección de Informática y Telecomunicaciones, Ibero
• Zotero ( We ❤️ Z forever!)

• An artifact is here a reinterpreted material or digital object. This idea is part of technology social studies by which technological objects are contingent products of human action both physical and interpretative.
