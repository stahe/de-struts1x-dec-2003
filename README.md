# Einführung in das Struts 1.x-Framework

👉 **Online-Kurs:**
[Einführung in das Struts 1.x-Framework anhand von Beispielen (Dezember 2003)](https://stahe.github.io/de-struts1x-dec-2003/)

---

## Ziele

Das Ziel dieses Projekts ist es, das Entwicklungs-Framework **Struts 1.x** zu erkunden, das aus dem Jakarta-Struts-Projekt der **Apache Software Foundation** hervorgegangen ist.

Struts bietet ein Standard-Framework für die Entwicklung von Java-Webanwendungen, die auf dem **MVC-Architekturmodell (Model–View–Controller)** basieren.

Die Lernziele sind:

* Die Prinzipien des MVC-Modells zu verstehen
* Eine Java-Webanwendung korrekt zu strukturieren
* Die Darstellung, die Anwendungslogik und den Datenzugriff klar voneinander zu trennen
* Diese Architektur mithilfe von Servlets und JSP zu implementieren
---
## Das MVC-Modell
Das **MVC-Modell (Model–View–Controller)** zielt darauf ab, Folgendes zu trennen:
| Ebene             | Rolle                  |
| ------------------ | --------------------- |
| **View (V)**        | Benutzeroberfläche |
| **Controller (C)** | Anwendungslogik   |
| **Model (M)**     | Datenzugriff     |

Diese Architektur ist auch als **dreistufige Architektur** bekannt.

### 1️⃣ Ansicht – Benutzeroberfläche

* Typischerweise ein Webbrowser
* Kann auch eine eigenständige Anwendung sein
* Sendet HTTP-Anfragen und formatiert die Ergebnisse

### 2️⃣ Controller – Anwendungslogik

* Verarbeitet Benutzeranfragen
* Koordiniert die Verarbeitungsaktivitäten
* Ruft Geschäftsklassen und Datenquellen auf

### 3️⃣ Modell – Datenquellen

Kann bestehen aus:
*
* Datenbanken
* Flache Dateien
* Webdienste
* LDAP-Verzeichnisse
* Jede andere persistente Quelle
*
* Das Hauptziel des MVC-Modells ist es, eine **starke Unabhängigkeit** zwischen diesen drei Schichten aufrechtzuerhalten, um die Auswirkungen von Änderungen zu begrenzen.
*
*
---

## MVC mit Servlets und JSP

Bei der Anwendung von MVC mit traditionellen Java-EE-Technologien (Servlets + JSP) ist die Architektur wie folgt aufgebaut:

### 🔹 Controller
* Ein **Servlet** fungiert als Einstiegspunkt der Anwendung
* Zentralisiert die HTTP-Anfragen

### 🔹 Geschäftslogik
* Eine Reihe von **Geschäftsklassen**
* Implementiert die funktionalen Regeln

### 🔹 Datenzugriff

* **Datenzugriffsklassen (DAO)**
* Interagieren mit Datenbanken oder anderen Systemen

### 🔹 Ansichten

* **JSP**-Seiten
* Verantwortlich für die Darstellung

---

## Warum Struts?

Struts formalisiert diese Organisation:

* Durch die Zentralisierung der Anforderungssteuerung
* Durch die Standardisierung der Aktionsverwaltung
* Durch die Erleichterung der Aufgabentrennung
* Durch die industrielle Strukturierung von Java-Webanwendungen

Es bietet somit ein solides Framework für die Entwicklung von Webanwendungen, die sich streng an die MVC-Architektur halten.

---

## Zielgruppe

* Informatikstudierende
* Java-Webentwickler
* Personen, die die MVC-Architektur in Webanwendungen verstehen möchten

---

## Behandelte Technologien:

* Java
* Servlet
* JSP
* MVC-Architektur
* Struts 1.x-Framework

---

## Lizenz

Lehrmaterial für den akademischen Gebrauch.

Serge Tahé, Dezember 2003