# artaker/.github

**Community Health Files und Org-Vorlagen** für die GitHub-Organisation [Artaker IT Group](https://github.com/artaker).

Dieses Repository ist **öffentlich**, enthält aber **keinen Anwendungs- oder Kundencode**. Es dient als zentrale Stelle für Richtlinien, Vorlagen und das öffentliche Org-Profil.

> **Außenauftritt:** Das Marketing-Profil der Organisation steht in [`profile/README.md`](profile/README.md) und erscheint auf https://github.com/artaker — nicht in dieser Root-`README.md`.

## Wofür dieses Repository da ist

| Zielgruppe | Was sie hier finden |
|------------|---------------------|
| **Besucher / Partner** | Über das [Org-Profil](profile/README.md) — Marken, Leistungen, Kontakt |
| **Org-Mitglieder** | Richtlinien (`ARTAKER.md`), Beitragsregeln, Issue/PR-Vorlagen |
| **Maintainer / Owners** | Übersicht aller Defaults, Setup-Hinweise, `CODEOWNERS` |

GitHub wendet Dateien aus diesem Repo als **Organisations-Defaults** an, sofern ein Projekt-Repository keine eigene Version hat (Reihenfolge: Repo `.github/` → Repo-Root → `docs/` → Org `.github`). Sie werden **nicht** in Klone der Projekt-Repos kopiert.

[Dokumentation: Default community health files](https://docs.github.com/de/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

## Inhalt dieses Repositories

### Org-Profil (öffentliche Übersicht)

| Pfad | Funktion |
|------|----------|
| [`profile/README.md`](profile/README.md) | Erscheint auf der Org-Startseite; Inhalte von [artaker.it](https://www.artaker.it) |

### Community Health Files (Org-Defaults)

| Datei | Funktion |
|-------|----------|
| [`SECURITY.md`](SECURITY.md) | Schwachstellen-Meldungen → compliance@artaker.it |
| [`SUPPORT.md`](SUPPORT.md) | Hilfe & Doku → docbee@artaker.it |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Verhaltenskodex (DE), Eskalation compliance@artaker.it |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Interner Entwicklungs-Workflow (kein OSS-Fork-Modell) |
| [`ARTAKER.md`](ARTAKER.md) | GitHub-spezifische Org-Regeln (@artaker.it, Sichtbarkeit, Teams) |

### Vorlagen

| Pfad | Funktion |
|------|----------|
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) | Bug, Feature, Zugang & Berechtigungen |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | Standard-PR-Checkliste |
| [`.github/ISSUE_TEMPLATE/config.yml`](.github/ISSUE_TEMPLATE/config.yml) | Issue-Chooser, Links zu Security/Support |

### Governance (nur dieses Repo)

| Datei | Funktion |
|-------|----------|
| [`CODEOWNERS`](CODEOWNERS) | Review-Pflichten **nur** für `artaker/.github` — nicht org-weit |

**Nicht enthalten (bewusst):** `workflow-templates/`, `FUNDING.yml`, `GOVERNANCE.md`, `LICENSE` (Lizenz pro Projekt-Repo).

## Nutzung der Organisation `artaker`

- **Primär:** private Repositories für interne und Kundenprojekte
- **Kein Open Source** als Standard; öffentliche Repos nur mit Owner-Freigabe ([`ARTAKER.md`](ARTAKER.md))
- **Sicherheit:** keine Security-Issues — siehe [`SECURITY.md`](SECURITY.md)
- **Profil-E-Mail:** Mitarbeiter mit `@artaker.it` als primary email auf GitHub

## Maintainer-Checkliste

Vor breiter Nutzung der Issue-Templates in der Org:

1. **Labels** in der Organisation anlegen: `bug`, `enhancement`, `access`
2. **Einladungen** offener Mitglieder annehmen → [`CODEOWNERS`](CODEOWNERS) mit echten `@artaker/<handle>` ergänzen
3. **Reviews:** `profile/README.md` (Sales/Marketing), `SECURITY.md` (Security Officer)

## Kontakt

| Thema | Kanal |
|-------|--------|
| Sicherheit / Compliance | [compliance@artaker.it](mailto:compliance@artaker.it) |
| Support / Dokumentation | [docbee@artaker.it](mailto:docbee@artaker.it) |
| Unternehmen | [artaker.it](https://www.artaker.it) · Heumühlgasse 11, 1040 Wien |
