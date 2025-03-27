# SAP Blue Eagle

## Aareon Connect in SAP Blue Eagle aktivieren

Um Aareon Connect in SAP Blue Eagle zu öffnen und somit Integrationen zu aktivieren müssen Sie die Transaktion **BE2/REIFAC** öffnen:

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Somit öffnen sich Aareon Connect direkt in SAP Blue Eagle:

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

## Use Cases

### Zuständige Sachbearbeiter

In SAP ist es möglich an verschiedenen Strukturelementen zuständige Bearbeiter, sowohl externe als auch interne als Geschäftspartner zuzuordnen. Dazu gibt es folgende Einrichtungstabellen:

1\. Einrichtungstabellen

1.1 Geschäftspartner-Rollen (GP -> allg. Einrichtung -> GP-Rollen)

* In SAP werden global GP-Rollen definiert

1.2. WE, Einheit, Vertrag -> Partner

* an den WE,  Einheit oder Vertrag können den GP-Rollen Sachbearbeiter zugeteilt werden

1.3. Tickettypen- GP-Rollen

* bei der Erstellung von Tickets, wird über die Einrichtung der Zuordnung von GP-Rollen an Tickettypen, der hinterlegte SB an der WE, Einheit oder Vertag gefunden und am Ticket eingetragen

1.4 Kreditoren

* an Kreditoren können GP-Rollen ebenso hinterlegt werden

**Darstellung in SAP**

Zu 1.2 an der WE werden GP-Rollen Geschäftspartnern (Sachbearbeitern) zugeordnet

<figure><img src="../.gitbook/assets/GP-Rollen an der WE.png" alt=""><figcaption></figcaption></figure>

Zu 1.3 An den Tickettypen werden GP-Rollen zugeordnet

<figure><img src="../.gitbook/assets/GP-Rollen an Tickets.png" alt=""><figcaption></figcaption></figure>

Zu 1.4 Kreditoren: GP-Rolle zuordnen

<figure><img src="../.gitbook/assets/GP-Rollen an Kreditoren.png" alt=""><figcaption></figcaption></figure>

&#x20;**Kundenabfragen:**

* Welche Geschäftspartnerrollen sollen übertragen werden?
* Welche Tickettypen sind angelegt?
* &#x20;Welche GP-Rollen sind den Tickettypen zugeordnet?
* Werden GP- Rollen auch an der Einheit oder dem Vertrag zugeordnet?
* Werden GP – Rollen an Kreditoren zugeordnet?

### Dokumente



#### Einstellungen

**Filter**

In SAP Blue Eagle muss ein Customizing hinterlegt werden, in dem Sie die Dokumentenarten, die über Aareon Connect verfügbar sein sollen einstellen können.

Zusätzlich können Sie basierend auf der genauen Dokumentenarten Kennung die Dokumente weiter, je nach Partner Lösung einschränken.
