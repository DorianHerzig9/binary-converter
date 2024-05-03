# binary-converter

Lorenzo Lai, Cyril Lutziger, Dorian Herzig, Simon Veljkovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 01.03.2024 | 0.0.0 | Wir haben noch den Auftrag 1303 vervollständigt. |
| 08.03.2024 | 0.0.1 | Wir haben unser Projekt begonnen. |
| 15.03.2024 | 0.1.0 | Wir haben die ersten User Stories umgesetzt. |
| 22.03.2024 | 0.2.5 | Wir waren heute am intensivsten am Programmieren. |
| 05.04.2024 | 0.5.0 | Wir haben die letzten User Stories umgesetzt und übrige Fehler verbessert. |
| 26.04.2024 | 1.0.0 | Wir haben unseren Portfolioeintrag geschrieben und somit das Projekt beendet. |

## 1 Informieren

### 1.1 Ihr Projekt

Wir erstellen einen binary-converter, der es uns ermöglicht, Zahlen in Binärcodes umzuwandeln und umgekehrt.

### 1.2 User Stories
| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |      muss       |  F   | Als ein Benutzer möchte ich eine Dezimalzahl in das Binärformat umwandeln können. |
| 2    |      muss       |  F   | Als ein Benutzer möchte ich sicherstellen, dass das Programm nur mit Nummern funktioniert, um Fehler bei der Umwandlung zu vermeiden. |
| 3    |      muss       |  F   | Als ein Benutzer möchte ich die Möglichkeit haben, positive Zahlen oder Minuszahlen in Binärcode umzuwandeln. |
| 4    |      kann       |  Q   | Das Programm kann eine Fehlermeldung anzeigen, wenn die Eingabe keine gültige Zahl ist, um Benutzer über fehlerhafte Eingaben zu informieren. |
| 5    |      muss       |  F   | Als ein Benutzer möchte ich die Fähigkeit haben, Binärcodes auch in normale Zahlen umzuwandeln, sodass ich diese wieder lesen kann. |

| Typ | Erklärung  |
| --- | ------------ |
|  F  |  Für das Funktionale des Programmes                          |
|  Q  |  Für die Qualität des Programmes                             |
|  R  |  Randbedingungen (müssen nicht implementiert werden)         |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet | Zahl | Zahl als Binärcode |
| 2.1  | Programm gestartet | Buchstabe | Bitte nur Zahlen |
| 3.1  | Programm gestartet | Positive oder negative Zahl | Zahl als Binärcode |
| 4.1  | Programm gestartet | Zahl mit Buchstabe (z.B. 1a) | Bitte nur Zahlen |
| 5.1  | Programm gestartet | Binärcode | positive oder negative Zahl |


### 1.4 Diagramme


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 15.03.2024 | Lorenzo Lai | Zahl zu Binärcode Funktion implementieren | 60 Minuten |
| 2.A  | 22.03.2024 | Simon Veljkovic | Fehlermeldungen implememtieren | 60 Minuten |
| 3.A  | 05.04.2024 | Cyril Lutziger | Funktion zum Minuszahlen und Kommazahlen in Binärcode umwandeln implementieren. | 90 Minuten |
| 4.A  | 05.04.2024 | Dorian Herzig | Binärcode zu Zahl Funktion implementieren | 90 Minuten |

Total: 4 Arbeitspakete

## 3 Entscheiden

Dieses Projekt dient hauptsächlich dazu, unser Wissen über Binärcodes in ein Programm umzusetzen und anhand der passenden User Stories dürfte ein gutes Programm machbar sein.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 15.03.2024 | Lorenzo Lai | 60 Minuten | 60 Minuten |
| 2.A  | 22.03.2024 | Simon Veljkovic | 60 Minuten | 90 Minuten |
| 3.A  | 22.03.2024 | Cyril Lutziger  | 90 Minuten | 180 Minuten |
| 4.A  | 05.04.2024 | Dorian Herzig   | 90 Minuten | 120 Minuten |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |



