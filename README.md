# ITA Media Delivery Framework

Ein schlankes, praxisnahes Delivery-Framework für KI‑gestützte Projekte der **ITA Media GmbH**. Es unterstützt den gesamten Projektlebenszyklus – von Potenzialanalyse bis Skalierung – mit Fokus auf **RAG‑Systeme, On‑Prem LLMs, Prozessautomatisierung, Content‑Qualitätssicherung, KI‑Training & Didaktik** sowie **Governance, Messbarkeit und DSGVO**.

---

## Start hier

1. **Überblick gewinnen**
   - `diagrams/01-master-architecture.md`
   - `processes/00-sop-master-index.md`
2. **Projektphase wählen**
   - `phases/01-analyse-strategie/README.md`
   - `phases/02-prototyping-validierung/README.md`
   - `phases/03-implementierung-skalierung/README.md`
3. **Kernartefakte nutzen**
   - Scope & Proposal: `templates/01-scope-of-work-template.md`, `templates/06-proposal-template.md`
   - Sicherheit & QA: `checklists/03-security-checklist.md`, `checklists/04-qa-testing-checklist.md`
   - Handover: `templates/08-handover-document-template.md`

---

## Wofür dieses Repository ist

Dieses Repository bündelt alle operativen Standards, Checklisten und Templates für die Lieferung von KI‑Projekten bei ITA Media. Es stellt sicher, dass Projekte:

- **messbar** geplant und überprüft werden (KPIs, Nutzen, Qualität),
- **DSGVO‑konform** umgesetzt werden (Datenklassifizierung, Governance, Security),
- **RAG‑fähig** und produktionsreif sind (Vektordatenbanken, Retrieval‑Tests, Monitoring),
- **skalierbar** werden (SLA, Monitoring, Betrieb),
- **transparent** an Kunden übergeben werden (Handover, Schulung, Dokumentation).

---

## Nutzung nach Projektphasen

### Phase 0–30 Tage: Analyse & Strategie
Ziel: KI‑Potenziale identifizieren, Datenlage klären, Zielbild definieren.

- **Kernaktivitäten**: Prozessaufnahme, Dateninventar, Use‑Case Priorisierung, Governance‑Check.
- **Artefakte**: KI‑Potenzialanalyse, KPI‑Baseline, Risiko‑ & DSGVO‑Bewertung.
- **Guides & Tools**:
  - `guides/01-client-onboarding-guide.md`
  - `guides/09-risk-management-guide.md`
  - `checklists/03-security-checklist.md`
  - `templates/01-scope-of-work-template.md`

### Phase 30–90 Tage: Prototyping & Validierung
Ziel: RAG/LLM‑Prototypen testen, Nutzen belegen, Risiken reduzieren.

- **Kernaktivitäten**: Datenpipelines, RAG‑Proof‑of‑Value, Prompt‑Tuning, Qualitätsmetriken.
- **Artefakte**: Prototyp‑Report, KPI‑Vergleich, Daten‑ & Modelländerungslog.
- **Guides & Tools**:
  - `guides/04-testing-qa-framework.md`
  - `checklists/04-qa-testing-checklist.md`
  - `templates/06-proposal-template.md`

### Phase 90–180 Tage: Implementierung & Skalierung
Ziel: Produktive Systeme, Monitoring, Betrieb & Übergabe.

- **Kernaktivitäten**: On‑Prem/Cloud Deployment, Observability, Security‑Hardening, Training.
- **Artefakte**: Betriebsdokumentation, Monitoring‑Dashboards, Handover‑Paket.
- **Guides & Tools**:
  - `guides/02-security-implementation.md`
  - `guides/05-handover-delivery.md`
  - `templates/08-handover-document-template.md`

---

## Schwerpunkt: KI, RAG, Governance, Messbarkeit, DSGVO

Dieses Framework erzwingt folgende Mindeststandards:

- **Datenklassifizierung & Governance**: Datenquellen, Zugriffe, Aufbewahrung, Löschkonzept.
- **RAG‑Qualität**: Retrieval‑Tests, Precision/Recall‑Metriken, Fallbacks.
- **Modellsteuerung**: Prompt‑Versionierung, Modell‑Changes, Freigabeprozess.
- **Messbarkeit**: KPI‑Definition, Baseline, Monitoring, Kostenkontrolle.
- **Sicherheit & DSGVO**: Risikoanalyse, DPA, Logs, Incident‑Prozess.

---

## Verzeichnisstruktur (Auszug)

```
ITA-Media-Delivery-Framework/
|
+-- phases/
|   +-- 01-analyse-strategie/
|   +-- 02-prototyping-validierung/
|   +-- 03-implementierung-skalierung/
|
+-- checklists/
+-- guides/
+-- processes/
+-- templates/
+-- diagrams/
```

---

## Teamlogik (reduziert)

- **Sales/Discovery**: Bedarf klären, Use‑Cases qualifizieren, KPI‑Ziele definieren.
- **Projektmanagement**: Planung, Kommunikation, Scope & Risiko.
- **Tech**: Architektur, Security, RAG/LLM‑Design.
- **Dev**: Implementierung, Tests, Dokumentation.
- **Client**: Daten, Feedback, Freigaben.

---

## Beitrag & Anpassung

Dieses Framework ist auf ITA Media zugeschnitten. Anpassungen erfolgen projektbezogen und werden versioniert dokumentiert.

---

**ITA Media GmbH** – KI‑gestützte Lösungen für Prozesse, Wissen und Bildung.
