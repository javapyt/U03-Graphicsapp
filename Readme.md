---
title: Template
author: Zuletzt bearbeitet von Alexander Bazo
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \usepackage{graphicx}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{OOP WS 2020/21}
    \lhead{U00 | Template}
    \cfoot{\includegraphics[height=2cm]{docs/footer.png}}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{OOP WS 2020/21}
      \lhead{U00 | Template}
      \cfoot[C]{\includegraphics[height=2cm]{docs/footer.png}}}
---


# Template für Übungsaufgaben 

## Wichtige Informationen zur Bearbeitung der Aufgabe 
 - [Link zu wichtiger Ressource](https://www.uni-regensburg.de/sprache-literatur-kultur/medieninformatik/)

## Starterpaket

Ein vorbereitetes Starterpaket zur selbständigen Implementierung der Aufgabe finden Sie [hier](https://github.com/OOP-Ubungen-WS2020-21/U03-Graphicsapp/archive/Starterpaket.zip).

## Text

---
author:	Alexander Bazo
---

# Grundlagen zu Variablen und Objekten

In der dritten Woche werden die grundlegenden Mechanismen zur Verwendung von Variablen eingeführt. Dazu erhalten Sie einen Überblick über die primitiven Datentypen der Programmiersprache Java sowie die Deklaration und Verwendung entsprechender Variablen. Zusätzlich wird das Konzept von Klassen und Objekten eingeführt. In Vorlesung und Übung ersetzen ab dieser Woche graphische, interaktive Anwendungen vom Typ *Graphics App* die bis jetzt verwendetete Bouncer-Umgebung.

## Vorlesung
In der Vorlesung wird das Prinzip des Speichers, Auslesens und Änderns von Werten und Inhalten durch Variablen erklärt. Sie lernen, (Zwischen-) Ergebnisse von Berechnungen und Programmabläufen abzuspeichern und an anderer Stellen einzusetzten. Aufbauend auf der Einführung primitiver Datentypen wird das Konzept von Klassen und Objekten erläutert. Sie lernen, Objekte auf Basis existierender Klassen zu erzeugen und durch den Aufruf von Methoden zu verwenden. 

In der Vorlesung wird zusätzlich die *Graphics App*-Umgebung eingeführt, die ab jetzt als Grundlagen für die Entwicklung der Beispiele und Übungsaufgaben dient. 

Die Folien zu dieser Vorlesung finden Sie [hier](https://regensburger-forscher.de/oop-slides/index.html?slides=03-Variablen-und-Objekte).

## Lesetexte

Die relevanten Lesetexte zu dieser Woche finden Sie aus rechtlichen Gründen im [GRIPS-Kurs](https://elearning.uni-regensburg.de/course/view.php?id=39457#section-0). Lesen Sie bitte das dort verfügbaren Kapitel 3 sowie die aufgeführten Ausschnitte aus dem Kapitel 4 aus *Eric Roberts: The Art & Science of Java*.

## Zentralübung

In der Zentralübung wird die Arbeit mit der *Graphics App*-Umgebung anhand erster, einfacher Beispiele demonstriert.


## Übung

In der Übung wenden Sie die vorgestellten Inhalte und Strategien zur Entwicklung erster *Graphics App*-Programme an. Dazu nutzen Sie die bekannten Anweisungen, Bedingungen und Schleifen sowie das neu eingeführte Konzept der Variablen.
