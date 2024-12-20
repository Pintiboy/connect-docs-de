---
description: Übermittlung von Nutzerdaten und Kategorien von den Wärmemessdienstleistern.
---

# Verbrauchs-Meta Daten

## Übersicht

* **Intervall**: Täglich
* **Richtung**: ERP → Partnersystem
* **Entitäten**:
  * Verbrauchs-Meta Daten

## Beschreibung

Dieser Use Case ist relevant, wenn das Partnersystem Verbrauchsdaten für die Mieter abrufen möchte. Dazu benötigt das Partnersystem Verbrauchs-Meta Daten aus dem ERP-System, so dass der Partner die Daten für jeden Mieter vom richtigen Wärmemessdienst anfordern kann, und zwar unter Verwendung der Mieter- und Kategorieerkennung, die der Wärmemessdienst verwendet.

{% hint style="warning" %}
Aareon Connect synchronisiert nicht die eigentlichen Verbrauchsdaten an sich, sondern nur die Metadaten. Der Partner ist verantwortlich für das Abrufen der eigentlichen Verbrauchsdaten.
{% endhint %}
