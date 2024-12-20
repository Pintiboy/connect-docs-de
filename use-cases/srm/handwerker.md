---
description: >-
  Übermittlung von Handwerker, welche für bestimmte Dienstleistungen beauftragt
  werden können.
---

# Handwerker

## Übersicht

* **Intervall**: Täglich
* **Richtung**: ERP → Partnersystem
* **Entitäten**:
  * Handwerker

## Beschreibung

Um im Partnersystem eine Liste aller Handwerker, mit ihrem spezifischen Gewerbe (d.h. welche Art von Handwerker sie sind, z.B. Elektriker, Gärtner, etc.) und Verbindung/Verknüpfung zu einem bestimmten Gebäude (z.B. wenn es einen Hausmeister für eine bestimmtes Gebäude gibt), Wirtschafsteinheit, oder ohne Verbindung, anzuzeigen werden die entsprechenden Handwerker Daten übertragen

Dies kann im Partnersystem genutzt werden, um z.B. den richtigen Handwerker für eine Reparatur zu finden und dann ggf. darauf aufbauend einen [Auftrag](auftrage.md) oder eine [Rechnung](rechnungen.md) zu erstellen (die mit den entsprechenden Use Cases mit dem ERP synchronisiert werden).

{% hint style="info" %}
* Handwerker sind in einigen ERPs eine Art von Kreditor. Der Use Case [Kreditoren](kreditoren.md) deckt alle Kreditoren ab, zu denen auch einige Handwerker gehören können.
* Handwerker sind in einigen ERPs eine Art von Kontakt und sind daher NICHT mit bestimmten Gebäuden oder Wirtschaftseinheiten verbunden.
{% endhint %}
