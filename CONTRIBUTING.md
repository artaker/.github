# Beitragsrichtlinien (intern)

Diese Organisation nutzt GitHub für **interne** und **Kundenprojekte**, nicht für Open Source. Die folgenden Regeln gelten für alle Mitglieder und Kollaboratoren mit Repository-Zugang.

## Voraussetzungen

- GitHub-Profil mit **@artaker.it** als primary email ([ARTAKER.md](ARTAKER.md))
- Zugang nur über Org-Owner / dokumentierten Onboarding-Prozess
- Keine Forks von privaten Repositories nach außen ohne Freigabe
- Einhaltung der internen **KI-**, **DSGVO-Richtlinie** und **Kundenverträge** ([CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)) — bei Fragen **Christian Semrajc** (HR)

## Workflow

1. **Issue** anlegen (Vorlage aus `.github/ISSUE_TEMPLATE/` nutzen, falls vorhanden)
2. **Branch** vom Default-Branch erstellen (Namenskonvention je Repository, z. B. `feature/kurzbeschreibung`, `fix/ticket-nr-beschreibung`)
3. **Commits** klar und nachvollziehbar (Ticket-Referenz im Betreff, wo üblich)
4. **Pull Request** mit Vorlage ausfüllen (Testplan, Reviewer, verlinktes Issue)
5. **Review** durch mindestens einen berechtigten Reviewer; Merge nur bei grünen Required Checks (sofern konfiguriert)

## Pull Requests

- Ein PR pro logische Änderung
- Keine Force-Pushes auf geschützte Branches
- Security-Fixes: koordiniert mit [SECURITY.md](SECURITY.md), nicht als öffentliches Issue

## CODEOWNERS

`CODEOWNERS` gilt **pro Repository** — legen Sie es im jeweiligen Projekt-Repo fest. In `artaker/.github` siehe [CODEOWNERS](CODEOWNERS).

## Verhalten

[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) ist verbindlich.

## Hilfe

- Technik / Doku: [SUPPORT.md](SUPPORT.md) — docbee@artaker.it
- Sicherheit: [SECURITY.md](SECURITY.md) — compliance@artaker.it
- Richtlinien (KI, DSGVO, Kundenverträge): [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) — Christian Semrajc (HR)
- GitHub-Org: [ARTAKER.md](ARTAKER.md)
