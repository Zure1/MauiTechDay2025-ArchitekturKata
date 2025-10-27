# Architektur Kata – Cashout System mit Promotions

## Ziel
Entwerft eine **Architektur** für ein System, das Waren einscannt und den **Endpreis** berechnet.
Dabei werden **Promotions** berücksichtigt:

**Promotions**
Das System verfügt zu jedem Zeitpunkt über eine **konfigurierte Menge an Promotions**.
Diese Promotions werden **nicht manuell ausgewählt**, sondern **automatisch angewandt**,
sobald der aktuelle Warenkorb die jeweiligen Bedingungen erfüllt.

**Beispiel:**  
Artikel A: 1,50 € pro Stück
Promotion: 3 Stück A kosten 4,00 €
Warenkorb: A×3 → Gesamtpreis 4,00 €

## Aufgabe
Erstellt folgende Diagramme:
1. **Modul-/Containerstruktur** (zentrale Bausteine)
2. **Promotion Engine** (wie werden die Promotions angewendet?)
3. **Sequenzdiagramm** für das obige Beispiel (Scan → Berechnung → Ergebnis)

## Anforderungen
- Ergebnis darf **nicht** von der Scan-Reihenfolge abhängen
- Entscheidung muss **erklärbar** sein (wie setzt sich der Endpreis zusammen?)

## Rahmen
- Zeit: 60–90 min
- Im Anschluss stellt jedes Team sein Ergebnis kurz vor

## Tools (frei wählbar)
- draw.io
- Excalidraw
- Miro
- etc.
