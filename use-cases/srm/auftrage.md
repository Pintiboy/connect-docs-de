---
description: Lesen und schreiben von Aufträgen.
---

# Aufträge

## Übersicht

* **Intervall**: Täglich / Echtzeit (via Webhook)
* **Richtung**: ERP ↔ Partnersystem
* **Entitäten**:
  * Aufträge

## Beschreibung

Partnersysteme können mit diesem Use Case Aufträge im ERP System erstellen. Diese Aufträge müssen vorher synchronisierte [Kreditoren](kreditoren.md) enthalten (entsprechend ist der [Kreditoren Use Case](kreditoren.md) eine Voraussetzung für diesen Use Case) und können basierend auf einer [Schadensmeldung](schadensmeldungen.md) erstellt werden.

Zusätzlich können Auftrags-Dateien mit Hilfe des [Protokolle Use Cases](../crm/protokolle-dokumente-upload.md) zum ERP hochgeladen werden.

Aufträge können zudem vom ERP in das Partnersystem synchronisiert werden.
