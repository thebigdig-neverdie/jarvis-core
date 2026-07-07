# Jarvis Core

> **Deterministic Runtime Intelligence Infrastructure**

Jarvis Core ist eine lokale Runtime-Intelligence-Engine zur deterministischen Ausführung intelligenter Infrastrukturprozesse.

Der Fokus liegt nicht auf autonomen Entscheidungen, sondern auf einer kontrollierten, nachvollziehbaren und stabilen Runtime.

---

# Was ist Jarvis?

Jarvis ist **kein Chatbot**.

Jarvis ist **kein autonomer Agent**.

Jarvis ist eine **Runtime Intelligence Engine**, die Infrastruktur überwacht, analysiert und innerhalb klar definierter Grenzen unterstützt.

Der Mensch bleibt jederzeit die höchste Entscheidungsinstanz.

---

# 🚧 Aktueller Entwicklungsstatus – VANTABLACK

Jarvis Core befindet sich derzeit in der **VANTABLACK-Härtungsphase**.

In dieser Entwicklungsphase werden bewusst **keine neuen Funktionen entwickelt**.

Der Schwerpunkt liegt ausschließlich auf der technischen Stabilisierung, Vereinheitlichung und Absicherung des gesamten Runtime-Kerns.

Bevor neue Fähigkeiten entstehen, wird das Fundament kompromisslos gehärtet.

---

## Das VANTABLACK-Protokoll

VANTABLACK ist das interne Architektur- und Härtungsprotokoll von Jarvis.

Es definiert verbindliche Regeln für sämtliche Kernkomponenten und stellt sicher, dass neue Funktionen niemals auf einem instabilen Fundament entstehen.

### Grundprinzipien

- Stabilität vor neuen Funktionen
- Determinismus vor Komfort
- Eine Runtime – eine Wahrheit (Single Source of Truth)
- Klare Verantwortlichkeiten statt vermischter Logik
- Keine stillen Zustandsänderungen
- Keine impliziten `None`-Zustände
- Jede Verzweigung besitzt einen vollständigen Kontrollfluss (`if` / `else`)
- Zustandsänderungen ausschließlich über kontrollierte Schnittstellen
- Präzise Fehlerprotokollierung
- Defensive Fallback-Strategien

---

## Warum VANTABLACK?

Neue Funktionen lassen sich jederzeit ergänzen.

Ein instabiles Fundament begleitet ein Projekt jedoch über Jahre.

Deshalb wird der Runtime-Kern zunächst vollständig gehärtet, bevor neue Fähigkeiten entstehen.

> **Stabilität vor Features. Fundament vor Geschwindigkeit.**

---

# Aktueller Status

✅ Signal-driven

✅ Decision-based

✅ Action-controlled

✅ Outcome-aware

✅ Learning-enabled (controlled)

✅ Observable

✅ Deterministic

✅ Backbone-hardened

✅ Runtime live verified

---

# Was Jarvis macht

Jarvis verarbeitet Runtime-Zustände als kontrollierten Ausführungszyklus.

```text
Request
    ↓
Queue
    ↓
Worker
    ↓
Runtime Update
    ↓
Signal Generation
    ↓
Decision Engine
    ↓
Action System
    ↓
Outcome Evaluation
    ↓
Learning Update
```

Jeder Schritt ist deterministisch, nachvollziehbar und kontrolliert.

---

# Runtime Backbone

Jarvis läuft auf einem gehärteten Runtime-Backbone.

## Produktiv abgesichert

- Single Source of Truth Runtime
- Harte State Ownership
- Write Ownership ausschließlich über `RUNTIME_ACCESS`
- Deterministische Write-Validierung
- Kontrollierte State Transitions
- Cycle Guards
- Snapshot Guards
- Snapshot Commit Protection
- Runtime Consistency Validation
- Runtime Hotpath Guarding

Das Runtime-System akzeptiert keine stillen Mutationen außerhalb des definierten Zugriffspfades.

---

# Kernmodule

## Runtime Intelligence

- Signalbasierte Zustandsanalyse
- Stability Layer
- Signal Decay
- Deterministische Runtime-Klassifikation

## Decision Engine

- Confidence- und Priority-basierte Entscheidungen
- Score-basierte Trigger
- Kontrollierte Entscheidungsfilter
- Deterministische Bewertungslogik

## Action System

- Scale Up
- Scale Down
- Worker Restart
- Cooldown Protection
- Kontrollierte Action Gates

## Outcome System

- Action-Bewertung
- Success / Failure Tracking
- Queue Impact
- Stability Impact
- Outcome Feedback

## Learning System

- Kontrollierte adaptive Gewichtung
- GOOD / BAD / NEUTRAL Tracking
- Kontextbasierte Bewertung

> **Learning unterstützt Entscheidungen.**
>
> **Learning ersetzt Entscheidungen niemals.**

---

# Runtime Validation

Jarvis validiert kontinuierlich:

- State Transitions
- Write Ownership
- Worker Consistency
- Cycle Integrity
- Snapshot-Reihenfolge
- Runtime Invariants
- Guard Violations

## Ziel

Deterministisches Laufzeitverhalten ohne stille Inkonsistenzen.

---

# Live Verification

Der Runtime-Core wurde erfolgreich unter realen Laufzeitbedingungen geprüft.

## Bestätigt

- Keine Write-Bypässe
- Keine State Corruption
- Keine Guard-Bypässe
- Keine Snapshot Regression
- Keine Runtime-Hotpath-Regression
- Keine stillen Inkonsistenzen

## Status

**✔ Live Verification PASS**

---

# Dashboard

![Jarvis Dashboard](docs/dashboard.png)

Das Dashboard visualisiert unter anderem:

- Runtime Status
- Worker Verhalten
- Signal History
- Decision Ergebnisse
- Performance
- Learning State
- Runtime Health

---

# Sicherheitsmodell

Jarvis arbeitet ausschließlich innerhalb definierter Grenzen.

Eine Aktion erfolgt niemals ohne:

- Validiertes Signal
- Stabilität
- Schwellwerte
- Cooldown
- Write Ownership

### Learning darf

- Analysieren
- Unterstützen
- Gewichten

### Learning darf niemals

- Direkt entscheiden
- Runtime überschreiben
- Sicherheitsmechanismen umgehen

---

# Start

## Starten

```bash
docker compose up -d
```

## Status

```bash
curl localhost:8002/status
```

## Dashboard

```text
http://localhost:8002/dashboard/status.html
```

---

# Nutzung

Dieses Repository ist öffentlich einsehbar.

Der Quellcode dient ausschließlich Forschungs-, Lern- und Architekturzwecken.

Es handelt sich ausdrücklich **nicht um ein Open-Source-Projekt**.

Weitere Informationen befinden sich in:

- LICENSE
- NOTICE.md

---

# Nächster Meilenstein

Nach Abschluss der VANTABLACK-Phase beginnt die strukturelle Aufteilung des Runtime-Kerns.

Geplante Komponenten:

- runtime_state
- runtime_access
- runtime_snapshot
- runtime_validation

## Ziel

- Kleinere Verantwortlichkeiten
- Bessere Wartbarkeit
- Höhere Testbarkeit
- Identisches Laufzeitverhalten bei sauber getrennten Komponenten

---

# Projektstatus

Jarvis Core entwickelt sich zu einer deterministischen Runtime-Intelligence-Plattform mit einem gehärteten Backbone, kontrollierter Adaptivität und einer Architektur, bei der Stabilität grundsätzlich Vorrang vor neuen Funktionen besitzt.

---

**Copyright © 2026 andreas "thebigdig" piepke**

Alle Rechte vorbehalten.
