# Demobank

Demobank is a public reference project for testing banking workflows without
connecting to a real bank account. It provides transparent demo data,
documented behavior, and an open issue tracker so integrations can be discussed
and improved in public.

Demobank is not a bank, not a payment service, and not a replacement for a
regulated FinTS, EBICS, PSD2, or online banking connection.

## English

### Purpose

This repository exists so developers, operators, and users can see how a demo
bank behaves before connecting real banking infrastructure. It is intended for:

- explaining demo account and transaction flows
- testing import and reconciliation workflows
- reproducing bugs with non-sensitive data
- collecting public issues and implementation notes
- documenting safe boundaries for banking-related automation

### What this project should contain

- sample accounts with fake identifiers
- sample transactions for common accounting cases
- documented response formats
- predictable demo fixtures
- issue templates for bug reports and feature requests
- examples for read-only integrations

### Safety boundaries

Demobank must never contain real banking credentials, real PINs, TANs, session
tokens, full real IBANs, private customer data, or production bank statements.

All examples should be synthetic. If an example needs realistic structure, use
clearly fake values and document that they are not connected to a real account.

### Public issues

Issues are enabled so everybody can report problems, ask questions, and suggest
improvements. Please include enough context to reproduce the behavior, but do
not post secrets or personal banking data.

Good issue reports include:

- what you tried to do
- what you expected to happen
- what actually happened
- relevant demo fixture names or command output
- the software version or commit you used

### Relationship to real banking

Real banking integrations should use regulated and bank-supported interfaces
such as FinTS/HBCI, EBICS, PSD2/XS2A, or official export formats. Demobank is a
development and documentation aid only.

## Deutsch

### Zweck

Dieses Repository dient als öffentliche Referenz für Banking-Workflows, ohne
echte Bankkonten anzubinden. Es soll nachvollziehbar zeigen, wie eine Demo-Bank
funktioniert, welche Datenformate verwendet werden und wie Fehler öffentlich
gemeldet werden können.

Gedacht ist Demobank für:

- Erklärung von Demo-Konten und Demo-Umsätzen
- Tests von Import- und Abgleichsprozessen
- Reproduktion von Fehlern mit nicht-sensiblen Daten
- öffentliche Issues und technische Diskussionen
- Dokumentation sicherer Grenzen bei Banking-Automation

### Was hier hinein gehört

- Beispielkonten mit künstlichen Kennungen
- Beispielumsätze für typische Buchhaltungsfälle
- dokumentierte Antwortformate
- stabile Demo-Fixtures
- Issue-Templates für Fehler und Wünsche
- Beispiele für rein lesende Integrationen

### Sicherheitsgrenzen

In dieses Repository gehören niemals echte Bankzugangsdaten, echte PINs, TANs,
Session-Tokens, vollständige echte IBANs, private Kundendaten oder produktive
Kontoauszüge.

Alle Beispiele müssen synthetisch sein. Wenn ein Beispiel realistisch aufgebaut
sein soll, nutze eindeutig künstliche Werte und dokumentiere, dass sie zu keinem
echten Konto gehören.

### Öffentliche Issues

Issues sind aktiviert, damit alle Fehler melden, Fragen stellen und
Verbesserungen vorschlagen können. Bitte liefere genug Kontext zur
Reproduktion, aber poste keine Secrets und keine persönlichen Bankdaten.

Gute Issues enthalten:

- was du versucht hast
- welches Verhalten du erwartet hast
- was tatsächlich passiert ist
- relevante Demo-Fixtures oder Kommandoausgaben
- Software-Version oder Commit

### Bezug zu echtem Banking

Echte Banking-Integrationen sollten regulierte und von der Bank unterstützte
Schnittstellen verwenden, zum Beispiel FinTS/HBCI, EBICS, PSD2/XS2A oder
offizielle Exportformate. Demobank ist nur eine Entwicklungs- und
Dokumentationshilfe.

## License

No license has been selected yet. Until a license is added, all rights remain
reserved by the repository owner.
