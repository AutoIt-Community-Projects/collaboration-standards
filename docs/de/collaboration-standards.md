## Thema A

### ...

<br>

## Thema B

### ...

<br>

## Beitragsrichtlinie

### Zweck

Für Projekte/Repositories gibt es mehrere allgemeine und empfohlene Richtlinien, die zu einer stabilen und verständlichen Art der Arbeit mit Code im Team führen.

Einer der Hauptgründe für die Existenz dieser Leitlinien und Standards ist die Einheitlichkeit beim Schreiben von Code, auch beim Review des Codes. Ansonsten könnte es zu allerlei verschiedenen Stilen kommen, die Neueinsteigern verwirren könnten und den Einstieg in das Projekt erschweren würden.

<br>

### 1. Sprache

- verwende Englisch für Code, Kommentare, Branches, Tags, Commit-Nachrichten usw.
- versuche so gut es geht Deutsch und Englisch nicht zu vermischen
- allerdings übersetze auch keine deutschen Eigennamen (behalte sie wie sie sind)

<br>

### 2. Branch Benennung

- verwende kebab-style für die Branch Benennung
  - alles klein geschrieben
  - alle Wörter separiert durch einen Bindestrich (Minus)

**Beispiele**

- add-database-connection
- add-login-feature
- apply-common-standards
- fix-prototype-code
- project-restructuring
- remove-obsolete-feature
- update-to-specific-version

**Warum**

- Einheitlichkeit
- verbreitete Art und Weise, dies zu tun

<br>

### 3. Commit Nachricht

**Verwendung**

- nutze den "Keep a Changelog" Stil (https://keepachangelog.com/en/1.0.0/)
  - \<Schlagwort\>\<Doppelpunkt\>\<Leerzeichen\>\<Commit Nachricht als Satz mit schließenden Punkt.\>
- Schlagwörter und deren Zweck
  - **Added** für neue Features.
  - **Changed** für Änderungen in existierender Funktionalität.
  - **Deprecated** für Features die bald entfernt werden sollen.
  - **Documented** für Änderungen die ausschließlich mit Dokumentation zu tun haben.
  - **Fixed** für etwaige Fehlerbehebungen.
  - **Refactored** für Änderungen die weder einen Fehler beheben noch ein Feature hinzufügen.
  - **Removed** für entfernte Features.
  - **Security** im Falle von Schwachstellen.
  - **Styled** for changes like whitespaces, formatting, missing semicolons etc.
  - **Styled** für Änderungen wie Leerzeichen, Formatierung, fehlende Semikolons usw.

**Beispiele**

- `git commit -m "Added: Login feature to main view."`
- `git commit -m "Changed: Adjustment of the GUI layout."`
- `git commit -m "Fixed: Broken label by set on top attribute"`
- `git commit -m "Refactored: Usage of map data type instead of array."`

**Warum**

- Einheitlichkeit
- neben "conventional commits" (cc) (https://www.conventionalcommits.org/en/v1.0.0/) ist der "Keep a Changelog" Stil ein verbreiteter Weg (jedoch einfacher und besser lesbar als cc) damit umzugehen
- die CHANGELOG.md Datei kann auf einfache Weise generiert und verwaltet werden

<br>

### 4. Pull requests (merge requests)

<br>

### 5. Code review

<br>

### 6. Version hochzählen (SemVer)

<br>

### 7. Changelog (Änderungshistorie)

<br>

### 8. Releases und Tags

<br>

## Workflow Beschreibung

### GitHub issues

<br>

### ...

<br>
