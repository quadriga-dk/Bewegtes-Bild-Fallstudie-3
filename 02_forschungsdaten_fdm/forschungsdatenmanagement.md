# Management von Forschungsdaten

Um die Anforderungen guter wissenschaftlicher Praxis zu erfüllen, ist ein "planvoller Umgang" {cite}`Dierkes_2021` mit Forschungsdaten entscheidend. Im Sinne der Projektumsetzung beinhaltet dies ein umfassend dokumentiertes und nachvollziehbares Forschungsdatenmanagement (FDM). Doch was beinhaltet das **FDM**? 
Laut dem RatSWD umfasst das FDM 
> "[...] den gesamten Prozess, den Forschungsdaten in einem Forschungsprojekt durchlaufen – angefangen mit der Planung der Studie, über die Datengewinnung, die Datenaufbereitung und -analyse, die Speicherung der Daten und Metadaten, deren Archivierung und eventuellen Bereitstellung – bis hin zur Wiederverwendung und ggf. Löschung der Daten" {cite}`RatSWD_2023`.

Dieser Prozess – also das Durchlaufen der einzelnen Schritte und Phasen der Forschungsdaten während der Projektumsetzung – wird oft auch als Forschungsdatenlebenszyklus bezeichnet.

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_forschungsdatenlebenszyklus.png
---
align: center
width: 60%
name: forschungsdatenzyklus
---
Forschungsdatenlebenszyklus
```
Dieser Zyklus orientiert sich vorrangig am Management quantitativer Daten. Eine an die jeweilige Disziplin (oder gar an das spezifische Projekt) gerichtete Anpassung dieses Datenlebenszyklus ist jedoch notwendig. Denn Forschungsprozesse sind nicht linear, also keine "Aneinanderreihung von kategorisierbaren Aktivitäten" {cite}`Dierkes_2021`. 

```{admonition} Anpassung des Zyklus-Modells
:class: important
Sophie Einwächter weist darauf hin, dass eine Orientierung des FDMs an diesem Zyklus-Modell auch nicht bei jedem Projekt sinnvoll sein muss; es gibt beispielsweise auch Projekte, die mit der planmäßigen Löschung der Daten enden {cite}`einwaechter_forschungsdaten_2019`. Ebenso muss der Umgang mit personenbezogenen Daten hinsichtlich der Archivierung und Nachnutzung der Daten mitgedacht werden.
```
 Wichtig ist also die kontextbezogene Auslegung und das Miteinbeziehen der projekteigenen Beschaffenheiten der Daten. Grundsätzlich bietet der Zyklus aber eine gute erste Basis für die Planung, da die Phasenhaftigkeit bzw. Prozesshaftigkeit der Arbeitsschritte adressiert wird {cite}`Dierkes_2021`.

(leitlinien-fair)=
 ## Leitlinien und FAIR-Prinzipien

 ````{margin}
 ```{admonition} Siehe auch:
 :class: seealso
Mehr Informationen zu den **FAIR-Prinzipien** gibt es in unserer <a href="https://quadriga-dk.github.io/Tabelle-Fallstudie-1/Markdown/3_1_FairPrinzipien.html" class="external-link" target="_blank">QUADRIGA Fallstudie: "Reproduzierbarkeit von Datenanalysen: Ein Fallbeispiel aus dem Nationalen Bildungsbericht"</a>.
```
````

 Allgemeine Anforderungen und Leitlinien guter wissenschaftlicher Praxis helfen, das FDM zu strukturieren und wesentliche Aspekte zu berücksichtigen. Die Behandlung der Forschungsdaten nach den sogenannten **FAIR-Prinzipien** ist dabei ein zentraler Bestandteil.
 FAIR steht für **F**indable, **A**ccessible, **I**nteroperable und **R**eusable, zusammengefasst heißt das {cite:p}`GOFAIR_oJ`:

 1. **F** = Die Daten sollten auffindbar und identifizierbar sein (DOI, Metadaten)
 2. **A** = Die Daten sollten so offen und zugänglich wie möglich sein (offene Protokolle, APIs, Repositorien)
 3. **I** = Die Daten sollen mit verschiedenen Systemen kompatibel sein 
 4. **R** = Die Daten sollen nachnutzbar und referenzierbar sein (Lizenzen/Verwendungsrechte und Dokumentation) 

 ```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_fair_prinzipien.png
---
align: center
width: 100%
name: fair-prinzipien
---
FAIR-Prinzipien
```
Gleichsam sollten auch immer Validität und Reliabilität der Daten gewährleistet werden {cite}`dang_forschungsdatenmanagement_2020`.

(leitlinien-dfg)=
## DFG-Leitlinien

````{margin}
```{admonition} Hinweis:
:class: hinweis
Die Leitlinien richten sich insbesondere an Antragstellende für Forschungsprojekte.
```
````
Neben der Berücksichtigung der FAIR-Prinzipien hat die DFG disziplinübergreifende [Leitlinien](../assets/02_forschungsdaten_fdm/doc_k02_dfg_leitlinien.pdf) zum Umgang mit Forschungsdaten formuliert. Kernpunkte dieser Empfehlungen sind die langfristige Sicherung und Bereitstellung der Forschungsdaten. Indem die Transparenz und Qualität wissenschaftlicher Arbeit gestärkt werden, können wichtige Anschlussmöglichkeiten (ganz im Sinne des wissenschaftlichen Austauschs und der Nachnutzung) geschaffen werden {cite:p}`DFG_2015`.

Die drei Kernpunkte fassen wir hier kurz zusammen:

1. In der **Projektplanung** sollen frühzeitig Überlegungen dazu festgehalten werden, welche Daten aus dem Forschungsvorhaben resultieren, wie sie generiert und ausgewertet werden, welche Konzepte für die Qualitätssicherung relevant sind, welche Datentypen anfallen, wie die langfristige Sicherung erfolgt und welche Publikationswege in Betracht komme. 
2. Bei der **Bereitstellung** wird angestrebt, die Forschungsdaten zeitnah und in einer nutzbaren Form (als Rohdaten oder bereits strukturiert) zugänglich zu machen und den Zugang auch bei übertragenen Verwertungsrechten (z. B. an Verlage) sicherzustellen.
3. Für die **langfristige Sicherung** sollten klare Archivierungsstrategien formuliert werden, wobei die Daten mindestens zehn Jahre in institutionellen (d. h. hochschuleigene Repositorien wie z. B. das <a href="https://refubium.fu-berlin.de/" class="external-link" target="_blank">Refubium der FU</a>) oder fachbezogenen überregionalen Infrastrukturen aufbewahrt werden sollen (z. B. <a href="https://mediarep.org/home" class="external-link" target="_blank">media/rep/</a>, <a href="https://zenodo.org/" class="external-link" target="_blank">Zenodo</a>, <a href="https://github.com/" class="external-link" target="_blank">GitHub</a>).

```{admonition} Weiterführende Links zum Thema Forschungsdatenmanagement und FAIR-Prinzipien
:class: seealso
**FDM:**
* <a href="https://www.dfg.de/de/grundlagen-themen/grundlagen-und-prinzipien-der-foerderung/forschungsdaten" class="external-link" target="_blank">DFG</a>
* <a href="https://forschungsdaten.info/themen/informieren-und-planen/was-ist-forschungsdatenmanagement/" class="external-link" target="_blank">forschungsdaten.info</a>
* <a href="https://www.cms.hu-berlin.de/de/dl/dataman/support/material" class="external-link" target="_blank">HU Berlin</a>
* <a href="https://www.filmuniversitaet.de/filmuni/universitaetsbibliothek/fachinformation/forschungsdaten" class="external-link" target="_blank">Filmuniversität Babelsberg</a>
* <a href="https://www.fu-berlin.de/sites/forschungsdatenmanagement/glossar/index.html" class="external-link" target="_blank">Glossar der FU Berlin</a>
* <a href="https://www.fu-berlin.de/sites/forschungsdatenmanagement/policy/index.html" class="external-link" target="_blank">Forschungsdatenpolicy der FU Berlin</a>

**FAIR**
* <a href="https://zenodo.org/records/6247015" class="external-link" target="_blank">Mark D. Wilkinson et al.</a>
* <a href="https://forschungsdaten-thueringen.de/fair-assessment-tool/articles/fair-assessment-tool.html" class="external-link" target="_blank">FAIR Assessment Tool TKFDM</a>
* <a href="https://quadriga-dk.github.io/Tabelle-Fallstudie-1/Markdown/3_1_FairPrinzipien.html" class="external-link" target="_blank">QUADRIGA Fallstudie: "Reproduzierbarkeit von Datenanalysen: Ein Fallbeispiel aus dem Nationalen Bildungsbericht"</a>
```

(datenmanagement-plan)=
## Datenmanagementplan

Um einerseits die Organisation des FDMs zu bewerkstelligen und andererseits klare, nachvollziehbare Strukturen zu etablieren, empfiehlt es sich, einen sogenannten **Datenmanagementplan** (kurz: DMP) zu erstellen. In einem DMP können die bisher weitestgehend grob bzw. abstrakt zusammengefassten Phasen des Datenlebenszyklus systematisch dokumentiert und organisiert werden. 
Der DMP muss hierbei als ein "living document", also ein lebendiges Dokument, verstanden werden, denn sowohl die eigentliche Forschung selbst als auch das FDM sind komplex und (besonders bei Langzeitprojekten) hochdynamisch; selten verlaufen diese Prozesse linear {cite}`RatSWD_2023`. 
Im Wesentlichen sind DMPs von Menschen lesbare Dokumente, wobei es mittlerweile auch eine Reihe von Entwicklungen hin zu automatisierten und maschinenlesbaren Formaten gibt. 

### Inhalte eines DMPs

Die konkreten Inhalte eines DMPs sind nicht normiert. Es gibt sowohl eine Reihe institutioneller Handreichungen und Vorlagen als auch digitale Werkzeuge, mit denen DMPs erstellt werden können. Für einen ersten Überblick fassen wir die wichtigsten Inhalte hier kurz zusammen {cite:p}`{vgl. für einen Überblick auch }Dierkes_2021,RatSWD_2023`:

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_dmp.png
---
align: center
width: 65%
name: datenmanagementplan
---
Datenmanagementplan
```

<style>
.table-clean {
    border-collapse: collapse;
    width: 100%;
    font-size: 15px;
}
.table-clean th {
    text-align: left;
    padding: 8px 6px;
    border-bottom: 1px solid #ccc;
    font-weight: bold;
}
.table-clean td {
    padding: 8px 6px;
    border-bottom: 1px solid #eee;
    vertical-align: top;
}
</style>

<table class="table-clean">
  <tr>
    <th>Bereich</th>
    <th>Leitfragen / Beschreibung</th>
  </tr>
  <tr>
    <td><strong>Art der Daten</strong></td>
    <td>Welche Forschungsdaten fallen an (Primär- oder Sekundärdaten, Annotationen, Transkriptionen? Metadaten, Visualisierungen uvm.); werden Daten nachgenutzt? Und wenn ja: Welche Lizenzen und Bedingungen gelten dafür?</td>
  </tr>
  <tr>
    <td><strong>Datengewinnung</strong></td>
    <td>Welche Methoden werden eingesetzt? Gibt es (ggf. rechtliche) Hürden bei der Datengewinnung? Welche Softwareversionen, Tools oder Geräte werden verwendet?</td>
  </tr>
  <tr>
    <td><strong>Datentypen</strong></td>
    <td>Formate, Datenmenge, Dateigrößen; werden offene und nachhaltige Formate verwendet (FAIR-Prinzipien)? Sind Konvertierungen notwendig?</td>
  </tr>
  <tr>
    <td><strong>Speicherung &amp; Speicherlösungen</strong></td>
    <td>Speicherplatz, Datenzugang, Speicherorte und Speicherdauer; gibt es tragbare Speicher? Werden lokale Speicher oder Cloud-Dienste genutzt? Werden Backups angelegt und wenn ja: welche Backup-Strategien werden entwickelt?</td>
  </tr>
  <tr>
    <td><strong>Datensicherheit</strong></td>
    <td>Verschlüsselung von Dateien und Speichersystemen, sichere Passwörter, Festlegung von Speicherfristen und ggf. Löschung nicht mehr benötigter Daten, Zugangsbeschränkungen und -kontrollen, Verteilung von Zugriffsrollen, Einhaltung des Datenschutzes, Speicherung personenbezogener Daten innerhalb der EU</td>
  </tr>
  <tr>
    <td><strong>Qualitätssicherung</strong></td>
    <td>Welche Maßnahmen gibt es, um die Qualitätssicherung der Daten zu gewährleisten? Gibt es Validierungsroutinen?</td>
  </tr>
  <tr>
    <td><strong>Ressourcen</strong></td>
    <td>Bearbeitungsaufwand, Zeitplan, personelle, technische und finanzielle Kapazitäten, ggf. geplante Workshops oder Schulungen für Datenkompetenzen</td>
  </tr>
  <tr>
    <td><strong>Archivierung und Veröffentlichung</strong></td>
    <td>Wo werden die Daten langfristig archiviert? Werden die Daten veröffentlicht? Wenn ja: Wo und wie werden sie veröffentlicht? Welche Lizenzen werden vergeben? Werden die Daten in einem (lokalen) Repositorium abgelegt? Erhalten die Daten einen persistenten Identifier (z. B. DOI)?</td>
  </tr>
  <tr>
    <td><strong>Datenorganisation</strong></td>
    <td>Ordnerstrukturen, Benennungskonventionen für Dateien und Ordner, Versionierung (z. B. Semantic Versioning), Konsistenzregeln</td>
  </tr>
  <tr>
    <td><strong>Nachnutzungsszenarien/Umgang nach Projektende</strong></td>
    <td>Nachvollziehbare Dokumentationen, Datenberichte, Metadaten, Kontextualisierung der Daten, Herkunft und Beschreibung der Daten; sind Daten ausreichend dokumentiert, damit Dritte sie verstehen können?</td>
  </tr>
  <tr>
    <td><strong>Rechtliche Aspekte</strong></td>
    <td>Einhaltung des Datenschutzes, Umgang mit personenbezogenen Daten, Lizenzbedingungen nachgenutzter Daten, Materialrechte (z. B. von Bildern, Videos oder Audiofiles) bzw. urheberrechtliche Aspekte, Einwilligungen für (z. B. für Interviews)</td>
  </tr>
</table>
<br>

Das Erstellen eines DMPs hilft dabei, im Vorfeld systematisch über Erzeugung, Nutzung und Einbindung von Forschungsdaten zu reflektieren. Gleichzeitig wird Transparenz über Datenerzeugung und -verwendung geschaffen – einerseits für die Planung innerhalb des Projekts, andererseits ebenso für die Kommunikation mit der Forschungseinrichtung oder Förderinstitution 
(z. B. <a href="https://www.dfg.de/de" class="external-link" target="_blank">DFG</a> oder <a href="https://www.bmftr.bund.de/DE/Home/home_node.html" class="external-link" target="_blank">BMFTR</a>). 

Um den Einstieg zu erleichtern, hat die HU Berlin hierzu ein kurzes Online-Video erstellt und die wichtigsten Punkte zusammengefasst.

<div style="max-width:500px; margin:2rem 0;">

  <video id="ref_91"
         controls
         preload="none"
         style="width:100%; height:auto;"
         poster="https://rs.cms.hu-berlin.de/dataman/plugins/api_resource/?ref=91&amp;key=3QUcTW8DyUNYbF_08xZQ-Q93zH0IHkE-STHwTP3S32mS2l1ZWuyPviKuHFv4tTHiZtIXZg,,&amp;preview=1&amp;skey=430ebe346ff118895412774462694765">
  </video>

  <div style="margin-top:0.6rem; font-size:0.85rem; text-align:center;">
    <a href="https://rs.cms.hu-berlin.de/dataman/pages/view.php?ref=91#"
       target="_blank" rel="noopener">
       Was sind Datenmanagementpläne?
    </a>
    von Kerstin Helbig et&nbsp;al. (HU Berlin), © CC BY 4.0
  </div>

</div>

Ein Beispiel dafür, wie ein ausgearbeiteter DMP aussehen kann, findet sich im Kapitel [Aufbereitung & Anreicherung filmwissenschaftlicher Daten](../05_aufbereitung_anreicherung/informationen_datenset.md) - exemplarisch dargestellt anhand der Daten des SFB-Teilprojekts.

```{admonition} Weiterführende Links zum Thema Datenmanagementplan, Tools und Vorlagen
:class: seealso
**Institutionelle DMP-Vorlagen** 
* <a href="https://www.fu-berlin.de/sites/forschungsdatenmanagement/materialien/handreichungen/dmp/index.html" class="external-link" target="_blank">FU Berlin</a>
* <a href="https://www.cms.hu-berlin.de/de/dl/dataman/mitdmparbeiten/dmp_erstellen/hinweise" class="external-link" target="_blank">HU Berlin</a>

**DMP-Tools**
* <a href="https://rdmo.aip.de/" class="external-link" target="_blank">RDMO</a>
* <a href="https://www.tu.berlin/ub/szf/tipps-tools/planen/tool-tub-dmp" class="external-link" target="_blank">TUB-DMP</a>
* <a href="https://argos.openaire.eu/home" class="external-link" target="_blank">ARGOS</a>
* <a href="https://ds-wizard.org/" class="external-link" target="_blank">Data Stewardship Wizard</a>

**Weiterführende Informationen**
* <a href="https://forschungsdaten.info/themen/informieren-und-planen/datenmanagementplan/" class="external-link" target="_blank">forschungsdaten.info</a>
* <a href="https://www.tu.berlin/ub/szf/nachrichtendetails/leitfaden-zur-erstellung-eines-datenmanagementplans-verfuegbar" class="external-link" target="_blank">Leitfaden TU Berlin</a>
* <a href="https://libereurope.eu/working-group/research-data-management/plans/" class="external-link" target="_blank">LIBER Research Data Management Working Group</a>
```

## Best Practices in der Filmwissenschaft

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_fair_dfg_dmp.png
---
align: center
width: 80%
name: fair-dfg-dmp
---
Standards des FDMs
```
Die bisher diskutierten Standards des FDMs (FAIR-Prinzipien, DFG-Leitlinien, DMP) sind allgemeingültig und sollten unabhängig von den Anforderungen der jeweiligen Disziplin beachtet und eingehalten werden. Doch wie sieht es mit Standards oder Best Practices in den Film- und Medienwissenschaften aus?

Obwohl digitale Methoden und Arbeitsprozesse schon länger in den Film- und Medienwissenschaften praktiziert werden, mangelt es bisher an Standardisierungen, die die speziellen Bedarfe filmwissenschaftlicher Forschung adressieren {cite}`dang_forschungsdatenmanagement_2020,matuszkiewicz_forschungsdatenmanagement_2022`. Laut Dang sei das Konzept des FDMs für viele Forscher:innen neu und stelle nach wie vor eine Herausforderung dar. Es besteht also die Notwendigkeit, den Begriff der Forschungsdaten und des FDMs auch in den Film- und Medienwissenschaften eingehend zu etablieren und Anforderungen zu formulieren, in denen die spezifischen Erfordernisse des Fachs berücksichtigt werden. Dies betrifft vor allem die Heterogenität der Daten und Datenquellen sowie die Frage des Urheberrechts in Bezug auf Film- und Bildmaterial.
Insbesondere für die Geisteswissenschaften, betont Drucker, sei die Dokumentation der Arbeitsprozesse essentiell; oftmals werden Forschungsdaten wie Film- und Literaturrecherchen (bibliographische Datenbanken), Sequenz- und Einstellungsprotokolle oder kommentierte Screenshots nicht publiziert. Dabei sind solche Arbeits- und Rechercheprozesse nicht unerheblich und können die Nachnutzung der Daten fördern {cite}`drucker_digital_humanities_2021,dang_forschungsdatenmanagement_2020`. 

```{figure} ../assets/02_forschungsdaten_fdm/abb_k02_workprocess.png
---
align: center
width: 80%
name: workprocess
---
Illustrative Visualisierung eines Arbeitsprozesses, © @lucifurification via Unsplash
```
Trotz eines Mangels an etablierten Standards gibt es in jüngster Zeit zahlreiche Bestrebungen, solche zu entwickeln. So arbeitet beispielsweise das Konsortium <a href="https://nfdi4culture.de/index.html" class="external-link" target="_blank">NFDI4Culture</a> – eine Infrastruktur für Forschungsdaten des materiellen und immateriellen Kulturerbes (darunter auch Film- und Medienwissenschaft) – an fachspezifischen Empfehlungen und Handreichungen.

(fiwi-best-practices)=
### 🎞️ Konkrete Best-Practice-Hinweise 

Neben den im Vorfeld thematisierten allgemeinen Standards, haben wir nachfolgend praxisnahe Empfehlungen ergänzt und zusammengefasst:

1. **Daten**: Heterogenität der Daten (z. B. Film- Videodaten, Transkripte, Annotationen, Metadaten, Visualisierungen, kommentierte Screenshots, Shotdetection uvm.) berücksichtigen; erfordert klare Strukturierungen im Vorfeld
2. **Formate**: Interoperable Formate wählen (z. B. `csv`, `json`, `mkv`, `png`); ggf. Digitalisierungs- und Bildqualität prüfen, technische Metadaten festhalten
3. **Rechte & Lizenzen**: Dies betrifft Nutzungsrechte, Lizenzbedingungen, Archivstatus (Fassungen) und Einschränkungen bei Weiterverwendung und Publikation
4. **Nachnutzbarkeit**: Metadaten und Dokumentationen (z. B. `README` oder Protokolle) für jedes Datenobjekt; Entstehung, Auswahl, Bearbeitungsschritte, Annotationsmethoden, Softwareversionen und Analyseverfahren dokumentieren
5. **Infrastruktur**: Regelmäßige Backups (z. B. von Annotationsdateien), früh archivieren und ggf. an Formatmigrationen denken (insbesondere bei softwarespezifischen Annotationsformaten wie `azp` (Advene) oder `eaf` (ELAN)).


## Literatur

```{bibliography}
:filter: docname in docnames
```


