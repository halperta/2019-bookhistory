---
layout: page
title: Resources
Image:
---

# Tutorials
<ul class="post-list">
{% for post in site.categories.tutorial %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

# Digital Scholarship Lab
* For help using the course website or uploading your Critical Review to GitHub, visit the Digital Scholarship Lab at the Benson.
	* Office Hours: Wednesday 9-11 Friday 1-3.
	* Schedule an appointment: email lb-digital@utlists.utexas.edu
	* More Information: [http://sites.utexas.edu/llilasbensonds/digital-scholarship-lab/](http://sites.utexas.edu/llilasbensonds/digital-scholarship-lab/)

# Course Documents
* [A student collaborator's bill of rights](https://cdh.ucla.edu/news/a-student-collaborators-bill-of-rights/)
* [Online Participation Contract](../../pdf/OnlineParticipationContract.pdf)
* [Archival Studies Reading List](https://docs.google.com/document/d/1oRXH3AoaUfKLhYG3Vz0apCnxWua5mFR3dPHmV-2TVy0/edit?usp=sharing)
* *Sample Lib-Guides*
	* [http://libguides.tulane.edu/latinos_NOLA](http://libguides.tulane.edu/latinos_NOLA)
	* [https://guides.lib.utexas.edu/digitalhumanities](https://guides.lib.utexas.edu/digitalhumanities)
	* [https://guides.lib.utexas.edu/latinamericanstudies](https://guides.lib.utexas.edu/latinamericanstudies)

# Sample Reviews of Digital Collections*  
* [American Archivist: Archival Technologies and Resources](https://www2.archivists.org/american-archivist-reviews/tech-and-resources)
	* [Bexar Archives Online](https://www2.archivists.org/sites/all/files/BexarOnline.pdf)
	* [Gallica: Digital Library of the Bibliothèque nationale de France](https://www2.archivists.org/sites/all/files/Gallica.pdf)
	* [A Tale of Two Plantations](https://www2.archivists.org/sites/all/files/Two%20Plantations.pdf)
* [sx archipelagos](http://www.smallaxe.net/sxarchipelagos/)
	* [Digital Archaeological Archive of Comparative Slavery](http://www.smallaxe.net/sxarchipelagos/issue02/monroe-review.html)
	* [The Caribbean Memory Project](http://www.smallaxe.net/sxarchipelagos/issue02/hudson-review.html)
* [SHARP News e-resources reviews](http://www.sharpweb.org/sharpnews/category/e-resource/)

# Digital Collections
*Bibliographies of digital collections*  
* [SALALM: Latin American & Caribbean Digital Primary Resource](https://salalm.org/collection-development-resources/digital-primary-resources/)
* [Crowdsourced: Latin American, Caribbean, and Latinx Digital Humanities Projects & Resources](https://docs.google.com/document/d/1JE5s77JETxUC6Qx_ZOd7aiRxfr2WBPNDweTemJGcYT8/edit?usp=sharing)
* [US Latinx DH projects database](https://docs.google.com/spreadsheets/d/1wtOeETfLvCv4ZYKxj0xiB6mqh3GfFqvRv8U9LVr_OkM/htmlview)

*Collections hosted by the University of Texas*  
* [Texas Archival Resources Online](https://legacy.lib.utexas.edu/taro/)
* Archivo Hist&oacute;rico de la Polic&iacute;a Nacional: [UT Website](http://ahpn.lib.utexas.edu/); [Guatemala website](http://archivohistoricopn.org/)  
* [Latin American Digital Initiatives](https://ladi.lib.utexas.edu/)  
* [Radio Venceremos](av.lib.utexas.edu/index.php?title=Category:Radio_Venceremos) (Note that this requires http (not https) and Flash, so it might not work with phones, tablets, or browsers like Chrome. Try Firefox.)  
* [Gabriel Garc&iacute;a M&aacute;rquez Archive Online](https://hrc.contentdm.oclc.org/digital/collection/p15878coll51/)  

*Colonial Collections hosted elsewhere*  
-   [Bureaucracy on the Ground in Colonial Mexico: The Visita of 1765](http://sites.utexas.edu/llilasbensonds/resources/galvez-visita/)
-   [Catalogación Colaborativa Fundación Histórica Neograndina](http://neogranadina.org/catalogacion-colaborativa/):  descripción y catalogación de documentación histórica perteneciente a los siglos XVI y XVII del fondo Notaría Segunda de Archivo Histórico Regional de Boyacá
-   [Catálogo Colectivo Marcas de Fuego](http://www.marcasdefuego.buap.mx:8180/xmLibris/projects/firebrand/)
-   [Codex Mendoza](http://codicemendoza.inah.gob.mx/inicio.php)
-   [Códices de México](http://www.codices.inah.gob.mx/pc/index.php)
-   [A Colony in Crisis](https://colonyincrisis.lib.umd.edu/)
-   [La Biblioteca Digital de Pensamiento Novohispano](http://www.bdpn.unam.mx/)
-   [Digital Aponte](http://aponte.hosting.nyu.edu/): A site dedicated to the life and work of [José Antonio Aponte](http://aponte.hosting.nyu.edu/jose-antonio-aponte/).
-   [Early Caribbean Digital Archive](http://ecdaproject.org/)
-   [Escritos de Mujeres](http://www.iisue.unam.mx/escritoras/)
-   [laflorida.org/ ](https://t.co/2Uj9sVGijF) "a multidisciplinary perspective of colonial Florida's rich history"
-   [Liberated Africans](http://liberatedafricans.org/): historical resources about liberated Africans in Cuba, Brazil, and Sierra Leone (images, court cases, documents)
-   [Lienzo de Quauhquechollan](https://lienzo.ufm.edu/vea-lienzo/vea-el-lienzo/)
-   [Mapping New York City's Nineteenth-Century Latina/o Press](http://www.babblelab.org/c19latinopress/)
-   [Mesolore](http://www.mesolore.org/): a bilingual resource for scholars and students of Mesoamerica.
-   [Mesoamerican Painted Manuscripts at Tulane University's Latin American Library](https://digitallibrary.tulane.edu/islandora/object/tulane%3Ap16313coll37)
-   [Multepal](http://multepal.spanitalport.virginia.edu/) : thematic research collection of the Popol Wuj
-   [Musical Passage: A Voyage to 1688 Jamaica](http://www.musicalpassage.org/#home)
-   [Nahuatl/Nawat](http://nahuatl-nawat.org/aboutus): Compilación y transcripción de documentos náhuatl/náwat centroamericanos
-   [PESSCA](https://colonialart.org/): Project on the Engraved Sources of Spanish Colonial Art
-   [Primeros Libros de las Américas](http://primeroslibros.org/): repository of early American printed books
-   [Power of Attorney](https://www.powerofattorneynative.com/): a geography of indigenous legal culture through digital maps and visualizations.
-   [Reading the First Books](http://sites.utexas.edu/firstbooks/): Multilingual, early modern OCR for Primeros Libros
-   [Slave Revolt in Jamaica, 1760-1761](http://revolt.axismaps.com/)
-   [Spanish Paleography Tool](http://spanishpaleographytool.org/)
-   [Texas Slavery Project](http://www.texasslaveryproject.org/maps/hb/)
-   [Texas Domestic Slave Trade Project](https://txdst.la.utexas.edu)
-   [TICHA](https://ds-omeka.haverford.edu/ticha/en/index.html): A digital text explorer for colonial Zapotec.
-   [Trans-Atlantic Slave Trade Database](http://www.slavevoyages.org/)
-   [Wired Humanities Projects](https://blogs.uoregon.edu/wiredhumanitiesprojects/)
-   [Nahuatl Dictionary](http://whp.uoregon.edu/dictionaries/nahuatl/)
-   [Mapas Project](http://mapas.uoregon.edu/)
-   [VISTAS](https://vistas.ace.fordham.edu/): colonial art history
-   [Voyages: Trans-Atlantic Slave Trade](http://www.slavevoyages.org/) 

