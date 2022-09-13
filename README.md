# 1100
☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Gilardoni

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

✍️ Number Generatorerstellen

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|1     |Muss             |Funktionalität|   User möchte  nur Zahlen zwischen 1-100 eingeben können, damit das Programm nicht abstürtzt|
|2     |Muss             |Funktionalität|  User möchte zuletzt eingegebenen Zahlen sehen können, damit  nicht die gleiche Zahl zweimal eingebe|
|3     |Muss             |Funktionalität|  User möchte  wissen, ob  eingegebene Zahl zu hoch oder zu tief , damit  einfacher ist die Lösung zu erraten|
|4     |Muss             |Funktionalität|  User möchte  wissen, ob  gesuchte Zahl erraten wurde und wie viele Versuche  gebraucht , damit  mit mir selber vergleichen kann|
|5     |Muss             |qualität|Als User möchte ich mithilfe von Farben dargestellt bekommen, ob die eingegebene Zahl der gesuchten entspricht oder nicht, damit ich es schnell und klar sehe|
|6     |kann             |Funktionalität|Als User möchte ich sehen, ob die Zahl die ich eingegeben habe akzeptiert wurde (z.B. String wurde erkannt und Fehler ausgegeben), damit ich erkenne, dass ich einen Text eingegeben habe|

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

[11:26] 
| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet | Eine Zahl eingeben | Das Programm ist nicht abgestürtzt.|
| 1.2  | Programm gestartet | Einen Text eingeben| Das Programm gibt einen Fehler aus.|
| 1.3  | Programm gestartet | Eine Zahl eingeben | Das Programm zeigt die eingegebenen Zahlen.|
| 1.4  | Programm gestartet | Eine Zahl eingeben | Das Programm gibt an, ob die Zahl zu hoch oder zu tief ist.|
| 1.5  | Programm gestartet | Eine Zahl eingeben | Das Programm zeigt an, ob die Zahl der gesuchten Zahl enspricht.|
| 1.6  | Programm gestartet | Eine Zahl eingeben | Das Programm zeigt mit Farben an, ob die richtige Zahl gefunden wurde.|
| 1.7  | Programm gestartet | Eine Zahl oder Text eingeben | nachedem ein Text eingegeben wurde, gibt das Programm die Fehler aus und zeigt an, dass nur Zahleneingegeben werden dürfen.|


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme
[La_1100 (2).zip](https://github.com/V4nil/1100/files/9400773/La_1100.2.zip)




## 2 Planen

| AP-№ | Frist | Beschreibung|geplante Zeit | Zuständig |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   30.08.2022    |   zahlen eingeben      |    90         |   Raul Gilardoni            |
| 1.A  |   30.08.2022    |  Wenn Text dann Fehler     |    90        |  Raul Gilardoni              |
| 1.A  |   30.08.2022    |  Programm giebt an ob Zahl höher oder tiefer      |    60        |   Raul Gilardoni             |
| 1.A  |   30.08.2022    |   zahl mit der generierten zahl vergleichen      |    30         |   Raul Gilardoni             |
| 1.A  |   30.08.2022    |   wenn Zahl über hundert dann Fehler  |    30         |    Raul Gilardoni            |



Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |13.09.2022|Es hatt funktioniert dass Program ist nicht abgestüzt.|Raul Gilardoni|
| 1.2  |13.09.2022|Es funktioniert, dass Program gibt einen Fehler aus.|Raul Gilardoni|
| 1.3  |13.09.2022|Es funktioniert, dass Programm gibt die angegebene Zahl hinaus.|Raul Gilardoni|
| 1.4  |13.09.2022|Es funktioniert, es gibt an ob die Zahl zu Hoch oder zu tief ist.|Raul Gilardoni|
| 1.5  |13.09.2022|Es funktioniert, es giebt an ob die Zahl der gesuchten Zahl entspricht.|Raul Gilardoni|
| 1.6  |13.09.2022|Es funktioniert, es wird angezeigt it Farbe.|Raul Gilardoni|
| 1.7  |13.09.2022|Es funktioniert, Ja es zeigt dieses an.|Raul Gilardoni|


✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
