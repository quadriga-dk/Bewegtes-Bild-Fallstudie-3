# Erhebung und Nachnutzung

*Da diese Fallstudie sich auf die **Organisation, Aufbereitung und Publikation** von Daten entlang des filmwissenschaftlichen SFB-Teilprojekts der FU konzentriert, werden hier lediglich einige gängige Methoden, Beispiele und Hinweise für die Datenerhebung vorgestellt - es besteht kein Anspruch auf Vollständigkeit.*

## Erhebung von Forschungsdaten

Je nach technischem Erfahrungsniveau stehen unterschiedliche Methoden und Verfahren zur Verfügung, um Forschungsdaten in der Film- und Medienwissenschaft zu erheben oder zu generieren. Im Folgenden werden gängige Methoden vorgestellt.

### Erhebung mit digitalen Annotationstools
⟶ <span style="background-color:#FF7F7F;">**Niveau: Basis**</span> 

Für filmanalytische Untersuchungen eignen sich insbesondere digitale Annotationswerkzeuge wie <a href="https://www.advene.org/" class="external-link" target="_blank">Advene</a>, (zum Beispiel in Verbindung mit dem <a href="https://www.ada.cinepoetics.fu-berlin.de/ada-toolkit/index.html" class="external-link" target="_blank">AdA-Toolkit</a>), <a href="https://archive.mpi.nl/tla/elan" class="external-link" target="_blank">ELAN</a>, <a href="https://www.vian.app/" class="external-link" target="_blank">VIAN</a> oder <a href="https://frametrail.org/" class="external-link" target="_blank"> FrameTrail</a>. 

Das Erstellen von Annotationsdaten erfordert i.d.R. nur begrenztes technisches Vorwissen. Die Handhabung kann auf Grundlage verfügbarer Manuals, Open Educational Resources oder Projektdokumentationen schnell erlernt werden. Die jeweiligen Plattformen bieten oftmals ausführliche Dokumentationen und Tutorials an. 

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_ada_timeline.png
---
align: center
width: 100%
name: ada-timeline
---
Visualisierung von Annotationsdaten mit der AdA-Timeline
```

```{admonition} Annotationen erstellen mit dem AdA-Toolkit
:class: seealso
 In unserer <a href="https://quadriga-dk.github.io/Bewegtes-Bild-Fallstudie-1/intro.html" class="external-link" target="_blank">QUADRIGA Fallstudie: "Affektrhetorik in Online-Videos zur Klimakrise. Datengestützte Analysen audiovisueller Muster"</a> wird gezeigt, wie mit der für die Filmanalyse entwickelten Analyseontologie AdA (Toolkit) in Advene Annotationsdaten erstellt und visualisiert werden können.
 ```
### Data Dumps, APIs und SPARQL-Abfragen
⟶ <span style="background-color:#FF7F7F;">**Niveau: Fortgeschritten**</span>

Neben eigenen Erhebungen können Forschungsdaten auch über bestehende Datenquellen und Datensammelbanken bzw. Plattformen gewonnen werden.

Hierzu zählen insbesondere:
* Sogenannte **Data Dumps** offener Filmdatenbanken wie <a href="https://www.omdb.org/en/us/content/Help:DataDownload" class="external-link" target="_blank">OMDB</a> oder <a href="https://grouplens.org/datasets/movielens/" class="external-link" target="_blank">Movielens</a>.
```{admonition} Was sind Data Dumps?
:class: hinweis, dropdown
Data Dumps sind große bereitgestellte Datenmengen, die von einem Computersystem, einer Datei oder einem Gerät auf ein anderes übertragen werden {cite}`Cambridge_Dictionary_Data_Dump`.
```
* Technisch versierte Nutzer:innen können **API-Schnittstellen** kommerzieller und nicht-kommerzieller Dienste nutzen –  z. B. <a href="https://developer.imdb.com/non-commercial-datasets/" class="external-link" target="_blank">IMDb Non-Commercial Datasets</a>, <a href="https://developer.themoviedb.org/docs/getting-started" class="external-link" target="_blank">The Movie Database</a> (TMDb –  für nicht-kommerzielle Nutzung) oder die <a href="https://opensubtitles.stoplight.io/docs/opensubtitles-api/e3750fd63a100-getting-started)" class="external-link" target="_blank">OpenSubtitles</a> REST API.
```{admonition} Was sind API-Schnittstellen?
:class: hinweis, dropdown
Eine API (Application Programming Interface) ist eine Programmierschnittstelle zwischen verschiedenen Softwareanwendungen. Sie ermöglicht die automatisierte Kommunikation zwischen Programmen, um Daten oder Funktionen auszutauschen, also eine Form der "Maschine-zu-Maschine"-Kommunikation. Über APIs können Entwickler:innen auf Inhalte, Daten oder Dienste anderer Systeme zugreifen und diese in eigene Anwendungen integrieren {cite}`Poggel_2025`.
```
* Ebenso bietet beispielsweise das Portal <a href="https://www.wikidata.org/wiki/Wikidata:Main_Page" class="external-link" target="_blank">Wikidata</a> mittes eines <a href="https://query.wikidata.org/" class="external-link" target="_blank">SPARQL-Endpoints</a> semantische Abfragen an. Anleitungen und Abfragebeispiele sind in den Dokumentationen der Seite zu finden. 

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_sparql_abfrage.png
---
align: center
width: 100%
name: sparql-abfrage
---
Beispiel einer SPARQL-Abfrage mit dem Schlagwort "climate change"
```
```{admonition} Was ist ein SPARQL-Endpoint?
:class: hinweis, dropdown
SPARQL ist eine "graphenbasierte Abfragesprache", durch die Daten aus der webbasierten Beschreibungssprache RDF (Resource Description Framework) abgefragt werden können. Ein SPARQL-Endpoint ist eine URL, über die Benutzer:innen diese Abfragen stellen können. Aus großen Datenmengen, die im RDF-Format vorliegen, können mit SPARQL-Abfragen also gezielt Informationen abgerufen werden {cite}`Wikipedia_SPARQL_2026`.
```
### Erhebung mit Webscrapingverfahren
⟶ <span style="background-color:#FF7F7F;">**Niveau: Expert:in**</span> <br>
**Webscraping für fortgeschrittene Nutzer:innen mit Programmierkenntnissen (Python, R, JavaScript)**

Webscraping ist ein Verfahren der automatisierten Extraktion von Daten aus Webseiten. Scraper - das sind Codeskripte - analysieren die `html`-Struktur einer Website und filtern bestimmte vorgegebene Informationen raus, die dann in einer Tabelle (`dataframe`) strukturiert gespeichert werden können.
Unter Berücksichtigung rechtlicher Vorgaben und der jeweiligen `robots.txt` kann Webscraping als digitales Verfahren eingesetzt werden, um beispielsweise Filmdaten zu extrahieren, die nicht über Schnittstellen oder offene Data Dumps zugänglich sind.
In jedem Fall sind **Lizenzbedingungen**, **Nutzungsrechte** und **Datenschutz** zu prüfen, insbesondere wenn Daten kommerzieller Anbieter (z. B. IMDb, TMDb) nachgenutzt werden sollen.

```{admonition} Was ist eine "robots.txt"?
:class: hinweis, dropdown
Eine `robots.txt` ist eine einfache Textdatei in dem Hauptverzeichnis einer Website. Darin können Websiterbetreiber:innen vorgegeben, aus welchen Bereichen automatisierte Programme Daten auslesen können und aus welchen nicht. Teilweise enthält sie auch Angaben dazu, wie viel Zeit zwischen einzelnen Anfragen liegen soll, damit der Server nicht überlastet wird {cite}`Koster_et_al_2022,Poggel_2025`.
```

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_webscraping.png
---
align: center
width: 60%
name: webscraping-code
---
Illustratives Beispiel eines Webscraping-Skripts
```

```{admonition} Siehe auch:
:class: seealso
Detaillierte Informationen zum Thema Webscraping gibt es in unserer
 <a href="https://quadriga-dk.github.io/Bewegtes-Bild-Fallstudie-2/intro.html" class="external-link" target="_blank">QUADRIGA Fallstudie: "Quantitative Analyse der kommunikativen Barrierearmut des Berliner Senats (2011-2024). Eine Fallstudie"</a>
 ```

## Nachnutzung von Forschungsdaten

Ergänzend zur eigenen Datenerhebung besteht ebenso die Möglichkeit, auf bereits vorhandene oder veröffentlichte Forschungsdaten anderer Projekte zurückzugreifen.

Die Nachnutzung solcher Daten kann den Forschungsprozess erheblich bereichern, neue kreative Wissensdynamiken entstehen lassen und den Austausch zwischen verschiedenen Institutionen und Akteur:innen anregen {cite}`dang_forschungsdatenmanagement_2020`. Der Prozess wissenschaftlicher Erkenntnisgewinnung erweist sich als umso stabiler und nachhaltiger, je mehr auf dem vorhandenen Wissen der Fachdisziplin aufgebaut wird; dies schließt die Miteinbeziehung oder gar Neuperspektivierung bereits existierender Daten ein {cite}`RatSWD_2023`.
So können etwa vergleichende Analysen durchgeführt werden, Annotationspraktiken angeeignet, übernommen und erweitert oder bestehende Datensätze weiterentwickelt werden. Voraussetzung für eine "kreative und inklusive Wissensproduktion" {cite}`dang_forschungsdatenmanagement_2020` ist die uneingeschränkte Verfügbarmachung von Daten, so Dang. Welche Prinzipien hierbei eine Rolle spielen, werden wir im [Kapitel 2.5. Forschungsdatenmanagement](../02_forschungsdaten_fdm/forschungsdatenmanagement.md) diskutieren.

### Arten der Nachnutzung

Je nach Forschungsziel kann die Nachnutzung sehr unterschiedlich ausfallen:

1. **Analytisch**: Annotations- oder Transkriptionsdaten können nachgenutzt werden, um neue Fragestellungen, z. B. zu Bewegungsmustern oder Farbkompositionen, zu prüfen.
2. **Vergleichend**: Datensätze können, unter der Einbeziehung einer spezifischen wissenschaftlichen Fragestellung oder These, miteinander verglichen werden; ebenso können Lücken aufgedeckt und diskutiert werden.
3. **Kuratierend**: Daten aus offenen Registern und Repositorien können in die eigene Forschung eingebunden werden, um bestehende Datensammlungen anzureichern oder neue Zugangswege zu schaffen (z. B. Datenaggregation von Metadaten aus Filmdatenbanken).
4. **Didaktisch**: Forschungsdaten können für Lehrzwecke, z. B. als Übungsmaterial in Seminaren, genutzt werden (z. B. Nachnutzung von bestehenden OERs oder Tutorials).

Für die Nachnutzung bietet es sich an, zunächst nach offenen Repositorien und Infrastrukturen zu suchen, in denen Forschungsdaten der Film- und Medienwissenschaft publiziert und verfügbar gemacht werden, wie etwa: 

* [media/rep/](https://mediarep.org/home)
* [European Film Gateway](https://www.europeanfilmgateway.eu/de)
* [Timeline of Historical Film Colors](https://filmcolors.org/)
* [Cinemetrics](http://cinemetrics.fredericbrodbeck.de/old.html)
* ... und viele mehr

```{admonition} Ressourcenübersicht
:class: hinweis
Im [Kapitel 4.3. Ressourcen und Entscheidungshilfen](../04_einführung_publikation/ressourcen_entscheidungshilfen.md) gehen wir auf konkrete Beispiele im Detail ein – sowohl auf publizierte film- und medienwissenschaftliche Daten aus verschiedenen Projekten und Institutionen als auch auf gängige Repositorien und Datenbanken. Eine ausführliche Übersicht relevanter Repositorien/Projekte/Tools/Infrastrukturen stellen wir dort ebenfalls kommentiert bereit.
```
### Ethische Aspekte und gute wissenschaftliche Praxis

````{margin}
```{admonition} Siehe auch:
:class: seealso
Mehr Informationen zur **Datenzitierung** gibt es in unserer  <a href="https://quadriga-dk.github.io/Tabelle-Fallstudie-1/Markdown/5_1_Datenzitierung.html" class="external-link" target="_blank">QUADRIGA Fallstudie: "Reproduzierbarkeit von Datenanalysen: Ein Fallbeispiel aus dem Nationalen Bildungsbericht"</a>.
```
````
Wichtig ist, die Nachnutzung transparent zu kommunizieren und ordnungsgemäß zu zitieren, sodass Herkunft, Kontext und Lizenzbedingungen nachvollziehbar bleiben. Nachgenutzte Datensätze sollten also ähnlich wie wissenschaftliche Publikationen behandelt werden, d. h. mit vollständiger Quellenangabe, [persistenten Identifikatoren (Kapitel 6.1.)](../06_publikation_repositorien/versionierung_lizenzierung.md) (z. B. DOI falls vorhanden) und Verweis auf [Lizenzbedingungen (Kapitel 6.1.)](../06_publikation_repositorien/versionierung_lizenzierung.md).

```{admonition} Was ist eine DOI?
:class: hinweis
Die Abkürzung DOI steht für **D**igital **O**bject **I**dentifier und ist ein eindeutiger und permanenter Identifikator für digitale Objekte wie beispielsweise wissenschaftliche Aufsätze, Publikationen, Forschungsdaten oder Videos. Ähnlich wie eine ISBN-Nummer dienen DOI’s dazu, Objekte im Internet dauerhaft auffindbar und zitierbar zu machen. Mehr Infos zum DOI gibt es auch im Kapitel [Versionierung, Lizenzierung, Zitierfähigkeit (Kapitel 6.1.)](../06_publikation_repositorien/versionierung_lizenzierung.md).
```
Wie bei anderen Datentypen gilt auch hier: Nachgenutzte Daten sind nie **neutral** oder **objektiv**. Sie sind Ergebnis von Auswahlprozessen, institutionellen Logiken und Strukturen sowie technologischen Bedingungen. Dies betrifft sowohl die Auswahl der erfassten Gegenstände/Filme (gibt es bevorzugte Archivbestände? Ist der untersuchte Filmkorpus westlich geprägt?) als auch die technischen Formate oder Klassifikationssysteme, die bestimmte Formen der Repräsentation bevorzugen und andere ausschließen können {cite}`drucker_digital_humanities_2021,dang_forschungsdatenmanagement_2020`.

Neben der Betrachtung der Relevanz und des Umgangs mit nachgenutztem Datenmaterial richtet sich der Fokus im nächsten Abschnitt auf das Forschungsdatenmanagement selbst.

## Literatur

```{bibliography}
:filter: docname in docnames
```

