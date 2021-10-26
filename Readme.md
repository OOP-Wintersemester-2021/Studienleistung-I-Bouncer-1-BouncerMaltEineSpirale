# Studienleistung I: Bouncer | 1. Bouncer malt eine Spirale
## Allgemeine Hinweise zur Studienleistung
In dieser Studienleistung werden Sie drei Programmieraufgaben lösen.
Diese Programmieraufgaben sind auf drei Projekte - pro Teilaufgabe ein Projekt - aufgeteilt.
Um die Aufgaben zu bearbeiten, müssen Sie zuerst das jeweilige Projekt in IntelliJ öffnen.
Diese Projekte sind:
* ```Studienleistung-I-Bouncer-1-BouncerMaltEineSpirale```
* ```Studienleistung-I-Bouncer-2-BouncerImLabyrinth ```
* ```Studienleistung-I-Bouncer-3-BouncerFuelltEineGrube```

Für die Teilaufgabe, die in diesem Dokument beschrieben ist, öffnen Sie bitte das Projekt: ```Studienleistung-I-Bouncer-1-BouncerMaltEineSpirale```

Nutzen Sie zum Lösen der einzelnen Aufgaben die bereitgestellten Klassendateien.
Zum Einreichen Ihrer Aufgaben nutzen Sie die entsprechende Funktion in GRIPS. 
Falls Sie Problemen mit dem Starterpaket oder dem Einreichen der Aufgabe haben, können Sie sich in den Handouts auf GRIPS informieren.

Achtung: Eine Verlängerung der Abgabefrist ist nicht möglich. 
Einreichungen, die uns (zu spät) per E-Mail erreichen, werden nicht mehr berücksichtigt. 
Alle nicht eingereichten Aufgaben werden mit nicht bestanden bewertet. 
Testen Sie den Upload am besten schon vor Ablauf der Frist in Ruhe: Sie können bis zum Abgabetermin beliebig viele neue Lösungen einreichen.

Bewertungskriterien: Für die gesamte Studienleistung gilt, dass die eingereichten Lösungen nur die in der Aufgabenstellung beschriebenen Probleme lösen sollen. 
Lassen Sie keinen Teil der jeweiligen Aufgabe weg und interpretieren Sie die Fragestellung nicht selbstständig.
Bewertet wird, in wie weit Sie das beschriebene Problem vollständig lösen. 
Wenn Sie die Aufgaben erfolgreich bearbeitet haben, können Sie Ihre Lösung gerne kreativ gestalten und erweitern; achten Sie dabei darauf, dass die eigentlichen Anforderungen weiterhin erfüllt bleiben.
Die Qualität Ihres Codes fließt in die Gesamtnote mit ein: Nutzen Sie Decomposition um Ihre Programme übersichtlich zu gestalten. 
Verwenden Sie sinnvolle Bezeichner für Variablen und Methoden und kommentieren Sie ausreichend. 
Beachten Sie dazu die Kriterien für guten und schlechten Code, die in der Vorlesung erwähnt wurden.

Sollten Sie Fragen haben oder Hilfe brauchen, können Sie im Discord unter der Kategorie Support in den Channel Studienleistung uns eine Nachricht hinterlassen. 
Wir stehen Ihnen dann zeitnah zur Seite über eine Direktnachricht.

## Ausgangslage

Bouncer steht in einem leeren, quadratischen Raum.
Bouncers Aufgabe ist es, eine blaue Spirale in den kompletten Raum zu zeichnen.
Der innerste Punkt der Spirale soll mit einem roten Feld markiert werden. 

| Bouncer steht im leeren, quadratischen Raum. | Bouncer steht auf den roten Feld in der Mitte der Spirale. |
|:------:|:------:|
| ![Bouncer steht auf dem ersten Feld der kaputten Straße.](./docs/spiral.png) | ![Bouncer steht auf dem letzten Feld der reparierten Straße](./docs/spiral_done.png) |


Die Ausgangsbedingung für diese Aufgabe ist wie folgt: 
Bouncer steht am unteren Kartenrand auf dem ersten Feld (0, 14) des Raumes und schaut nach Osten.
Bouncer soll nun entgegen dem Uhrzeigersinn eine blaue Spirale in den Raum malen.

## Aufgabe

Lösen Sie folgende Teilaufgaben, um die blaue Spirale in den Raum zu zeichnen.

1. Bouncer muss überprüfen und sich merken, wie breit (und hoch) der Raum ist.
2. Bouncer muss die Spirale in der linken unteren Ecke beginnen und entgegen dem Uhrzeigersinn die Spirale malen
3. Zwischen den Linien der Spiralen soll immer Platz der Größe von einem Feld freibleiben (weiß).
4. Sobald Bouncer aus Platzgründen die Spirale nicht mehr weitermalen kann, färbt Bouncer das Feld auf dem Bouncer steht rot und bleibt stehen.

