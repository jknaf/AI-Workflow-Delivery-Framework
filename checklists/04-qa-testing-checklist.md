# QA & Testing Checklist
## KI/RAG‑Qualität, Regression & Betrieb

---

## Daten & Testsets
```
 Repräsentative Testdaten vorhanden
 Edge Cases & Grenzwerte enthalten
 Sensible Daten anonymisiert
 Testset versioniert
```

---

## RAG‑Spezifische Tests
```
 Retrieval‑Qualität gemessen (Precision/Recall)
 Vektordatenbank‑Index geprüft
 Fallback‑Strategie getestet
 Quellenzitate korrekt (falls vorgesehen)
```

---

## Prompt- & Modelländerungen
```
 Prompt‑Regression‑Tests durchgeführt
 Modellwechsel mit A/B‑Vergleich
 Output‑Format validiert
 Guardrails geprüft
```

---

## Funktionale Tests
```
 Trigger/Inputs korrekt
 End‑to‑End‑Pfad validiert
 Integrationen stabil
 Fehlerbehandlung greift
```

---

## Monitoring & Logging
```
 Logging vollständig und PII‑reduziert
 Alerts bei Fehlerquote/Latenz
 Kostenmonitoring aktiviert
```

---

## Performance & Kosten
```
 Latenz unter Zielwert
 Token‑Kosten innerhalb Budget
 Lasttest (min. erwartete Peak‑Last)
```

---

## Abnahme
```
 KPIs erfüllt
 QA‑Report erstellt
 Client‑Abnahme dokumentiert
```

---

**Next**: `05-handover-checklist.md`
