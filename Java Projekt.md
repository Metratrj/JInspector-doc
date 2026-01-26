	Documentation
- mind. 10 Seiten

Projektumfeld

Nutzwertanalyse
Wenn Projekt nicht begründet werden kann ->
	Implementierung einfacher als externe Lösungen

Zeitangaben
Datenschutz

Projektziel
Was soll erreicht werden
Zeitplanung
Projektphasen

100 Stunden

Analyse
Entwurf
Implementierung und Einführung
Dokumentation

JByteInspector

1. Projektbezeichnung
   Entwicklung eines Java-Bytecode-Analysers zur Untersuchung von Klassenhierarchien und Instruktionsmetriken
   
2. Projektbeschreibung
   Ausgangslage: Nach einer Kompilierung von Java-Quellcode liegt dieser als Bytecode in .class-Dateien vor. Für Entwickler ist es oft schwer nachzuvollziehen, wie der Compiler Optimierungen vornimmt oder welche Abhängigkeiten auf Bytecode-Ebene tatsächlich bestehen.
   Zielsetzung: Ziel des Projekts ist die Erstellung einer Java-Anwendung, die .class-Dateien einliest, deren Struktur analysiert und die enthaltenen Informationen (z.B. Methoden, [[Opcode]]-Metriken, Sichtbarkeiten) übersichtlich aufzuarbeiten. Das Tool soll helfen, die Komplexität von kompilierten Klassen zu verstehen.
   
3. Zeitplanung

| **Phase**              | **Aufgabe**                         | **Stunden** | **Summe Phase** |     |
| ---------------------- | ----------------------------------- | ----------- | --------------- | --- |
| **1. Analyse**         | [[Ist-Analyse]] & Problemstellung   | 1h          | **6h**          |     |
|                        | Technologie-Recherche & Auswahl     | 5h          |                 |     |
| **2. Entwurf**         | Architekturdesign (Visitor Pattern) | 6h          | **16h**         |     |
|                        | Klassendiagramme & Programmlogik    | 6h          |                 |     |
|                        | UI-Konzept / Schnittstellendesign   | 4h          |                 |     |
| **3. Implementierung** | Projekt-Setup & Infrastruktur       | 5h          | **58h**         |     |
|                        | Kern-Entwicklung (Bytecode-Parsing) | 15h         |                 |     |
|                        | Analyse-Algorithmen & Logik         | 10h         |                 |     |
|                        | UI-Entwicklung & Reporting          | 8h          |                 |     |
|                        | Testing & Fehlerbehebung            | 20h         |                 |     |
| **4. Dokumentation**   | Technische Projektdokumentation     | 12h         | **20h**         |     |
|                        | Anwenderhandbuch                    | 4h          |                 |     |
|                        | Abschlussbericht & Reflexion        | 4h          |                 |     |
| **Gesamt**             |                                     |             | **100h**        |     |


# Projektantrag: JByteInspector

## 1. Projektbezeichnung

**Entwicklung eines Java-Bytecode-Analyzers zur statischen Untersuchung von Klassenhierarchien und Instruktionsmetriken.**

## 2. Projektbeschreibung

**Ausgangslage:**

Nach der Kompilierung von Java-Quellcode liegt dieser als Bytecode in `.class`-Dateien vor. Für Entwickler ist es oft schwer nachzuvollziehen, wie der Java-Compiler (javac) Optimierungen vornimmt oder welche Abhängigkeiten auf Bytecode-Ebene tatsächlich bestehen. Bestehende Tools wie `javap` sind oft rein textbasiert und für schnelle, statistische Auswertungen unhandlich.

**Zielsetzung:**

Ziel des Projekts ist die Entwicklung der Java-Anwendung **JByteInspector**. Diese soll `.class`-Dateien automatisiert einlesen, deren interne Struktur analysieren und die gewonnenen Informationen (wie Klassenhierarchien, Methodensignaturen und Instruktionsstatistiken) übersichtlich aufbereiten. Das Tool soll Entwicklern helfen, die Komplexität und den Aufbau von kompilierten Klassen effizient zu verstehen.

## 3. Zeitplanung (100 Stunden)

| **Phase**              | **Aufgabe**                                     | **Stunden** | **Summe** |
| ---------------------- | ----------------------------------------------- | ----------- | --------- |
| **1. Analyse**         | Ist-Analyse, Problemstellung                    | 3h          | **8h**    |
|                        | Technologie-Recherche & Auswahl                 | 5h          |           |
| **2. Entwurf**         | Architekturdesign & Schnittstellen              | 6h          | **14h**   |
|                        | Klassendiagramme & Design der Programmlogik     | 8h          |           |
| **3. Implementierung** | Projekt-Setup & Basis-Infrastruktur             | 5h          | **58h**   |
|                        | Kern-Entwicklung (Bytecode-Parsing)             | 18h         |           |
|                        | Implementierung der Analyse-Algorithmen         | 15h         |           |
|                        | UI-Entwicklung (CLI/GUI) & Reporting-System     | 10h         |           |
|                        | Qualitätssicherung (Unit-Tests & Bugfixing)     | 10h         |           |
| **4. Dokumentation**   | Erstellung der technischen Projektdokumentation | 12h         | **20h**   |
|                        | Erstellung des Anwenderhandbuchs                | 4h          |           |
|                        | Projektabschlussbericht & Reflexion             | 4h          |           |
| **Gesamt**             |                                                 |             | **100h**  |

---
