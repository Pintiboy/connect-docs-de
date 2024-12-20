---
description: >-
  Lesen und Schreiben von Schadensmeldungen, die im Rahmen des Anwendungsfalls
  Aufträge weiterverarbeitet werden können.
---

# Schadensmeldungen

## Übersicht

* **Intervall**: Täglich / Echtzeit (via Webhook)
* **Richtung**: ERP ↔ Partnersystem
* **Entitäten**:
  * Schadensmeldungen
  * Schadensmeldungs-Schadenscodes

## Beschreibung

Dieser Use Case wird benötigt, wenn das Partnersystem eine Schadensmeldung im ERP-System anlegen soll, da diese von einem Mieter innerhalb der Partnerlösung angelegt wurde.

Je nach Partnersystem werden die Schadensmeldungs-Schadenscodes vorher mit dem Partnersystem synchronisieren, damit sie dieselben Schadensmeldungs-Kategorien anzeigen, die auch im ERP vorhanden sind.

Schadensmeldungen können als [Auftrag](auftrage.md) weiterverarbeitet werden. Dies ist auch der Hauptunterschied zu einem [Ticket](../crm/tickets.md), da diese nicht in einem Auftrag referenziert werden können.

Die ERP-Schadensmeldungs-ID wird in das Partnersystem zurückgeschrieben, damit sie in Zukunft wieder verwendet werden kann.

Schadensmeldungen können zudem vom ERP in das Partnersystem synchronisiert werden.
