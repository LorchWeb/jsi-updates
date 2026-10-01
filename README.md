# JSI – Joomla JSON-LD Snippet Injector

Ein Systemplugin für Joomla 5 und 6 von Alpenrand Digital Agentur.

JSI ergänzt optionale JSON-LD-Snippets direkt an Joomla-Menüpunkten, einschließlich der Startseite. Ein separates globales Snippet kann in den Plugin-Einstellungen gepflegt werden. Die Speicherung ist unabhängig von Template und Template-Stil.

## Download

[JSI 1.0.2 herunterladen](https://lorchweb.github.io/jsi-updates/plg_system_jsi-1.0.2.zip)

Das ZIP über die Joomla-Erweiterungsverwaltung installieren und **System – JSI JSON-LD Snippet Injector** aktivieren. Jeder Frontend-Menüpunkt erhält einen Reiter **JSON-LD**. Das globale Feld befindet sich in den Plugin-Einstellungen. In die Felder reines JSON ohne umschließende Script-Tags eintragen.

Beide Funktionen sind optional und standardmäßig ausgeschaltet. Den Pflegeort des globalen Snippets entscheidet der Administrator: Wird es bereits über eine andere Erweiterung oder das Template ausgegeben, kann die globale JSI-Ausgabe ausgeschaltet bleiben. JSI verändert fremde Schema-Ausgaben nicht.

## Verhalten

- Eigene JSON-LD-Daten pro Menüpunkt, bei Mehrsprachigkeit entsprechend pro Sprachmenüpunkt.
- Ausgabe des Seitensnippets ausschließlich auf dessen Seitenziel, ohne automatische Vererbung auf Beitragsdetailseiten oder weitere Paginierungsseiten.
- Menü-Aliase verwenden das Zielsnippet. Überschriften, Trennzeichen und externe Links erzeugen keine eigene Seite.
- JSON-Prüfung beim Speichern und HTML-sichere Ausgabe. Keine automatische inhaltliche Schema.org-Prüfung.
- Reguläre Joomla-Berechtigungen und Joomla-Caches; keine eigene Cache-Verwaltung. Nach Änderungen vorhandene Seitencaches leeren.
- Globale JSI-Daten gelten sprachübergreifend. Sprachabhängige Seiteninhalte gehören in die jeweiligen Menüpunkt-Snippets.

## Updates

Ab Version 1.0.1 ist diese Updatequelle registriert:

https://lorchweb.github.io/jsi-updates/plg_system_jsi.xml

Eine ursprüngliche Installation von 1.0.0 benötigt einmalig die manuelle Installation von 1.0.1. Danach werden spätere Versionen über die Joomla-Erweiterungsaktualisierung angeboten.

## Voraussetzungen und Lizenz

Joomla 5 oder 6; mindestens PHP 8.1 und zusätzlich die Systemanforderungen der eingesetzten Joomla-Version. Laufzeittests der ersten Version wurden auf Joomla 5.4.9 und Joomla 6.1.3 durchgeführt.

Lizenz: GNU GPL Version 2 oder neuer. Das Installationspaket enthält den PHP-Quellcode des Plugins. Dieses Repository dient der öffentlichen Verteilung von Paketen und Update-Metadaten.

[Alpenrand Digital Agentur](https://alpenrand-digital.de)
