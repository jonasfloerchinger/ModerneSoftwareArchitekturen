# Entwurfsmuster

* Status: proposed
* Date: 2023-03-15

## Context and Problem Statement

Anfang des Entwicklungsprozess: Es muss stragegisch die richtige Architektur gewählt werden.
Problem: richtige Entscheidung treffen

## Considered Options

* Schichtenmodell
* Microservices-Architektur
* SOA (Service-oriented Architecture)
* DDD (Domain-Driven Design)

## Decision Outcome

Chosen option: "Schichtenmodell", because ein Vorteil des Schichtenmodells ist, dass die Schichten eine gute Wartbarkeit und Flexibilität ermöglichen. Diese Modularität macht es leicht Erweiterungen vorzunehmen. Außerdem können die einzelnen Schichten in zukünftigen Projekten wiederverwendet werden, wenn man die entsprchende Funktion der Schicht braucht. Die Modularität bietet weiterhin den Vorteil, dass jede Schicht einzeln getestet werden kann. Durch hinzufügen zusätzliche Schichten ist die Architektur gut skalierbar.
Ein weiterer Vorteil des Schichtenmodells ist die Einfachheit. Die Architektur ist leicht zu implementieren und verständlich. Es ist eine gute Wahl für kleinere Anwendungen, wie in diesem Projekt, sodass unnötige Komplexität vermieden wird.
Durch die Verwendung von Schnittstellen zwischen den Schichten können Entwickler die Details jeder Schicht ausblenden und sich auf die Funktionen konzentrieren, die für ihre Aufgaben relevant sind. Dies erleichtert die Zusammenarbeit.
Die Schichten können der Architektur auch zum Nachteil gereichen. Wenn diese möglicherweise zu groß werden, was zu einer schlechten Leistung führt, oder zu klein, was zu einer unnötigen Komplexität führt. Das Schichtenmodell kann auch Schwierigkeiten bei der Handhabung von Änderungen in einer Schicht verursachen, da dies Auswirkungen auf die anderen Schichten haben kann.
