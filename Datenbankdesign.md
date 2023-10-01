# Datenbanksysteme

Einteilung:
- Hierarchische DBS
- Netzwerk DBS
- Relationale DBS
- Objektorientierte DBS
- Objektrelationale DBS

## Drei-Ebenen-Architektur

Weiter Infos unter:<br>
[https://luo-darmstadt.de/wiki2/doku.php?id=db:datenbanksysteme](https://luo-darmstadt.de/wiki2/doku.php?id=db:datenbanksysteme)

## Datenbankentwurf

[https://info-wsf.de/datenbankentwurf/](https://info-wsf.de/datenbankentwurf/)

![dbs02.png](pic/dbs01.png)

Die 4 Phasen eines Datenbankentwurfs:
- In der **externen Phase** findet eine Zweckbestimmung statt -> Kundenwunsch
- In der **konzeptionellen Phase** erfolgt die formale und strukturierte Beschreibung aller relevanten Objekte und deren Beziehungen untereinander -> **ER-Modell**
- Dieses semantische Modell wird in der **logischen Phase** in ein Relationenmodell (auch **relationales Datenbankmodell**) umgesetzt.
- Erst in der **physischen Phase** wird die Datenbankstruktur mit einem DBMS modelliert.

![dbs02.png](pic/dbs02.png)

### Externe Phase

[https://info-wsf.de/informationsstruktur-ermitteln-externe-phase/](https://info-wsf.de/informationsstruktur-ermitteln-externe-phase/)

- **Top-Down** versus **Bottom-Up**-Ansatz
- Ermittlung aufgrund von Realitätsbeobachtungen Erzeugung eines Ausschnitts der realen Welt -> **Miniwelt**
  
  Beispielsweise ist die Schule ein Teil der realen Welt. Unter dem Blickwinkel der Verwaltung von Schülerdaten würde unsere Miniwelt aus den Objekten Schüler, Lehrer, Bücher, Kurse, Noten und deren Beziehungen zueinander bestehen; andere Objekte der Schule, wie Gebäudedaten, Reinigungskosten usw. würden ausgeklammert. Wir bilden deshalb im Hinblick auf die logische Gesamtsicht ein Modell der Miniwelt.
- Ermittlung aufgrund von Benutzersichtanalysen<br>
  Benutzersichten stellen zum Beispiel Formulare und Berichte dar.
- Ermittlung aufgrund von Datenbestandsanalysen<br>
  Dieses Verfahren ermöglicht die Integration existierender Datenbestände in ein neues Datenmodell -> **Migration**
- Geschäftsregeln<br>
  Feststellungen über die Objekte der Miniwelt.

### Konzeptionelle Phase
Wie im Datenbankentwurf ausgeführt, ist es zunächst sinnvoll, ein konzeptionelles Modell des gegebenen Problems zu erstellen.

Dabei lassen sich drei Abstraktionsmechanismen unterscheiden:
- **Klassifikation**
- **Aggregation**
- **Generalisierung oder Spezialisierung**

Um die Modellierung der Realität systematischer gestalten zu können, gibt es verschiedene Standardstrategien. Eine der bekanntesten ist das so genannte Entity-Relationship-Modell (ER-Modell). Neben dem ER-Modell gibt es weitere Datenbankmodelle, z.B. das Hierarchische Modell (HM), das Netzwerkmodell (NWM), das Relationenmodell (RM), das SQL-Datenmodell (SQL) oder das Normalformmodell (NFM).

Abstraktionskonzepte:<br>
Bei der Erstellung eines Datenmodells werden die Objekte und deren Eigenschaften untersucht. Es werden zuerst alle Daten (Objekte) gesammelt. In einem Prozess der Abstraktion werden dann gleichartige Mengen von Objekten zusammengefasst und auf relevante Eigenschaften untersucht. In der Informatik existieren bestimmte Konzepte, nach denen dieser Abstraktionsprozess erfolgt.

#### Klassifikation

Gleichartige Dinge (Objekte) mit gemeinsamen Eigenschaften werden zu Klassen zusammengefasst.

#### Aggregation







