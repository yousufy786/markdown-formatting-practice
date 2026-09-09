# Release-Plan: Campus App

## Ziel
Das Team bereitet Version 1.0 für die Veröffentlichung am Freitag vor.

## Aufgaben
- [x] Vorbereitung abgeschlossen
- [ ] Umsetzung noch offen
  - [ ] Navigation testen
  - [ ] Profilseite prüfen
  - [ ] README ergänzen

---

## Teamübersicht

| Bereich | Verantwortlich | Status |
| :--- | :--- | :--- |
| Navigation | Aylin | fertig |
| Profilseite | Ben | in Arbeit |
| Tests | Team | offen |

- [x] Repository klonen
- [x] Lokalen main aktualisieren

---

## Geplanter Ablauf

### 1. Main aktualisieren
```bash
git switch main
git pull
### 2. Arbeitsbranch erstellen

```bash
git switch -c release-check
```

### 3. Änderungen prüfen und speichern

```bash
git status
git add .
git commit -m "Prepare release"
```

> **Hinweis:** Direkte Änderungen auf `main` vermeiden. Für jede Aufgabe wird ein eigener Branch verwendet.

---

## Dokumentation

* [GitHub Flow](https://docs.github.com)
