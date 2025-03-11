---
description: Synchronisierung von leerstehenden Einheiten aus dem ERP in das Partnersystem
---

# Leerstände

## Übersicht

* **Interval**: Maximal Stündlich / Echtzeit (via Webhook)
* **Richtung**: ERP → Partnersystem
* **Entitäten**:
  * [Leerstände](../../entitaeten/leerstaende.md)

## Wie aktiviere ich die Übertragung von Leerständen an meine Partnerlösung?

### Yuneo & Sigma

Damit Leerstände aus dem ERP an Ihre Partnerlösung übermittelt werden, muss ein Job im ERP eingerichtet werden. Alle wichtigen Informationen zur Übertragung finden Sie im Bereich „Helpdesk“ in Yuneo. Dort erfahren Sie Schritt für Schritt, wie Sie Leerstände in Yuneo pflegen, zur Vermarktung freigeben und mit ansprechenden Multimediadaten wie Bildern ergänzen.

Sollten Sie Fragen haben, die im Helpdesk nicht beantwortet werden, wenden Sie sich bitte an Ihren ERP-Berater. In Wodis Sigma gibt es leider keinen Helpdesk – hier müssen Sie sich direkt an Ihren ERP-Berater wenden.

### GAP, UTS KARTHAGO & RELion

Leerstände müssen im ERP freigegeben werden, damit Aareon Connect diese abrufen kann. Ihr ERP Berater zeigt Ihnen wie es funktioniert.

## Beschreibung

Die Synchronisation von Leerständen ermöglicht es Ihnen, **Daten über freie Verwaltungseinheiten zu übertragen**, die z.B. in einem System zur Verwaltung von Leerständen und Interessenten ausgeschrieben werden können.

Die Übertragung der Leerstände basiert bei allen ERPs und Partner Lösungen auf dem [OpenImmo 1.2.7b Format](http://www.openimmo.de/go.php/p/24/download.htm).

{% hint style="info" %}
Bei den Wodis ERPs wird der Interval über das ERP gesteuert ([mehr Details](../../erps/wodis-yuneo.md#leerstande-und-interessenten)).
{% endhint %}
