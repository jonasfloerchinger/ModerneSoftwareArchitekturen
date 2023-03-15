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

Chosen option: "Schichtenmodell", because ein Vorteil des Schichtenmodells ist, dass die Schichten eine gute Wartbarkeit und Flexibilität ermöglichen. Diese Modularität macht es leicht Erweiterungen vorzunehmen. Außerdem können die einzelnen Schichten in zukünftigen Projekten wiederverwendet werden, wenn man die entsprchende Funktion der Schicht bracht. Durch hinzufügen zusätzliche Schichten nimmt die Skalierbarkeit zu.
