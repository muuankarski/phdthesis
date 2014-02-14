---
title: Väitöskirjaprojektin yhteenveto
author: Markus Kainu
lang: finnish
output:
  html_document:
    toc: true
    theme: flatly
---

******************************

Johdanto
========

Tälle sivulle on linkitetty väitöstutkimukseni kannalta tärkeimmät projektit. Sivujen vasemmassa laidassa on aina ko. sivun sisällysluettelo. Kuvaus projektin nykytilasta ja lähitulevaisuudesta löytyy kohdasta [Tapahtunutta vuonna 2013 ja suunnitelmaa vuodelle 2014](plan2014.html). Aikaisemmat vuosikertomukset ja suunnitelmat löytyvät [hieman alempaa](#toc_2). Ajantasainen projektin yhteenveto löytyy [sivun lopusta](#toc_11). 


```
## [1] "Päivitetty 2014-02-14 18:33:24"
```



Tämän sivun linkit johtavat projektieni sivuille [GitHub](https://github.com/):ssa. *Github* on yksi monista [*git*](http://fi.wikipedia.org/wiki/Git)-[versionhallinnan](http://chronicle.com/blogs/profhacker/a-gentle-introduction-to-version-control) *hosting*-palveluista. Github:ia käytetään etupäässä avoimen lähdekoodin ohjelmistoprojekteissa, mutta yhä enemmän myös akateemisten tutkimusprojektien alustana. Itse pidän kirjaa tekstieni ja analyysieni versiohistoriasta *git*:n avulla ja julkaisen versiohistoriat etenkin yhteistyöprojekteissa *GitHubissa*. Tämän sivun linkit johtavat projektien ns. *julkisille sivuille*, joista ei pääse ilman tunnuksia ja minun valtuutusta katsomaan itse tutkimuksen etenemistä. Sitten itse asiaan.



Vuosikertomukset ja suunnitelmat
============

-   [Tapahtunutta vuonna 2013 ja suunnitelmaa vuodelle 2014](plan2014.html)
-   [Tapahtunutta vuonna 2012 ja suunnitelma vuodelle 2013](plan2013.html)
-   [Happened in 2010-2011 and Research plan for years 2012-2013](plan2012.html)
-   [Alkuperäinen suunnitelma](plan2010.html)




Projektit
==============

Alla oleviin taulukoihin olen jäsennellyt ja linkittänyt kaikki väitöskirjatutkimuksen ja oman ammatillisen osaamiseni kannalta tärkeimmät projektit. Ensimmäisenä ovat *artikkelikäsikirjoitukset*, toisena *data- ja metodiprojektit* ja kolmantena *muut ammatilliset kirjoitusprojektit*. Kunkin projektin alla on otsikko, lyhyt kuvaus sekä linkki projektin github sivuille. Suljetuissa projekteissa näkyvissä ovat vain ns. julkiset sivut sillä hetkellä, kun taas avoimissa projekteista pääsee suoraan projektikansioon.

Artikkelikäsikirjoitukset
---------

*Artikkelikäsikirjoitukset* olen luokitellut *vertaileviin*, *Venäjän tapaustutkimuksiin* ja *flopanneisiin* artikkelikäsikirjoituksiin. 

### Comparative post-socialist

| Title | Type | Link | Status |
| ----- | ---- | ---- | ------ |
| Attributions for poverty in Post-Socialist countries | Article draft with Mikko that **will be part of thesis** | [github](http://muuankarski.github.io/attributions/) | To be submitted in early 2014 |
| Welfare State Entry and Exit: Combatting macro-economic and life-course sustainability deficit in Europe | Article draft with Olli Kangas & Joakim Palme **will NOT be part of thesis** | [github](http://muuankarski.github.io/exitentry/) | Submitted in Dec 2013 |
| European regimes of material deprivation: Temporal dynamics of components of material deprivation in the EU27 countries | Article draft that **will be part of thesis** | [github](http://muuankarski.github.io/deprivation/) | Some work. To be submitted Autumn 2014 |

### Russian spesific

| Title | Type | Link | Status |
| ----- | ---- | ---- | ------ |
| Targeting performance of monthly cash payments at multidimensional poverty in Russia in 2000 - 2011 | Article draft that **will be part of thesis** | [github](http://muuankarski.github.io/monetisation/) | Lots of work. To be submitted in late 2014 |
| Geographies of deprivation in Russian Federation  | Article draft that **will be part of thesis** | [github](https://github.com/muuankarski/geographies) | Lots of work. To be submitted in late 2014 |
| Modernisation and Russian Welfare regime | Article draft with Markku Kivinen, Meri Kulmala and Jouko Nikula for [Demokratizatsiya: The Journal of Post-Soviet Democratization](http://www.metapress.com/content/122625/?p=c4ba001b0a7d425585532b911e01c1b0&pi=2). **will NOT be part of thesis** | No project running yet. | To be submitted in late spring 2014 |

### Ones that have not taken off

| Title | Why not | link |
| ----- | ------- | ---- |
| WHO GETS WHAT - AND WHERE: Regional poverty outcomes of social assistance in enlarged EU: The case of Poland and Austria  | Has been pending useless availability of regionally aggregated data both in LIS and EU-silc | [github](http://muuankarski.github.io/regional2013/) |
| Social cash benefits and poverty spells in post-soviet Russia | This was replaced by the **monetisation article** above. Some longitudinal work should be done using RLMS some time.. | [abstract](pending/pending.html) |


Data ja metodiprojektit
---------

Data- ja menetelmäprojektit ovat merkittävä osa väitöstutkimusta. Ei vain tutkimuksen tekemisen puitteina, vaan myös menetelmäartikkelin kirjoittamisen aiheena. Yksi artikkeleista tulee käsittelemään kirjoittamaani rustfare-pakettia, jonka avulla on mahdollista käyttää avointa Venäjä-dataa suoraan R-ohjelmistossa. [rOpenGov](http://ropengov.github.io/)-projektissa taas meillä on tarkoituksena julkaista myös perinteisiä kanavia pitkin, mutta aikaisintaan syksyllä 2014, riippuen miten saamme projektiin lisää kv-kehittäjiä ja muita yhteistyötahoja (ja rahaa) mukaan.

### rOpenGov-projektiin liittyvät

| Title | Type | link |
| ---- | ---- | ---- |
|**rOpenGov** - R Ecosystem for Open Government Data and Computational Social Science | A joint project of many developers internationally | [github - website](http://ropengov.github.io/) [github - code base](https://github.com/rOpenGov) |
| **rQog** - Search, extract and format data from the Quality of Government Institute data |   Simple, targeted library for QoG-database | [github](https://github.com/muuankarski/rQog) [documentation](http://markuskainu.fi/rqog/) |
| **rustfare** - Algorithms for Russian data | My own project within rOpenGov | [github](https://github.com/rOpenGov/rustfare) [documentation](http://markuskainu.fi/rustfare/) |


### Omat sekalaiset visualisointi/ käyttöliittymäprojektit

| Title | Type | link |
| ---- | ---- | ---- |
| Exploring Russian Census data using R | Data mining project for article | [github](https://github.com/muuankarski/censusanalysis) |
| GoogleVis aka bubble chart visualisation of Rosstat Regional Data | Visualization of Russian regional data for teaching and exploring the data | [github](https://github.com/muuankarski/rusRegionGVis) |
| Quality of Government Institute data as Motion Charts | Visualization of Quality of government data for teaching and data exploration | [github](https://github.com/muuankarski/QogGVis) |

Muut ammatilliset kirjoitusprojektit
---------

| Title | Type | Link | Status |
| ---- | ---- | --- | ----- |
| Kainu, Markus, & Niemelä, Mikko. Taloudelliset elinolot ja elämänvaiheet Euroopassa. In Eurooppalaiset elinolot (Forthcoming), edited by Mikko Niemelä. Helsinki: Kansaneläkelaitos, 2014. | Johdanto-luku kirjaan | | Accepted |
| Kainu, Markus. 2014. Open research methods in computational social sciences and humanities: introducing R | Luku Jessica Parland.von Essenin ja Kenneth Nybergin toimittamaan [Historia i en digital värld](http://digihist.se/)-kirjaan | [github](https://github.com/muuankarski/rlang) | eka versio submitattu |



Väitöskirjaprojektin yhteenveto
==========================

Opintosuoritukset
--------------------------


### Vuosi 2010

| Suoritus | Pisteet | Kurssi/konferenssi | Suoritus |
| -------- | ------- | ------------------ | --------------- |
| kesakoulu | 3 | VASTUU-tutkijakoulu Mekrijärvellä 27.-28.5.2010 | paper & presentation |
| Kv-konferenssi |  5  | [‘Issues in Social Security’: The Global Crisis : Impact and Challenges for Social Security - Sigtuna, Sweden, 16-18 June 2010](http://webh01.ua.ac.be/csb/fiss/?page_id=53) | paper & presentation |
| Kesäkoulu | 5 | [Civil Society Around the Baltic Sea (Neru Network) 6-11.6, 2010](http://www.helsinki.fi/aleksanteri/neru/activities/2010.htm) | paper & presentation |
| Kv-konferenssi | 5 | [ 8th ESPAnet Conference 2010 Social Policy and the Global Crisis: Consequences and Responses, 2.-4.9.2010 in Budapest](http://tatk.elte.hu/news-english/1398-espanet-2010-annual-conference) | paper & presentation |
| **Yhteensä** | 18 | | |


### Vuosi 2011

| Suoritus | Pisteet | Kurssi/konferenssi | Suoritus |
| -------- | ------- | ------------------ | --------------- |
| kesakoulu | 3 | VASTUU-tutkijakoulu Lammilla 26.-27.5.2011 | paper & presentation |
| Kv-konferenssi | 5 | [ 18th International Research Seminar on Issues in Social Security, June 8.-10.6, 2011.](http://webh01.ua.ac.be/csb/fiss/?page_id=48) | paper & presentation |
| kesäkoulu | 5 | [ESPANET/RECWOWE summer school: Welfare States of Eastern and Western Europe, 27.6-8.7.2011](http://www.socialpolicy.ed.ac.uk/recwowetac/summer_schools/budapest_2011) | paper & presentation |
| Kesäkoulu | 5 | Life course dynamics and the mechanisms of social inequality, 29.8 –2.9, 2011 (TCWR, University of Turku) | kurssi + harjoitustyö |
| **Yhteensä** | 18 | | |


### Vuosi 2012

| Suoritus | Pisteet | Kurssi/konferenssi | Suoritus |
| -------- | ------- | ------------------ | --------------- |
| kesäkoulu | 5 | The Finnish Centre of Excellence in Russian Studies Summer School: Choices of Modernisation, June 3-8, 2012  | paper & presentation |
| kv-konferenssi | 5 | [ISA RC19 Oslo, 23-25.8.2012](http://www.nova.no/id/24834) | paper & presentation | 
| kv-konferenssi | 5 | [10th ESPAnet Anniversary Conference 2012 Edinburgh. September 7, 2012.](http://www.espanet2012.info/in_edinburgh) | paper & presentation |
| **Yhteensä** | 15 | | |


### Vuosi 2013

| Suoritus | Pisteet | Kurssi/konferenssi | Suoritus |
| -------- | ------- | ------------------ | --------------- |
| kv-konferenssi | 5 | [1st International Russia Longitudinal Monitoring Survey of HSE User Conference, Moscow, 17.-18.5, 2013](http://www.hse.ru/rlms/conference) | paper & presentation |
| kesäkoulu | 5 | [Oslo Summer School in Comparative Social Science Studies 2013: Using Spatial Data & Workshops in the Social Sciences: An Applied Survey  22.-26.7, 2013](http://www.sv.uio.no/english/research/doctoral-degree/summer-school/courses-2013/bivand.html) | ennakkolukemisto & osallistuminen |
| kesäkoulu | 5 | Aleksanteri-instituutin tutkijakoulun & Glasgow'n yliopiston kesäkoulu 8-12.6.2013 Ahvenanmaalla | paper & presentation |
| kv-konferenssi | 5 | [3rd International Annual Research Conference: “Cultural and Economic changes under cross-national perspective”. HSE-Moscow, 12.-17.11, 2013](http://lcsr.hse.ru/en/Conference2013) | paper & presentation |
| **Yhteensä** | 20 | | |


### Yhteensä vuosina 2010 - 2013

Kesäkouluista ja kv-konferensseista yhteensä ~ **71** opintopistettä. Valtaosa odottaa vielä rekisteriin viemistä. Tämän lisäksi on aika paljon kaikkea muuta seminaaria ja kurssia, josta voisi opintopisteitä tulla.

Artikkelit
-----------------------------

1. Attributions for poverty 
    - lähtee ensi viikolla kielentarkastukseen
    - lähtee huomenna Moskovaan (HSE associate researcher konferenssi maaliskuun lopussa)
2. Eu-silc material reprivation pitkittäispaperi 
    - vaatisi kuukauden intensiivistä työtä
3. Venäjän paikka+köyhyyspaperi 
    - odottaa [2010 väestölaskennan mikrodatan julkaisua](http://www.perepis-2010.ru/). Se pitäisi tulla hetkenä minä hyvänsä.
4. Venäjän luontoisetuuksien rahamääräistämistä käsittelevä paperi
    - vaatisi reilusti paneutumista 
    - Pidin juuri luennon [köyhyydestä ja sosiaaliturvasta Venäjällä](https://github.com/muuankarski/sosiaalipolitiikka-venaja) Porvoossa ikäihmisten yliopistossa ja kehittelen paperia vähän eteenpäin luentoa kirjottaessani
5. rustfare-pakettia kuvaava menetelmällinen artikkeli
    - vaatisi pari viikkoa paketin viimeistelyyn ja kuukauden paperin kirjoittamiseen


Rahoitussuunnitelmat
----------------------------

Alkuvuonna minua on pyydetty mukaan kahteen suurempaan menetelmiin ja teknologiaan liittyvään rahoitushakuun HY:ssä, joihin olen tehnyt vähän töitä ja nimenä mukana. Myös yliopiston ulkopuolelta on tiedusteltu mahdollisuuksia koodata analyysisovelluksia ja olen kertonut olevani ilman sopimusta maaliskuun lopulta alkaen ja olevani kiinnostunut lyhyistä projekteista. Saan tarkempaa selkoa vielä tämän kuun puolella näistä. Muutenkin R-taidoille alkaa olla myös Suomessa hiljalleen kysyntää yliopistojen ulkopuolella. (USA:ssa R-kieli oli viime vuonna parhaiten palkattu it-taito ([Dice Tech Salary Survey 2013-2014, s. 9](http://marketing.dice.com/pdf/Dice_TechSalarySurvey_2014.pdf)).) Koti-isan ja konsultin yhdistelmä on myös yksi vaihtoehto, mutta Turun yliopiston tilanne luonnollisesti kiinnostaa kovasti.


Yhteenvetoartikkeli
================

**Poverty, place and income redistribution - Analysis of poverty dynamics and welfare state development in post-socialist transition**

*Summary article will be a lean and short introduction to my research project. It will provide an overarching conceptual and methodological frame for the individual articles and precisely speak out the contribution of the overall thesis and the individual articles.*

**Evolution**

| Conference | Date | Paper |
| ---------- | ---- | ----- |
| **Current state** | Feb 2013 | [Disposition](summary/summary.html)


