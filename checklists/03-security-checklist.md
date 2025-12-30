# Security Checklist
## KI/RAG‑Security & DSGVO (ITA Media)

---

## Datenklassifizierung & Governance
```
 Datenklassifizierung je Quelle dokumentiert
     Öffentlich / Intern / Vertraulich / Personenbezogen
 Datenverantwortliche benannt
 Datenminimierung umgesetzt
 Aufbewahrungs- & Löschkonzept definiert
 Audit-Logs aktiviert
```

---

## RAG & Vektordatenbanken
```
 Vektordatenbank abgesichert (Netzwerk, Auth)
 Zugriffsrechte nach Least-Privilege
 Index-Refresh-Prozess dokumentiert
 Sensitive Daten vor Indexierung bereinigt
 Retrieval-Queries geloggt (ohne PII)
```

---

## Prompt- & Modelländerungen
```
 Prompt-Versionierung aktiv
 Modellwechsel dokumentiert
 Freigabeprozess vor Deployment
 Regression-Tests vor Produktivsetzung
```

---

## Credential Security
```
 Client besitzt alle Accounts und zahlt direkt
 Sichere Übertragung (1Password/Bitwarden)
 Keine Credentials in Code/Logs/Dokumentation
```

---

## Zugriff & Authentifizierung
```
 MFA für alle Admin-Zugänge
 Rollenbasierte Rechte in n8n/LLM/RAG
 Zugriff nur projektbezogen
 Offboarding-Plan vorhanden
```

---

## Netzwerk & Transport
```
 TLS 1.2+ für alle Verbindungen
 Keine sensiblen Daten in URLs
 Webhooks abgesichert (Token/Signature)
```

---

## Monitoring, Logging, Kostenkontrolle
```
 Monitoring für Fehlerquote/Latenz eingerichtet
 Alerts bei Schwellenwerten definiert
 Logging anonymisiert/PII‑reduziert
 Kostenkontrolle (Token/Request) aktiv
```

---

## DSGVO & Compliance
```
 DPA abgeschlossen (falls nötig)
 Verarbeitungstätigkeiten dokumentiert
 Rechte der Betroffenen berücksichtigt
 Incident-Response-Prozess definiert
```

---

**Next**: `04-qa-testing-checklist.md`
