# SOP Master Index – ITA Media GmbH

Kompakte Teamlogik für KI‑Delivery mit klaren Rollen und Übergaben.

---

## Teamstruktur (reduziert)

```
Sales/Discovery  ->  Projektmanagement  ->  Tech  ->  Dev  ->  Client
```

---

## SOP‑Dokumente

| Rolle | Dokument | Fokus |
|------|----------|-------|
| Sales/Discovery | `01-sop-sales-discovery.md` | Bedarf, Use‑Cases, KPI‑Ziele |
| Projektmanagement | `02-sop-project-manager.md` | Scope, Kommunikation, Risiko |
| Tech | `03-sop-technical-lead.md` | Architektur, Security, RAG/LLM |
| Dev | `04-sop-developer.md` | Umsetzung, Tests, Doku |
| Client | `05-sop-client.md` | Daten, Freigaben, Feedback |

---

## Handoff‑Logik

```
Sales/Discovery -> PM:
- Zielbild, priorisierte Use‑Cases, KPI‑Baseline

PM -> Tech:
- Scope, Datenquellen, Governance‑Vorgaben

Tech -> Dev:
- Architektur, Integrationen, Testanforderungen

Dev -> PM:
- Implementierung, QA‑Report, Doku

PM -> Client:
- Handover, Training, Betrieb
```

---

## Kommunikationsstandard

- Kundenanfragen: Antwort innerhalb 24h
- Kritische Themen (Security/Incidents): sofort eskalieren
- Änderungen an Prompts/Modellen nur mit Freigabe

