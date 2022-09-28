# Visualising the Catalogues of Digital Editions

## Introduction

Digital scholarly editions (DSE) are essential to arts and humanities research, but also, society and culture at large. They are the primary instrument through which textual and cultural heritage, expert knowledge, and public understanding are negotiated. Scholarly editions make documentary materials reliable, adhering to established editorial standards and rigorous intellectual practices to ensure that cultural artefacts are compiled and represented in a fashion that can be considered authoritative. 

DSEs are among the earliest projects in a field that used to be described as humanities computing and is currently mostly referred to as digital humanities (Dalbello 2011). This makes them especially suited for a diachronic approach, describing their change over time. While digital editions can vary greatly in scope and lifespan, a quantitative analysis of two of the most comprehensive data sources on digital editions can produce data-based insight into the developments within the field over time. This longitudinal approach to DSEs also means that historically successful formats for editions will shape the dataset and respective metadata. In practice, this means that most of the editions in the data sources will be based on or modelled after critical editions of text. 

Digital editions are positioned between drawing from archived material, and being an archive themselves (Dillen 2019, 266). In addition to that, digital editions also are web resources in need of archiving, lest they fall subject to link rot and very soon disappear from the web either for the lack of a persistent identifier or lack of maintenance. For digital editions past and present, two main data sources are available. Patrick Sahle lists around 800 editions in a curated catalogue (Sahle 2020), while the Catalogue of Digital Editions features about 320 digital editions in a database (Franzini 2012). Both sources have different criteria for inclusion, overlap in content and differ in granularity, yet these are the sources from which a history of DSEs will mostly draw. Analysis of these sources will present them in their scope, aim and usability for research, while highlighting underrepresented areas of data collection on digital scholarly editions.

DSE in the context of this paper are best defined using Patrick Sahle’s definition of editions as the “critical representation of historic documents'' (Sahle 2016). This definition is best suited for the editions described in both data sources, as Sahle compiled the first list of digital editions and the Dig-Ed-Cat explicitly refers to Sahle’s work as the basis of their data collection. These data sources from part of a response to Joris van Zundert, who calls on theorists and practitioners to “intensify the methodological discourse” necessary to “implement a form of hypertext that truly represents textual fluidity and text relations in a scholarly viable and computational tractable manner” (2016: 106) “Without that dialogue,” he warns, “we relegate the raison d’être for the digital scholarly edition to that of a mere medium shift, we limit its expressiveness to that of print text, and we fail to explore the computational potential for digital text representation, analysis and interaction.” This dialogue has begun in earnest (Driscoll and Pierazzo 2016; Boot et al. 2017), but a previous survey on the expectations and use of digital editions found that user needs are seldom satisfied by such resources (Franzini, Terras, and Mahony 2019). This dialogue can be augmented by the availability of data-driven insight into the development of digital scholarly editions over time, as well as an assessment of the scope and potential use of data sources for research on digital editions.

Digital editions have a long history of adapting to new challenges and possibilities presented by both changes in computational methods and research policy. While earlier DSEs were distributed through physical media, such as a CD-ROM sold through a publisher, digital platforms and browser-based access has become the standard practice for digital scholarly editions. With recent changes in EU funding directives, the majority of recent digital editions are based on open access models, further increasing accessibility of digital editions. Similarly, digital platforms providing metadata about digital editions can extend the accessibility of scholarly editing by providing the data from which to construct a history of digital scholarly editing and editions.

Exploring this history and at the same time assessing the available metadata on DSEs is the aim of this section. It presents the state of the two most comprehensive available sources on digital editions and details the methodology and visualisation process undertaken. This section is part of the larger C21 Editions project , a three-year international collaboration jointly funded by the Arts & Humanities Research Council (AH/W001489/1) and Irish Research Council (IRC/W001489/1). 

## Methodology

### Data sources on DSEs

Metadata on DSEs is primarily available through the [“Catalogue of Digital Editions”](https://dig-ed-cat.acdh.oeaw.ac.at/) (Dig-Ed-Cat). It incorporates other sources such as [Patrick Sahle’s list of DSEs](https://www.digitale-edition.de/exist/apps/editions-browser/index.html), and provides new data fields. This makes the Dig-Ed-Cat a key resource for a quantitative analysis of DSEs over time, with the project itself providing multiple ways to access and query the data. The Catalogue also fulfils a second, but equally important function: Through syndication with the German Datenbank-Infosystem [Database information system] [(DBIS)](https://dbis.ur.de/index.php?bib_id=alle&colors=3&ocolors=40&ref=about), DSEs listed in the Digt-Ed-Cat are discoverable resources for subscribing libraries. This greatly adds to the findability and impact of listed DSEs and is an important step in the integration of DSEs with other academic resources 

The common source of both catalogues can be traced back to a list of digital editions Patrick Sahle compiled in 1997[^1]. Continuously updating the list, Sahle would expand the catalogue to a list of currently 714 editions. In a comment on the collection, Sahle explains his motivation for compiling the list:

>Since most digital editions don't really fit into the traditional bibliographic model, usually there are no bibliographic library records available for them. We try to create bibliographic-like data as far as possible by collecting names of general editors, places of (virtual) publishing, publishing institutions, years of publishing and ISBN-numbers and other identifiers (where available) to help make these editions identifiable and referenceable. Whenever possible, we use snippets of self-description from the web pages of the editions as comments. Otherwise, there are edition descriptions from my (Patrick's) point of view. This is particularly the case for the oldest entries. Remember: some entries go back to the late 90s, early 00s and the concept of self description by quotation only started in 2008. (Sahle 2020)

This aim of increasing discoverability of digital editions in the light of poor bibliographic records for such works (Expressed in both the 2008 and 2020 version of the catalogue) is again found in the Dig-Ed-Cat’s syndication of editions to increase discoverability through library catalogues. Sahle’s list is compiled by himself and updated irregularly. Regarding data bias, Sahle explains:

>What I see is what you get. I am currently professor for Digital Humanities, affiliated to a history department at Wuppertal University, Germany. I have a background in (medieval) history and historical and humanities methodologies at large. Therefore, German editions will inevitably be overrepresented as well as historical editions, editions from Europe, and editions documented in Western languages. You can improve this situation by indicating underrepresented types of editions. (ibid)

This data bias is also found in the Dig-Ed-Cat, where the authors explain that a lack of a Asian or African digital editions in the catalogue is due to the project team not being able to evaluate these editions. Instead, users are invited to submit entries on editions from the global South.[^2] With both data sources, it must be considered that the data held is largely focussed on European projects.

### Structure

Both data sources are different in structure and granularity. Sahle describes his catalogue not using a controlled vocabulary, and few categories (Title, Subject Area, Language, Material, Period). Additionally, each entry has a description/comment and a link to the edition or publisher. Sahle deliberately does not remove inactive projects[^3] (though it is not clear if and when broken links are removed or updated). 
The Dig-Ed-Cat self-describes as a data agglomerator which again is connected to the Linked Open Data cloud to promote discoverability. Consequently, Dig-Ed-Cat features a much more granular approach to DSEs, including some fields with linked data vocabularies.[^4] Dig-Ed-Cat is designed as a participatory project, and users can submit new entries through the project’s github page. One of the data fields in the Dig-Ed-Cat is availability, indicating that inactive projects remain part of the data, however it seems that this value does not update automatically based on, say, the HTTP status of the URL. As part of the granular approach and voluntary contributions from the DSE community, some fields concerning funding source and amount per project are seldom filled out. The analysis in this paper will largely be based on the granular data available through the Dig-Ed-Cat, especially with regards to longitudinal developments in the field.

### Data Access

Dig-Ed-Cat being a data agglomerator and data source, it features convenient access to underlying data. While the project homepage features extensive data visualisations and a SPARQL endpoint[^5], it also provides Open Access to the underlying data which can be accessed in .csv format. 
Sahle’s catalogue - referring here to version 4.0, released in 2020 - also has made available its data source[^6]. The data is structured in TEI-XML and can be translated into a dataframe or .csv file for a quantitative analysis.[^7] Before version 4.0, the website itself could be scraped for edition data, although this includes somewhat more effort especially in regards to data cleaning.

### Analysis

With the data available, the main objective of the analysis is to produce a longitudinal analysis of DSEs within the scope and constraints of the respective data sources. In most cases, the more granular Dig-Ed-Cat is the preferred source (especially since Dig-Ed-Cat provides an end date field indicating the actual or envisioned end of the active development), while in some cases the larger data source provided by Sahle yields more conclusive results. Acknowledging the bias and limitations in both sources, the aim of this analysis as a whole is to understand long-term developments within the field of DSE and at the same time show the value of comprehensive data sources on digital editions for research purposes.

## Key Findings

### Overview

To gain a first overview of the dataset, the first step in visualising is to show editions over time. For this scenario, the data extracted from Sahle’s catalogue can be used to show the number of editions over time. This results in the following visualisation:

![Editions per year, based on Sahle's Catalogue of Editions](https://user-images.githubusercontent.com/33122848/192783972-63e300ea-0c75-4d29-8359-ce1f3f39f770.png) [*Figure 1: Editions per year, based on Sahle's Catalogue of Editions*](https://public.tableau.com/app/profile/michael1760/viz/Sahle_EditionsYear/Dashboard3)

Note that Sahle’s catalogue uses multiple dates for editions, including first publication, second editions and relaunches. The data used here is the first publication date. The visualisation shows that the oldest edition in the data source goes back to 1988, while the latest entry is from 2022. The number of editions increases until 2015, then sharply declines. This is likely due to the fact that editions only become part of the catalogue after publication and works in progress are less likely to be featured.

To get a better understanding of the works in progress and the average lifespan of a digital edition, Dig-Ed-Cat provides a value for the end date (usually this indicates the official end of the project and funding). Complementing the two sources, it is possible to plot individual editions ordered by their start date:

![Dashboard 2(1)](https://user-images.githubusercontent.com/33122848/192785494-3800e63c-ee8e-439e-8f51-39f10cc67d6b.png) [*Figure 2: Project duration by start date*](https://public.tableau.com/app/profile/michael1760/viz/C21_Start_End_Duration/Dashboard2)

Since the Dig-Ed-Cat features different date formats (likely due to non-standardized user inputs), and to help the readability of the graph, start dates are reduced to the year, while the difference between start and end dates is calculated in months. This difference then allows us to assign the colour and size. Noteworthy findings include one edition project with a reported duration of 0, one edition with two periods of activity and a number of long-term edition projects with future end dates. Since not all entries in Dig-Ed-Cat have an end date value, this visualisation only includes editions with both start and end dates. Similar to the previous visualisation, it seems likely that ongoing projects are less likely to have an end date, skewing the results accordingly.

The duration of edition projects is a useful value which in itself can be plotted over time to show the average project duration per year:

![Dashboard 2(2)](https://user-images.githubusercontent.com/33122848/192786785-c256c990-e2fe-4674-85d9-3489f46bcc3b.png) 
[*Figure 3: Average project duration in months per year*](https://public.tableau.com/app/profile/michael1760/viz/C21_Start_End_Duration/Dashboard2)

This graph again must be considered in the light of the scarcity of digital editions pre-1995. The few very old editions featured in Dig-Ed-Cat disproportionately influence the average project duration for these years. Nevertheless, it can be shown that the average project duration is 36 months, with a tendency to decline past 2010. The reason for this is speculative, but may be a combination of the availability of comprehensive tools to produce editions (mostly for textual editions), without the need to develop a custom solution from scratch. Likely further playing into this is also the fact that, as digital editions become more widely accepted as scholarly research projects, editions adapt to funding cycles and aim for results achievable within these cycles. 

Using the start date value, it is also possible to plot the number of projects started per year. This is helpful since it gives a better chance to also include ongoing projects which might not have an end date yet.

![Dashboard 2(3)](https://user-images.githubusercontent.com/33122848/192787327-00c70b10-1bcb-4bfd-8b6f-b754ef88ba5c.png) [*Figure 4: Number of projects per year*](https://public.tableau.com/app/profile/michael1760/viz/C21_Start_End_Duration/Dashboard2)

This graph then is similar to the first visualisation and shows a general upwards trend in the number of projects started per year. The average number of projects per year is around 7 to 8. The drop in numbers past 2015 is likely due to similar reasons as described in the first visualisation: Unfinished projects are less likely to report or be reported to the Dig-Ed-Cat. 

### Geography & Institutions

As both data sources mention the global North bias in their data, another interesting approach to the data is to visualise the location and languages of digital editions. The Dig-Ed-Cat features coordinates for editions, which easily lets us plot their location on a map:

![Dashboard 3(2)](https://user-images.githubusercontent.com/33122848/192788302-f5d8a203-1926-4e86-bc7c-287e161be999.png) [*Figure 5: Location of institutions mentioned in Dig-Ed-Cat*](https://public.tableau.com/app/profile/michael1760/viz/C21_LoctionsLanguages/Dashboard3)

The map confirms the concentration of DSEs in Europe and North America. Only four editions are located outside the global North, with none at all being located in Asia or South America. Among the locations, the UK, USA, Germany and Italy are the countries with the most editions. Such a result is hardly surprising given that both sources explicitly express their awareness of this bias in their documentation, yet it is a stark reminder that access to tools essential for the study of cultural heritage is subject to a strong divide between countries of the global North and South. 

A more granular approach to this uneven distribution of projects is to plot project languages amongst DSEs. Dig-Ed-Cat allows combinations of languages within one field, so that bilingual editions are less likely to rank highly. The language selection refers to the source material of the edition, not the interface (although it is unclear if all entries are correctly labelled) 

![Dashboard 3(3)](https://user-images.githubusercontent.com/33122848/192788899-67f6f516-5fdd-4cee-a6fe-9bc22b2ca601.png) [*Figure 6: Primary material languages*](https://public.tableau.com/app/profile/michael1760/viz/C21_LoctionsLanguages/Dashboard3)

The most widely used language is English, followed by Latin, German, Hungarian, Italian and Spanish. This further confirms a bias towards North American and European institutions already found in the previous visualisation. This Western-centeredness is addressed by the authors in the FAQ section of the Dig-Ed-Cat: 

>Q. Why are there no Asian and/or African digital editions in the Catalogue? A: Because the team cannot read those languages and we hesitate to rely on browser translation plugins as any machine translation errors would go unnoticed and possibly lead to incorrect cataloguing. We're eager to fill this gap but need help from users to do so. (Franzini 2022)

What is of further interest is the level of centralization between institutions. While in the above map, each dot represented an institution, it did not account for the number of projects housed at that institution. The map revealed a distribution within Europe and North America, but did not allow us to make clear statements about the number of projects per institution. Regarding the data source, Dig-Ed-Cat features institutions, but also allows for a combination of institutions. Further, editions might ont be housed at academic institutions at all, but at private or public institutions. Plotting the number of projects per institution produces the following graph:

![Dashboard 4(1)](https://user-images.githubusercontent.com/33122848/192789445-d9e67a2a-a56e-47a3-bb85-7f2ca0a87251.png) [*Figure 7: Number of projects per institution*](https://public.tableau.com/app/profile/michael1760/viz/C21_Institutions/Dashboard4)

Because of the inconclusive data, this is to be taken as indicative only. Rather than rating institutions against each other, the point that can be made here is that the data on digital editions - as Western-centred as it is - is rather evenly distributed with only 10 institutions having more than five projects on record. This may indicate that DSEs are more projects of individual scholars than institutions. The data in this case is hard to check for accuracy, with potential error sources being collaborations between institutions (University College Cork and University of Sheffield would, for example, count as *one* new institution rather than *two*). A more productive way this data can be used, however, is to divide the number of projects per year by the number of institutions. The longitudinal perspective allows us to - within the constraints of the available data - understand the level of centralization per year.

![Centralization](https://user-images.githubusercontent.com/33122848/192789920-77e2c2ba-42ec-4332-b756-2c702dbf40fb.png) [*Figure 8: Centralization, Relation between active Projects and Institutions per year*](https://public.tableau.com/app/profile/michael1760/viz/C21_centralization/Centralization)

The moving average bar shows the centralization for each year, where high values indicate more projects than institutions and a value of 1 indicates maximal distribution of projects between institutions. The total average shows a low centralization of only ~1.1 projects per institution and, while pre-2000 years saw relatively high centralization scores, with a growing number of projects came a general drop in centralization. Looking at the data from this perspective shows that the field of DSEs has successfully been kept open and digital editions have not become “monopolised” by a select few institutions. 

### Licensing & Access

Reasons for this low centralization are likely the move towards Open Access models for digital editions and permissive licensing. Dig-Ed-Cat records both the assigned licence as well as the access model for editions. Using this data, it becomes possible to plot both in one graph:

![Sheet 9(1)](https://user-images.githubusercontent.com/33122848/192791377-4e5b5021-4cca-4021-a800-de97276781df.png) [*Figure9: Open Source licencing and Open Access models in DSEs over time*](https://public.tableau.com/app/profile/michael1760/viz/C21_CcOpenSource/Sheet9#1)

What we can see in this graph is that both use of open source licensing and open access licences increased in the early 2000s, around the same time that the centralization value dropped and stayed at the new lower level. Combining the date in such a way allows one to understand the influence of licensing (and consequently, the availability of open source tools for digital editions) on the field as a whole. Further noteworthy here is the life cycle of such policy changes: While 2005 sees open source become a standard (<50%) practice, the same is only true for Creative Commons licensing from 2015 on. With recent change in EU funding directives (Open Access as the defined standard for research outputs where possible), these trends are likely to be sustained.

### The Text Encoding Initiative

![Dashboard 3(4)](https://user-images.githubusercontent.com/33122848/192791903-b9094387-be70-465e-9a8a-7509c0eb9fb5.png) [*Figure 10: Useage of TEI-XML over time*](https://public.tableau.com/app/profile/michael1760/viz/C21_XML/Dashboard3)

When speaking of open tools to benefit the field of digital editions, the key tool which had a measurable impact on the field is the Text Encoding Initiative (TEI) Guidelines. Dig-Ed-Cat measures the transcription method on a scale from 0 (no XML and no TEI) to 0.5 (XML but no TEI) to 1 (XML-TEI). This allows us to plot the average value for this field over time. From its introduction in 1990, it took XML-TEI 31 years to establish itself as the standard (used in <50% of editions) practice for source material encoding in digital scholarly editions. While its adaptation varied between 1987 and 2002, adaptation steadily increased from thereon. This data shows both the timescale of introducing a standard in encoding as well as the importance of XML-TEI. XML has been the standard since 2002, and XML-TEI has been the encoding standard since 2012. This again relates to the drop in centralization and the increase in open source licensing in DSEs. Relating the last three quite different approaches to the question how tools and service models impact centralization in digital editions, we can now with some certainty say that there is a relationship between the use of open source tools and open access models and the level of centralization, that is the relation between number of institutions and number of editions.

### Interfaces and Interoperability

![Dashboard 3(5)](https://user-images.githubusercontent.com/33122848/192792415-b9b9d2f5-3a02-4408-ab5d-c40840748fa7.png) [*Figure 11: Availability of API or print function*](https://public.tableau.com/app/profile/michael1760/viz/C21_ApiPrint/Dashboard3)

The question in this section relates to the possible different ways of accessing data in a digital edition. Two fields in Dig-Ed-Cat are potentially relevant for that. One measures the existence of an API access to the edition, the other records the availability of a print-friendly view. The documentation indicates that both are binary questions, with the first one not specifying any details about the level of API access and the latter not recording details about the print function. While print function and API access at first glance appear to be very different things, in the context of access they perform similar functions of helping to export data from the edition to use it in other contexts. While the general move towards open data in digital editions means that increasingly, the underlying data is available, this does not equal easy access or export as is provided by the two functions described here. 
The graph shows that API access is a rare function in DSEs, and is limited to a few, more recent editions. The ability to easily print sections (pages) of editions has been a consistent feature which is used in more than half of editions before 2010, and approximately ⅓ of editions past 2010. These results show that, despite the general move towards openness, interoperability and export functionality are not standart amongst digital editions. This is especially important when discussing the longevity of these digital projects.

### Availability

For edition availability, that is the assessment of how long an edition will be accessible after launch, both sources offer data. First, Dig-Ed-Cat features a value for current availability. This asks the submitting author if the edition is currently available. As Dig-Ed-Cat is an actively maintained resource, it seems that these checks are also performed periodically to identify broken links. Simply aggregating that data and comparing it against a check of all project URLs produces the following table:

| May 2022 URL status check | Dig-Ed-Cat March 2022 | % of Total Count |
|---------------------------|-----------------------|------------------|
|                           |None (Not available)   |5.94% |
|                           |True (Available)       |94.06% |
|404 (Not found)            |                       |6.79% |
|200 (Found)                |                       |93.21% |

*Table 1: URL availability in Dig-Ed-Cat*

These preliminary results seem to confirm that loss happens among digital editions. The difference between the two checks might be due to the time difference, and likely also due to ongoing loss. To gain a better understanding of the longevity of digital editions, it was decided to undertake a more detailed analysis of all editions listed in the more extensive catalogue maintained by Sahle. The goal was to produce an automated URL checker for each project URL listed by Sahle.
With the latest release 4.0 the underlying data for Sahle’s catalogue is openly available. The catalogue data is a structured XML-TEI file, which means some work in Python is necessary to extract the desired data. The following section will outline the steps taken along with the code for this project.


```python
from bs4 import BeautifulSoup as bs
import pandas as pd
!pip install lxml
```
This section instals the required libraries for this project. BeautifulSoup is a versatile parser for structured documents such as XML and HTML. While not a TEI-specific tool, in this case it can easily be used to find and extract data from TEI tags. Pandas is used to create dataframes and perform basic operations on them. BeautifulSoup normally comes with a built-in XML parser, but in case the installation is without, the last line instals it.

A look at the XML file itself shows us what we are looking for:

```
<TEI xml:id="e1"><teiHeader><fileDesc><titleStmt><title>L’année 1437 dans
            la pratique de Pierre Christofle, notaire du Châtelet d’Orléans - Digital Scholarly Editions Catalog Entry</title><author>Catalog entry by PS</author></titleStmt><publicationStmt><publisher>Published by Patrick Sahle (Bergische Universität Wuppertal) and the project team</publisher><availability><licence target="https://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 (CC BY 4.0)</licence></availability></publicationStmt><sourceDesc><p>Research data collection, DSE catalog v. 4.0, based on earlier work (1996-2020)</p></sourceDesc></fileDesc><revisionDesc><listChange><change when="2018-02-21" who="PS" type="creation"/></listChange></revisionDesc></teiHeader><text><body><bibl><title>L’année 1437 dans
            la pratique de Pierre Christofle, notaire du Châtelet d’Orléans</title><rs type="sortkey">1437</rs><ref>http://elec.enc.sorbonne.fr/christofle/index.html</ref><edition>Par Kouky Fianu avec la collaboration d’Anne Fortier.
                    Paris: École nationale des chartes, 2016.</edition><date type="firstPubliction" when="2016"/></bibl><p>  "Pierre Christofle fut notaire
                royal à Orléans de 1423 à 1450, attaché à la prévôté pour qui il rédigeait des
                contrats portant le sceau de l’institution. Comme ses confrères, Pierre Christofle
                inscrivait dans un registre et en une forme abrégée les conventions qu’il attestait.
                Ces notes, au nombre de 387, rédigées entre le 1er janvier et le 29 décembre 1437,
                conservées aux Archives départementales du Loiret sous la cote 3E 10144, sont ici
                éditées dans leur ensemble. L’édition, indexée et prochainement téléchargeable,
                permet l’enquête sur le lexique des actes." [from resource] </p><note type="labels">[hier stehen normalerweise Kommentare von mir zum internen Gebrauch]</note><desc type="material" ana="charters">Kopiar, Notariatsurkunden</desc><desc type="subject" ana="history"/><desc type="language" ana="fr"/><desc type="era" ana="late_ma"/></body></text></TEI>
    <TEI xml:id="e2"><teiHeader><fileDesc><titleStmt><title>The Aberdeen...

```
For every of the 789 entries, the data from the <title>,  <ref> and the <date> for the first publication should be extracted. The structure of XML-TEI makes it easy to extract the values from these tags. First, the document needs to be loaded and parsed - read - by BeautifulSoup to recognize the tags. At this point, we do not need to specify whether the document is encoded in TEI or not.

```python
  with open("catalog_TEI.xml", "r") as file: #load the file
    bs_content = bs(file, 'lxml') #parse as XML

col ={'title':[],'url':[],'year':[]} #create columns for the DataFrame
df = pd.DataFrame(col) #create DataFrame
df.head() #check, should bring up empty DataFrame with columns now
```

The downloaded file “catalog_TEI.xml” is loaded and read by the XML parser. An empty DataFrame is created with three columns title, url, year as these are the values we are looking for at this point.
  
```python
result = bs_content.find_all("ref") #simple search to export all URLs, even review links
for t in result:
    print(t.text)
```
  
To show how well BeautifulSoup can process XML documents, this short statement is enough to find all <ref> tags and print out their text. Using t.text, we can select if we want the text of a tag or the attributes. This will become important later on. For now, the code prints out all links in the document:

![Screenshot 2022-09-23 at 14-49-30 Sahle_Url_check - Jupyter Notebook](https://user-images.githubusercontent.com/33122848/192795630-3b883a3b-da6c-42b6-ae1b-cddb653f98f9.png) *Figure 12: Extracted links*

Immediately, some issues become apparent. Some links are links to reviews or further information about the edition, not the edition itself. Also, some plain text in the <ref> field was also extracted. This happened because we selected all <ref> tags, when only specific tags are of interest for this analysis. Making use of the hierarchical structure of XML, we can select only the <ref> tags within a <text> tag:

```python
results = bs_content.find_all("text") #find all <text> tags
for entry in results:
    output = [] #create empty list for output
    title = entry.bibl.title.text #select the title by its tag
    title = " ".join(title.strip().split()) #Some titles have extra whitespaces, this removes them
    url= entry.bibl.ref.text #again, select urls by the <ref> tag
    date = (entry.find(type ="firstPublication")) #select only dates with the attribute "firstPublication"
    year = (entry.bibl.date.get('when')) #select the value of the  "when" field - the publication year
    df.loc[len(df.index)]=(title,url,year)

```  
 Each <text> tag indicates a separate entry in the catalogue. By searching for all and then iterating over the results, we can extract the required information for each entry. BeautifulSoup can navigate through the structure of the XML document and find the right <title> tag via its place in the hierarchy. As some titles extend over multiple lines and have line breaks and whitespaces between them, the next line removes them. Similarly, URLs are extracted by only selecting the <ref> tag inside the <bibl> inside the <entry> tag. This removes reviews and URLs not related to this project.
Extracting the correct date is a bit more complicated: within the <date> tag, multiple attributes indicate first publication and relaunch, such as 
`<date type="firstPubliction" when="1996"/><date type="relaunch" when="2015"/>`
Extracting the whole <date> tag would thus yield multiple dates. The solution is to first only select <date> tags that have the attribute “firstPublication” and then to extract the value from the “when” field. Finally, all three extracted values are added to the DataFrame.
  
![Screenshot 2022-09-23 at 15-18-33 Sahle_Url_check - Jupyter Notebook](https://user-images.githubusercontent.com/33122848/192796313-97737bbf-d0ac-43e5-8bb3-80ae8c7d2e55.png) *Figure 13: Extracted DSE data*

The next step is to prepare the URL status check. For this, we import a library that allows us to send out simple HTTP requests to the collected URLs.

```python
import requests #this will allow us to check html status of the pages
df['status'] = "NaN" #add a new column to the dataframe
```
An empty column is added to the DataFrame, this is where the HTTP status report will go.
  
```python
def check_url(url): #function to check all urls and report back
    try:
        request = requests.get(url, verify=False, timeout=10)
        print ("Checked URL "+ str(url) +", Status was "+str(request.status_code))
        return request.status_code
    except requests.exceptions.RequestException as e: #basic error handling, if no response is received, continue on
        return e
```
  
Then, we need a basic function to check the HTML status of the pages. The above code tries to get a request status code. Because some pages will not produce one, we also need a way to deal with any connection errors we might encounter. A very simple solution is to just return the error message and continue on with the next URL.

```python  
df['status'] = df['url'].apply(check_url) #now checking all urls for their status code, might take a minute
df.head() # checking one more time
df.to_csv('ouput.csv') #and output to a csv file for visualisation
```
  
With the above, the function is executed on each URL in the DataFrame and the result is stored in the newly created status column. The result should look like this:

![Screenshot 2022-09-23 at 15-25-38 Sahle_Url_check - Jupyter Notebook](https://user-images.githubusercontent.com/33122848/192797185-8c0c2850-9aef-40f6-a790-acefdc02be53.png) *Figure 14: Dataframe with completed URL check*

With the last line, we export the DataFrame to a .csv file for any further data cleaning and processing. Three main steps in data cleaning in this example were:

- In a few cases, no URL was in the catalogue and so no check could be run. These few empty field must be discarded for the analysis
- All connection errors are aggregated under the general error label. They count towards unreachable editions.
- It was found that a number of links referred to the Internet Archive. These links were marked up and visualised as a separate category.

Finally, the output can be plotted to show the percentage distribution of status codes for each year:

![Dashboard 4](https://user-images.githubusercontent.com/33122848/192797753-97dde1b3-cdb8-403d-bc6d-e45f8da0abb5.png) *Figure 15: DSE availability September 2022*

The results show that loss occurs for all years from 2021 onwards (excluding pre-1994, where scarcity of sources skews the results somewhat). It confirms the findings from Dig-Ed-Cat, but also shows how loss increases over time. If links referring to the internet archive are counted as signs of loss (which they should, for the Internet Archive’s crawler has no access to the underlying database and is likely not able to capture an edition in its entirety), the picture is sobering. Pre-2004 editions experienced a loss rate of no less than 25%, with 50% of 1999 editions being unreachable. In this brief case study, redirects are counted towards reachable sites, an assumption which is likely not correct in all cases as redirects will not in all cases lead to the original resource. The lack of completely lost pages (404) in the pre-1996 years aligns with Sahle beginning work on the catalogue in 1998. Earlier editions, already lost by then, probably never made it into the catalogue.

From a Web archiving perspective, the fact that a large percentage of Internet Archive links are found shows that no widely used preservation solution exists for Digital Editions. It is further unclear if the authors themselves deposited material into the Internet Archive, or if the list curators used the Internet Archive to reconstruct a lost edition. In either case, these links must be seen as not providing the full edition in any way.

## Conclusions

Visualising the two main data sources on digital editions shows the application of a data-driven approach to the historiography of digital editions. It produced insight into the development of the field over time as well as provided a critique of the existing data sources. While both sources are very different in their approach (Generally speaking, Sahle’s list is a curated collection of editions while the Dig-Ed-Cat is a data agglomerator) they were both very valuable sources of information for this study. 

The data analysis was, where possible, focussed on providing a longitudinal approach to assess the development of the field over time. Following a general overview of the number of projects in both data sources,  results showed the average project duration decreased over time, while the number of projects per year kept increasing. An investigation of languages and project locations confirmed a strong focus on Europe and North America. Referring back to the documentation supplied with both data sets, this data bias was acknowledged by both sources.

Moving on from a data overview was the discussion of centralisation in digital editions, that is the number of projects in relation to the number of institutions. It was found that the field is largely decentralised, with few institutions featuring more than one entry in the Dig-Ed-Cat. This centralisation of the field was related to the use of tools and licensing in digital scholarly editions. Using TEI-XML as an example, it could be shown that the introduction of text encoding standards coincides with a drop in centralisation. Further, licensing models (Creative Commons / proprietary licences) and Open Access models experienced an upward trend in the early 2000s, which has been sustained since. 

To understand the level of interoperability between digital editions, APIs in digital editions and export/ print functionality were visualised as graphs. While APIs and print views are far apart in terms of functionality, they both represent functions for data export and potential data re-use in other contexts. The analysis was able to show that, while print functionality has been a part of digital editions throughout, APIs are only found in a few editions. These results indicate that interoperability between digital editions is low, with no widely used data exchange format and only a handful of APIs available.

As the final part, the analysis was concerned with the availability and sustainability of digital editions. Here, the larger number of editions in Sahle’s list was chosen as the primary data source. The relevant data (Edition name, Year of first publication and URL) were extracted from the structured data source. Necessary steps were described to enable reproducibility and increase transparency in the analysis. Distinguishing between plainly unavailable URLs, server errors and links to the Internet Archive, loss rates could be determined to be around 5% per year, leading up to 25% to 50% of pre-2000 DSEs being unavailable. This result shows the need for a sustainable preservation solution for DSEs.

## References
“Acdh-Oeaw/Dig_Ed_Cat: Release For Zenodo.” 2018. https://doi.org/10.5281/ZENODO.1250797.
Boot, Peter, Anna Cappellotto, Wout Dillen, Franz Fischer, Aodhán Kelly, Andreas Mertgens, Anna-Maria Sichani, Elena Spadini, and Dirk van Hulle, eds. 2017. Advances in Digital Scholarly Editing. Sidestone Press.
Dalbello, Marija. 2011. “A Genealogy of Digital Humanities.” Journal of Documentation 67 (3): 480–506. https://doi.org/10.1108/00220411111124550.
Dillen, Wout. 2019. “On Edited Archives and Archived Editions.” International Journal of Digital Humanities 1 (2): 263–77. https://doi.org/10.1007/s42803-019-00018-4.
Driscoll, Matthew James, and Elena Pierazzo, eds. 2016. Digital Scholarly Editing: Theories and Practices. Open Book Publishers. https://doi.org/10.11647/OBP.0095.
Franzini, Greta. 2012. “Gfranzini/Digeds_Cat: First Release.” Zenodo. https://doi.org/10.5281/ZENODO.1161425.
———. (2015) 2022. “Gfranzini/DigEds_cat.” https://github.com/gfranzini/digEds_cat/blob/81df723e147e50cb68fc1eb4393b6b56cd8209e7/CONTRIBUTING.md.
Franzini, Greta, Melissa Terras, and Simon Mahony. 2019. “Digital Editions of Text: Surveying User Requirements in the Digital Humanities.” Journal on Computing and Cultural Heritage 12 (1): 1:1-1:23. https://doi.org/10.1145/3230671.
“History – TEI: Text Encoding Initiative.” n.d. Accessed March 16, 2022. https://tei-c.org/about/history/.
Sahle, Patrick. 2016. “What Is a Scholarly Digital Edition?” In Digital Scholarly Editing: Theories and Practices, edited by Matthew James Driscoll and Elena Pierazzo, 19–40. Open Book Publishers. https://doi.org/10.11647/OBP.0095.02.
———. 2020. “A Catalog of Digital Scholarly Editions v 4.0.” https://digitale-edition.de/index.html.

  
<!-- Footnotes -->
[^1]: See (https://v3.digitale-edition.de/vlet-about.html) "I've been interested in digital scholarly editing roughly since 1994. I still try to keep an eye on the ongoing developments in this area and I continuously collect hints on digital editions. This list is replacing my Virtual Library Page on "(Digitale) Editionstechnik" from the year 2000 which I retrospectively would call Version 2.0. There were even earlier lists from 1998 and 1997 which I now call V1.0 and V0.8 respectively."
[^2]: See the [FAQ section of the Dig-Ed-Cat](https://dig-ed-cat.acdh.oeaw.ac.at/faq/).
[^3]: Explained in the [about section of Version 4.0](https://www.digitale-edition.de/exist/apps/editions-browser/about.html), see Sahle (2020).
[^4]: “The data in the Catalogue is being hooked up to the [Linked Open Data (LOD)](http://programminghistorian.org/lessons/intro-to-linked-data) cloud to increase discoverability while supporting semantic integration and knowledge sharing. The linked data vocabularies currently connected to the Catalogue are [W3C Basic Geo](https://www.w3.org/2003/01/geo/), [FOAF](http://xmlns.com/foaf/spec/#), [GeoNames](http://www.geonames.org/ontology#), [Data Catalog](http://www.w3.org/ns/dcat#) and [Dublin Core Metadata](http://purl.org/dc/terms/). Institution data also links to [DNB (Deutsche Nationalbibliothek)](http://www.dnb.de/DE/Home/home_node.html) Catalogue IDs.” (“Acdh-Oeaw/Dig_Ed_Cat: Release For Zenodo” 2018)
[^5]: [SPARQL](https://www.ontotext.com/knowledgehub/fundamentals/what-is-sparql/) is a semantic query language for databases, allowing users to run custom queries on the Dig-Ed-Cat database.
[^6]: The data source is available [here](https://git.uni-wuppertal.de/dhsfu/sde-catalog).
[^7]:  For a detailed description of this process, the section on availability. <!-- Insert Link -->
