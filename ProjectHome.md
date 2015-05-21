# GTFS to GOODRELATIONS #

## Ziel und Nutzen ##

Da es im World Wide Web ein reichhaltiges Angebot an Suchmaschinen zum Vergleich von Flugangeboten und Bahnverbindungen gibt, stellt sich die Frage, warum man nicht auch die Angebote verschiedener öffentlicher Transportdienstleister mit Bus-, Tram- oder Bootsverbindungen untereinander vergleichbar machen kann?
Gtfs2gr konvertiert also unter Verwendung der Schemata GoodRelations und Tickets Ontology vorhandene GTFS-Feeds und erzeugt daraus Graphen mit allen relevanten Verbindungs- und Preisinformationen. Diese können dann als Metadaten auf Webseiten hinterlegt werden und ermöglichen so Vergleiche und Verknüpfungen der Angebote verschiedener Transportdienstleister.

## Ausführen des Konverters ##

Unter Downloads kann der gtfs2gr-Konverter heruntergeladen werden.
Der entpackte Ordner beinhaltet die gtfs2gr-Konverterdateien und zwei GTFS-Beispielfeeds.

Zum Ausführen des Konverters, in der Datei 'main.py' den Pfad des zu konvertierenden GTFS-Feeds eintragen und die Datei ausführen.

Der erzeugte Graph wird als 'Output.txt' in den gtfs2gr-Ordner gespeichert gespeichert.