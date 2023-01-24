---
Description: So editierst Du eine neue Attraktion.
icon: material/train-car
---

# Attraktionen editieren

Sobald eine Freizeiteinrichtung angelegt wurde, kann man dieser nicht nur [Zonen im Park](./park.md/#park-zonen) zuweisen, sondern auch Attraktionen anlegen und zuweisen.

## Grunddaten

### Name der Attraktion

!!! info ""
     Gebe den offiziellen Namen (in Landesprache) für die Attraktion an.

### Kategorie

!!! info ""
     Wähle die Kategorie [Übersicht](./categories.md) der Attraktion aus. Zur einfacheren Übersicht haben wir die Kategorien in dieser Dokumentation extra hinterlegt.

### Status

!!! info ""
     Wir definieren folgenen Status[^1] einer Attraktion:

     | Status|Beschreibung|
     |-----------|--------------|
     | `In Bau`| Wird derzeit gebaut/umgebaut|
     | `Im Betrieb`| Regulärer Betrieb|
     | `Ehemalig`| Attraktion wird nicht mehr betrieben|
     | `Außer Betrieb`| Temporär, für einen längeren Zeitraum außer Betrieb|

### Hersteller

!!! info ""
     Wir führen eine Liste von Herstellern in unserer Datenbank. Zur Sicherung unserer Datenqualität, fügen wir die Namen der Hersteller selbst hinzu. Wähle den Hersteller aus der Liste aus. Die Suche schlägt ab 3 Zeichen entsprechende Namen vor. Der Hersteller der Attraktion ist das Hauptkriterium. Wurde zu einem späteren Zeitpunkt ein weiterer Hersteller einbezogen, kannst Du diesen hinzufügen.

     **Beispiel**:
     
     [Fort Fun - SpeedSnake FREE](https://coaster.cloud/attractions/1a2a0802-speedsnake-free){:target='blank' } (Baujahr 1981) :material-arrow-right-box:{.golden} Hier wurde 2018 der Zug des Herstellers [Vekoma](https://coaster.cloud/manufacturers/3bc7392a-vekoma){:target='blank' } nach 37 Jahren, in 2019 durch einen neuen Zug des Herstellers [SunKid](https://coaster.cloud/manufacturers/41c4f014-sunkid-heege-gmbh){:target='_blank'} ersetzt. Nun sind beide Hersteller hier markiert.

### Parkzone

!!! info ""
     Die Zonen einer Freizeiteinrichtung müssen vorher angelegt sein. Dann kann die Attraktion damit verknüpft werden. Die verknüpften Attraktionen einer gemeinsamen Zone, werden in der Ansicht der Freizeiteinrichtung in einer Übersicht der Parkzonen angezeigt. So gelangt man zügig auf den Filter einer Parkzone.

### Onride Video

!!! info ""
     Es gibt viele schöne Onride Videos zu den Attraktionen auf :simple-youtube:{.red .heartbeat} YouTube. Findest Du den passenden für unsere Plattform? Dann kopiere den Codes des Videos in das Feld. Beispiel: https://www.youtube.com/watch?v={==wNs6oRhObc8==}

### Koordinaten

!!! info ""
     Um die Einrichtung auf unserer Karte darstellen und Entfernungen messen zu können, benötigen wir die Koordinaten. Gib bitte den **Breitengrad** und **Längengrad** als Dezimalwert an. Vergleiche auch gerne diese Funktion mit der [Beschreibung bei einer Freizeiteinrichtung](./park.md#koordinaten).

### Scoring System

!!! info ""
     Wenn die Attraktion ein Scoring System bietet, in dem man sich messen kann, dann hast Du hier die Optionen `Punktezahl` oder `Zeitmessung`. Bei jeder Fahrt die man `countet` wird nun der Score abgefragt und mit archiviert.

## Kurzbeschreibung

!!! info ""
     Hinterlege eine stilvolle kurze Beschreibung der Attraktion. Übernehme bitte keine Wikipedia Texte oder Marketingtexte. Stelle heraus, was sie besonders macht.

## Sicherheitsbestimmungen

!!! info ""
     Eine sehr wichtige Information vor allem für Familien mit Kindern, sind die Sicherheitsbestimmungen auf Attraktionen. Sehr oft stellen sich Eltern die Frage "Welche Achterbahn darf mein Kind fahren?". Mit unserer App und der Sammlung dieser Daten schaffen wir eine hervorragende Übersicht.

     Hinterlege bitte die Daten der Mindestgröße, Mindestalter, Höchstgröße und Höchstalter bei `ohne Begleitung` und auch `mit Begleitung`. Hat die Attraktion keine Sicherheitsbestimmungen, setze den Schalter auf diese Option. Damit ist in der Auswertung klar, dass dies keine Rolle spielt.

## Technische Informationen

!!! info ""
     Einige technische Informationen lassen sich durch Pressemitteilungen, an der Attraktion oder anderen Quellen **verifizieren**. Damit wir uns nicht nur einen Spaß für die Statistik erlauben können, sammeln wir diese Daten. Natürlich ergeben sich damit auch andere Parameter für z.B. `gefahrene Strecke` und ähnliches. Bitte achte darauf dass keine "Fantasie" Daten entstehen oder Vermutungen eingetragen werden!

     Besonders wertvoll sind Informationen zu Länge, Höhe, Höchstgeschwindigkeit und Dauer der Attraktion.

## Zug Informationen

!!! info ""
     Auch zu den Zügen einer Attraktion sammeln wir Informationen. Wie viele Waggons pro Zug, Reihen pro Waggon oder Anzahl der Züge stehen zur Verfügung? Bei Wasserfahrt Attraktionen natürlich die Zahlen für ein Boot. Das [Rückhaltesystem](../faq/restraint.md) und die Sitzart spielen eine weitere Rolle.

## Zusätzliche Informationen

!!! info ""
     Wir sammeln auch Nebeninformationen zu Attraktionen. So können wir in der App gezielt danach filtern und unseren Nutzern eine komfortable App bereitstellen. Wir sammeln hier Daten zur Fläche, Baukosten aber auch zu einfachen Attributen wie vorhandener Pre-Show, Barrierefreiheit, Überdachungsart. Einige Attribute sind besonders interessant für Sonderfunktionen der App. Im Betriebszeitraum setzen wir fest ob eine Attraktion eine klassische "Halloween" Attraktion ist und nur in dieser Zeit nutzbar wäre. Diese bekommt dann eine eigene Funktion in der App.
     Ebenso sind Informationen wichtig wie: Zuschlagspflicht, FastPass, Single Rider, Test Sitz, Baby Switch oder der Rucksack Handhabung.

## Fahrelemente

!!! info ""
     Wir haben mit Beginn der Programmierung unserer App sehr enthusiastisch gedacht, wie toll wäre es auch die Fahrelemente sehr filigran bestimmen zu können. Daraus ist eine sehr umfangreiche Liste an Elemente entstanden. Nach den ersten 2 Jahren der Veröffentlichungen bemerken wir jedoch, dass die Definition dieser Elemente nicht jedem klar ist. Wir lagern daher die [Definition der Fahrelemente](../faq/elements.md) gesondert aus.

## Historie

!!! info ""
     Die Historie einer Attraktion zeigt die Veränderung auf. Hier geht es um die Eröffnung, Umbenennung oder auch Schließung der Attraktion. Aber Achtung vor Diskussionen. Wir haben zwei gute Beispiele, an denen wir begründen warum eine Umbenennung **und** auch die thematische Änderung nicht unbedingt zu einem neuen `count` führen müssen.

     **Beispiel** - [Movie Park Germany - Show: Crazy Cops New York](https://coaster.cloud/de/attractions/8b134039-crazy-cops-new-york-das-chamaleon){:target='_blank'}
    
     Diese Show wechselte in vielen Jahren, einige male den Titel und passte auch die Darbietung von Jahr zu Jahr geringfügig an. Von einer "neuen Show" konnte zunächst jedoch nicht gesprochen werden. Für {==2023==} wurde das Show-Set komplett abgerissen und eine neue Show startet. Das ist ein neuer Datensatz wert, auch wenn sich die Eigenschaften des Spielortes nicht geändert haben.

     **Anderes Beispiel** - [Movie Park Germany - Roxy 4D Theater](https://coaster.cloud/de/attractions/2695adf5-roxy-4d){:target='_blank'}
     
     Das Roxy 4D Kino bietet fortlaufend das gleiche Erlebnis von aufregenden 4D Actionfilmen. Der Spielort und das Konzept ändert sich nicht. Nur der Film selbst, ist für uns kein Anlass einen neuen Datensatz einer Attraktion zu erstellen.

[^1]: Betreiben einer Attraktion: Gilt für diesen Park. Wird die Attraktion z.B. verkauft, ist diese nicht mehr in diesem Park verfügbar. Es gleicht einem Abriss. Die Attraktion wird damit in das Archiv verschoben und ist unter `Ehemalige Attraktionen` noch zu finden. In unser Suche werden die archivierten Ergebniss gegebenenfalls in der Reihenfolge weniger priorisiert.
