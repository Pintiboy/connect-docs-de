---
description: Lesen und schreiben von Rechnungen.
---

# Rechnungen

## Übersicht

* **Intervall**: Täglich / Echtzeit (via Webhook)
* **Richtung**: ERP ↔ Partnersystem
* **Entitäten**:
  * Rechnungen
  * Sachkonten

## Beschreibung

Partnersysteme können mit diesem Use Case Rechnungen im ERP System erstellen. Diese Rechnungen müssen vorher synchronisierte [Kreditoren](kreditoren.md) enthalten (entsprechend ist der [Kreditoren Use Case](kreditoren.md) eine Voraussetzung für diesen Use Case) und können basierend auf einem [Auftrag](auftrage.md) erstellt werden.

Um die korrekten Sachkonten in Rechnungen zu verwenden, können Sachkonten vom ERP zum Partnersystem synchronisiert werden.

Zusätzlich können Rechnungs-Dateien mit Hilfe des [Protokolle Use Cases](../crm/protokolle-dokumente-upload.md) zum ERP hochgeladen werden.

Rechnungen können zudem vom ERP in das Partnersystem synchronisiert werden.
