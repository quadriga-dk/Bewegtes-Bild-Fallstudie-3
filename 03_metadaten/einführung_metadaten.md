# Einführung Metadaten

```{figure} ../assets/03_metadaten/abb_k03_metadata.png
---
align: left
width: 100%
name: metadata
---
Metadata, © Markus Winkler via <a href="https://unsplash.com/de/fotos/ein-holzklotz-mit-der-aufschrift-metadaten-der-auf-einem-tisch-liegt-9DZsVF-qLaY" class="external-link" target="_blank">Unsplash</a>
```
Metadaten sind Daten über Daten. Oder wie Johanna Drucker es treffend formuliert: "Think of metadata as the information about a resource or digital asset" {cite}`Drucker_2021`. Die Bandbreite der Erscheinungsformen von Metadaten reicht von sehr einfachen Beschreibungen, wie etwa den grundlegenden "Get Info"-Angaben zu einem digitalen Objekt, bis hin zu hochkomplexen Metadatenstrukturen mit mehreren Ebenen, Feldern und Hierarchien, wie sie insbesondere in Museen, kulturellen Einrichtungen und Archiven zur Erschließung und Verwaltung von Beständen genutzt werden {cite}`Drucker_2021`.

```{image} ../assets/03_metadaten/abb_k03_bandbreite_metadaten.png
---
align: center
width: 70%
name: bandbreite-metadaten
---
```
<br>

Als Bestandteil von Dateien und Dokumenten geben Metadaten im Kern zusätzliche, strukturierte Informationen an, die den eigentlichen (Forschungs-)Daten, Ressourcen oder Objekten, die sie beschreiben, beigefügt werden {cite}`Drucker_2021,FUBerlin_oJ`. Häufig stehen die Metadaten aber auch als Platzhalter für das Objekt selbst, wie es beispielsweise in Bibliothekskatalogen der Fall ist. Hier wird das ursprüngliche Objekt (z. B. ein Buch oder Film) über Metadaten definiert und identifiziert, um Materialien zu lokalisieren und Informationen einzugrenzen. Auf diese Weise ermöglichen Metadaten die Beschreibung, Identifizierung und Klassifizierung von (digitalen) Objekten und kulturellen Artefakten.

```{figure} ../assets/03_metadaten/abb_k03_kinemathek_katalog.png
---
align: center
width: 80%
name: kinemathek-katalog
---
Ergebnisansicht eines Bestandeintrags im Katalog der <a href="https://deutsche-kinemathek.bsz-bw.de/cgi-bin/koha/opac-detail.pl?biblionumber=21039" class="external-link" target="_blank">Deutschen Kinemathek Bibliothek</a>
```
Für die Publikation von Forschungsdaten sind Metadaten unerlässlich, da erst durch die ergänzenden Informationen Daten zuverlässig auffindbar, eindeutig identifizierbar und damit zitierfähig werden. Die zentrale Bedeutung von Metadaten in der digitalen Forschungspraxis hebt auch Drucker hervor: 
> "Metadata is an essential aspect of any digital scholarship or research. Data have to be described and identified in order to be useful." {cite}`Drucker_2021`

Die Charakterisierung von Daten über Metadaten ermöglicht es Forschenden somit, Daten in ihre jeweiligen Kontexte einzuordnen, ihre Herkunft und Struktur nachzuvollziehen und ihre Qualität zu bewerten {cite}`Dierkes_2021`.

## Arten von Metadaten

Es gibt verschiedene Typen von Metadaten, die hinsichtlich ihrer Art und Funktion unterschieden werden (vgl. hierzu auch {cite:alp}`ForschungsdatenInfo_2026,Riley_2017`):
<style>
.table-clean {
  border-collapse: collapse;
  width: 100%;
  font-size: 15px;
}
.table-clean th {
  text-align: left;
  padding: 6px 6px;
  border-bottom: 1px solid #ccc;
  font-weight: bold;
}
.table-clean td {
  padding: 6px 6px;
  border-bottom: 1px solid #eee;
  vertical-align: top;
}
</style>

<table class="table-clean">
  <tr>
    <th>Metadatentyp</th>
    <th>Eigenschaften und Funktionen</th>
    <th>Beispiele</th>
  </tr>

  <tr>
    <td><strong>Deskriptive (inhaltliche) bzw. bibliographische Metadaten</strong></td>
    <td>Helfen beim Auffinden oder Verstehen einer Ressource und bieten inhaltliche Eingrenzung </td>
    <td>Titel, Autor, Beschreibung, Keywords, Publikationsdatum uvm. </td>
  </tr>

  <tr>
    <td><strong>Administrative Metadaten</strong></td>
    <td>
      Helfen bei der Verwaltung und langfristigen Sicherung der Daten<br><br>
      Unterarten:
      <ul>
        <li>Technische Metadaten</li>
        <li>Metadaten zur Erhaltung</li>
        <li>Rechtliche Metadaten</li>
      </ul>
    </td>
    <td>Dateityp und -größe, Speicherort, Erstellungsdatum, Provenance, Zugriffsrechte, Lizenzen uvm.</td>
  </tr>

  <tr>
    <td><strong>Strukturelle Metadaten</strong></td>
    <td>Beschreiben die Anordnung  und Hierarchie eines Objekts oder einer Sammlung, d. h. die Beziehung der einzelnen Teile zueinander </td>
    <td>Kapitelstruktur eines Buchs, sequentielle Abfolge eines Films, Verlinkungsstrukturen einer Website, Codelisten uvm.</td>
  </tr>

  <tr>
    <td><strong>Prozessmetadaten</strong></td>
    <td>Dokumentieren die Schritte und Methoden, die zur Entstehung und Verwendung von Daten angewendet werden</td>
    <td>Verarbeitungsschritte, Tools, Transformationen, Workflows, Versionsverlauf uvm.</td>
  </tr>
</table>
<br>

Nicht immer sind die einzelnen Metadaten-Kategorien klar voneinander zu trennen. So kann es beispielsweise Überlappungen zwischen Prozessmetadaten und administrativen Metadaten geben, wenn es um technische Beschreibungen wie Dateiformat, Erstellungsdatum oder Migration geht. Nichtsdestotrotz ist eine grundlegende Charakterisierung der Funktionen und Eigenschaften verschiedener Metadatentypen im Forschungsprozess sehr hilfreich.

(markup-sprachen)=
## Exkurs: Markup-Sprachen

Metadaten liegen oft in maschinenlesbarer Form vor – in sogenannten Markup-Sprachen. Dies unterstützt die Interoperabilität der Daten hinsichtlich Weiterverwendung und Austausch. 

```{admonition} Was sind Markup-Sprachen?
:class: hinweis
Markup-Sprachen (dt. Auszeichnungssprache) sind maschinenlesbare Sprachen. Sie strukturieren und formatieren Texte und Dateien, indem sie ihnen Eigenschaften - sogenannte `tags` - hinzufügen. Die bekannteste Markup-Sprache ist `html` {cite}`Wikipedia_Auszeichnungssprache_2026`.
```
Am häufigsten wird dabei die Markup-Sprache `xml` verwendet. Metadaten liegen dann als Datensatz in einem `xml`-Dokument vor.

```{figure} ../assets/03_metadaten/abb_k03_xml_beispiel.png
---
align: center
width: 90%
name: xml-beispiel
---
`xml`-Beispiel, © <a href="https://www.niso.org/" class="external-link" target="_blank">NISO</a> CC BY-NC 4.0 
```

```{admonition} Wie funktioniert XML?
:class: hinweis, dropdown
`xml` nutzt definierte Elemente bzw. Tags, um anzugeben, welche Bedeutung den jeweils enthaltenen Werten zukommt. Elemente können auch andere Elemente enthalten. Ein `xml`-Dokument ist ähnlich aufgebaut wie eine Baumstruktur, beginnend mit einem Stammelement {cite}`Riley_2017`.
```
In den Digital Humanities hat sich die auf `xml` basierte Markup-Sprache `tei` als gängiger Standard etabliert. `tei` wurde gezielt an die Bedürfnisse geisteswissenschaftlicher Forschung angepasst.

```{admonition} Mehr Informationen zu XML & TEI
:class: seealso
* <a href="https://docs.nfdi4culture.de/lido-schulung/modul-xml-grundlagen" class="external-link" target="_blank">NFDI4Culture</a>
* <a href="https://libguides.exeter.ac.uk/digitalhumanities/tei" class="external-link" target="_blank">University of Exeter LibGuides</a>
* <a href="https://programminghistorian.org/en/lessons/encoding-texts-tei-1" class="external-link" target="_blank">Programming Historian</a>
```
Neben solchen spezifischen, auf Markup-Sprachen basierenden Strukturierungen von Metadaten, die in erster Linie für die Auszeichnung von Texten genutzt werden, spielen auch **allgemeine Metadatenstandards** eine wichtige Rolle. Nachfolgend gehen wir auf zwei gängige Standards ein. 

(allgemeine-standards)=
## Allgemeine Metadatenstandards

```{image} ../assets/03_metadaten/abb_k03_metadatenstandard.png
---
align: center
width: 80%
name: metadatenstandard
---
```

````{margin}
```{admonition} Markup-Sprachen/XML
:class: hinweis
Mehr Infos zum Thema `XML` gibt es in {ref}`Kapitel 3.1.<markup-sprachen>`.
```
````
<br>

Das System der Strukturierung von Metadaten wird als **Metadatenstandard** bezeichnet {cite}`Drucker_2021`. Metadatenstandards sind also Klassifizierungssysteme. Häufig liegen diese Standards in `XML` vor und legen bereits eine Struktur fest, wobei der Einsatz von kontrolliertem Vokabular bei der Standardisierung der Inhalte hilft (z. B. <a href="https://www.getty.edu/research/tools/vocabularies/" class="external-link" target="_blank">Getty Thesaurus</a>).

> "Dies reicht von kontrollierten Wortlisten, die fehlerhafte oder unterschiedliche Schreibweisen von Konzepten vereinheitlichen, über Taxonomien und Thesauri, die Über- und Unterbegriffe wie auch Synonyme zu Konzepten enthalten, bis hin zu Ontologien, die Eigenschaften und Relationen zwischen Konzepten modellieren." {cite}`ForschungsdatenInfo_2026`

```{admonition} Was sind Taxonomien und Ontologien?
:class: hinweis, dropdown
Taxonomien sind Benennungssysteme, bestehend aus kontrolliertem Vokabular, um Dinge und Objekte zu bezeichnen. Ontologien sind Wissensmodelle, die Informationen als relationale Strukturen organisieren und Konzepte systematisieren {cite}`Drucker_2021`.
```
Es gibt eine Vielzahl von fächerübergreifenden, generischen Metadatenstandards. Zwei der bekanntesten stellen wir kurz vor. 

(dublin-core-header)=
### Dublin Core

Ein weit verbreiteter, generischer Standard zur Beschreibung von Dokumenten und anderen Objekten ist der sogenannte <a href="https://www.dublincore.org/" class="external-link" target="_blank">Dublin Core</a>. Er besteht aus einem Set aus 15 allgemeinen, weit verbreiteten <a href="https://www.dublincore.org/specifications/dublin-core/usageguide/elements/" class="external-link" target="_blank">Elementen </a> (siehe auch <a href="https://www.ietf.org/rfc/rfc2413.txt" class="external-link" target="_blank">hier</a>), darunter beispielsweise `title`, `creator`, `subject` oder `description`, und wird vielseitig für verschiedenste Ressourcen eingesetzt  – von digitalen Objekten in Repositorien über Webseiten bis hin zu Bibliotheksbeständen {cite}`Dierkes_2021`.

```{figure} ../assets/03_metadaten/abb_k03_dublin_core.png
---
align: center
width: 75%
name: dublin-core
---
Dublin Core und die 15 Elemente 
```
#### Die 15 Elemente des DC und ihre Beschreibungen
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
    <th>Element</th>
    <th>Beschreibung</th>
  </tr>
  <tr>
    <td><strong>dc:title</strong></td>
    <td>Titel der Ressource (Name, Bezeichnung)</td>
  </tr>
  <tr>
    <td><strong>dc:creator</strong></td>
    <td>Person oder Organisation, die die Ressource geschaffen hat</td>
  </tr>
  <tr>
    <td><strong>dc:subject</strong></td>
    <td>Themen, Schlagworte oder Klassifikationen</td>
  </tr>
  <tr>
    <td><strong>dc:description</strong></td>
    <td>Beschreibung, Zusammenfassung oder Abstract der Ressource</td>
  </tr>
  <tr>
    <td><strong>dc:publisher</strong></td>
    <td>Herausgebende Institution, die die Ressource veröffentlicht</td>
  </tr>
  <tr>
    <td><strong>dc:contributor</strong></td>
    <td>Weitere Personen oder Organisationen, die zur Ressource beigetragen haben</td>
  </tr>
  <tr>
    <td><strong>dc:date</strong></td>
    <td>Relevantes Datum (z.&nbsp;B. Erstellung, Veröffentlichung)</td>
  </tr>
  <tr>
    <td><strong>dc:type</strong></td>
    <td>Art bzw. Typ der Ressource (z. B. Text, Bild, Dataset)</td>
  </tr>
  <tr>
    <td><strong>dc:format</strong></td>
    <td>Format/Medium der Ressource (z. B. <code>pdf</code>, <code>png</code>, audio/mpeg, <code>txt</code>/<code>xml</code>)</td>
  </tr>
  <tr>
    <td><strong>dc:identifier</strong></td>
    <td>Eindeutige Kennung/Identifikator der Ressource (z. B. DOI, URN, ISBN, URL)</td>
  </tr>
  <tr>
    <td><strong>dc:source</strong></td>
    <td>Ursprungsquelle, aus der die Ressource hervorgeht oder abgeleitet ist</td>
  </tr>
  <tr>
    <td><strong>dc:language</strong></td>
    <td>Sprache der Ressource (z. B. ISO-639-Code)</td>
  </tr>
  <tr>
    <td><strong>dc:relation</strong></td>
    <td>Beziehungen zu anderen Ressourcen (z. B. Teil-von, Version, Referenz)</td>
  </tr>
  <tr>
    <td><strong>dc:coverage</strong></td>
    <td>Räumliche oder zeitliche Abdeckung (Ort, Region, Zeitraum)</td>
  </tr>
  <tr>
    <td><strong>dc:rights</strong></td>
    <td>Rechte, Lizenzen und Nutzungsbedingungen der Ressource</td>
  </tr>
</table>

#### Vor- und Nachteile des DC-Metadatenschemas

✅ **Vorteile**
* Weit verbreitet und international genutzt
* Disziplinübergreifend
* Einfacher Einstieg und geringe Komplexität
* Interoperabel

❌ **Nachteile**
* Eher ungeeignet für komplexere Forschungs- oder Fachdaten 
* Keine spezifische Struktur für für Versionierung oder Zitation von Forschungsdaten
* Uneinheitliche Nutzungsmöglichkeiten

(data-cite-header)=
### DataCite 

Das <a href="https://schema.datacite.org/" class="external-link" target="_blank">DataCite</a> Schema ist eine strukturierte Liste bestehend aus Kern-Metadaten und ihren Eigenschaften. Es wird insbesondere für die bibliographische Beschreibung von Forschungsdaten, für Publikation, Zitation sowie die Registrierung von DOIs genutzt. Bestimmte Elemente, wie z. B. `Autor` oder `Titel`, sind verpflichtende Bestandteile, andere Elemente, wie z. B. `Fachbereich` oder `Beschreibung`, werden empfohlen oder sind optional. Das Metadatenschema sowie praxisnahe <a href="https://schema.datacite.org/meta/kernel-4.6/" class="external-link" target="_blank">Anwendungsbeispiele </a> werden in `xml` und `json` zur Verfügung gestellt {cite}`DataCite_2024`. 
Ein DataCite <a href="https://dhvlab.gwi.uni-muenchen.de/datacite-generator/" class="external-link" target="_blank">Metadatengenerator </a> (aktuell für die Schema Version 4.6.) der Ludwig-Maximilians-Universität München generiert durch Eingabe der Metadatenfelder automatisch ein DataCite-`xml`-Schema. Dieses kann heruntergeladen und in einem Repositorium der Wahl den Forschungsdaten beigefügt werden. Mehr Informationen zur Anwendung gibt es auf der 
<a href="https://github.com/UB-LMU/datacite-metadata-generator" class="external-link" target="_blank">GitHub-Page</a>.

```{figure} ../assets/03_metadaten/abb_k03_data_cite.png
---
align: center
width: 85%
name: data-cite
---
Elemente des DataCite Schemas - *notwendig* (links) & *empfohlen* (rechts)
```
#### Vor- und Nachteile des DataCite-Metadatenschemas

✅ **Vorteile**
* Enge Verknüpfung mit DOIs
* Zitierbare Referenzierung von Daten in Publikationen
* International etablierter Standard in Forschungsdateninfrastrukturen
* Interoperabel

❌ **Nachteile**
* Komplexer und voraussetzungsreich
* Weniger geeignet als universeller Minimalstandard
* Fokus liegt auf Zitation und Publikation, weniger auf inhaltliche Beschreibungen

Beide Metadatenstandards sind auch in den Digital Humanities etabliert und bieten einen guten Einstieg. Welcher am Ende für das eigene Projekt genutzt werden soll, hängt von verschiedenen Variablen der jeweiligen Datensätze ab. Für eigene Projekte ist es daher ratsam, sich frühzeitig über geeignete Metadatenschemata zu informieren. Der folgende Fragenkatalog soll dabei helfen, eine passende Auswahl zu treffen.

## Praxisnaher Fragenkatalog für die Auswahl des Metadatenschemas

<div style="
  border: 1px solid #E5E5E5;
  padding: 1.4rem 1.6rem;
  margin: 2rem 0;
  border-radius: 6px;
">

<details style="margin-bottom:1rem;">
  <summary style="font-weight:600; cursor:pointer;">
    1. Umfang und Komplexität der Daten
  </summary>
  <ul style="margin-top:0.6rem;">
    <li>Handelt es sich um komplexe oder überschaubare Daten?</li>
    <li>Gibt es verschiedene Datentypen (z. B. Texte, Audio, Video, Bilder) oder ist der Datenbestand homogen?</li>
  </ul>
</details>

<details style="margin-bottom:1rem;">
  <summary style="font-weight:600; cursor:pointer;">
    2. Inhaltliche Aspekte
  </summary>
  <ul style="margin-top:0.6rem;">
    <li>Welche Bestandteile der Datensätze sollen in den Metadatendokumentationen beschrieben werden (z. B. Inhalt, Struktur, Entstehungskontext, Methoden, Rechte)?</li>
    <li>Werden grundlegende bibliographische Angaben benötigt oder fachspezifische?</li>
  </ul>
</details>

<details style="margin-bottom:1rem;">
  <summary style="font-weight:600; cursor:pointer;">
    3. Publikation und Zitation
  </summary>
  <ul style="margin-top:0.6rem;">
    <li>Soll das Schema insbesondere für die Publikation und Zitation genutzt werden (DOIs)?</li>
    <li>Sollen die Forschungsdaten langfristig referenzierbar sein?</li>
  </ul>
</details>

<details style="margin-bottom:1rem;">
  <summary style="font-weight:600; cursor:pointer;">
    4. Ressourcen und Kompetenzniveau
  </summary>
  <ul style="margin-top:0.6rem;">
    <li>Welche zeitlichen und technischen Ressourcen bzw. Kapazitäten gibt es im Projekt, um sich ggf. auch in komplexere Schemata einzuarbeiten?</li>
    <li>Stehen Personen mit Vorwissen zu Metadatenstandards oder technischen Formaten (z. B. <code>xml</code>, <code>tei</code>, <code>rdf</code>) zur Verfügung?</li>
  </ul>
</details>

<details>
  <summary style="font-weight:600; cursor:pointer;">
    5. Minimalstandard oder mehr?
  </summary>
  <ul style="margin-top:0.6rem;">
    <li>Reicht für den Zweck des Projektes ein Minimalstandard (z. B. wenige, generische Felder), oder sind detaillierte, fachlich spezialisierte Metadaten erforderlich?</li>
  </ul>
</details>

</div>

Allgemeine, generische Schemata sind ein guter Einstieg für Projektanfänge. Häufig decken sie jedoch die Erfordernisse des jeweiligen Fachs nicht genügend ab. In der Praxis werden Metadatenschemata daher konfiguriert oder angepasst, um die Fach- bzw. Projektspezifika zu adressieren {cite}`Drucker_2021`. Daran anknüpfend rückt im nächsten Kapitel die Filmwissenschaft in den Fokus, um fachspezifische Metadatenstandards exemplarisch zu vertiefen.

```{admonition} Weiterführende Links
:class: seealso
* <a href="https://forschungsdaten.info/themen/beschreiben-und-dokumentieren/metadaten-und-metadatenstandards/" class="external-link" target="_blank">forschungsdaten.info</a>
* <a href="https://rdamsc.bath.ac.uk/" class="external-link" target="_blank">Metadata Standards Catalog</a>
* <a href="https://www.fu-berlin.de/sites/forschungsdatenmanagement/in-der-praxis/durchfuehrung/metadaten.html" class="external-link" target="_blank">Metadaten (FU Berlin)</a>
* <a href="https://www.cms.hu-berlin.de/de/dl/dataman/teilen/dokumentation" class="external-link" target="_blank">Dokumentation und Metadaten (HU Berlin)</a>
* <a href="https://www.zedif.uni-jena.de/en/210/metadata-and-metadata-standards" class="external-link" target="_blank">Metadata and Metadata Standards (Friedrich-Schiller-Universität Jena)</a>
```

## Literatur

```{bibliography}
:filter: docname in docnames
```


