<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Solothurn: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-25 07:51 UTC, Solothurn: Systematische Sammlung (bgs.so.ch): 424 Adressen gelesen; 92 hinzugefügt, 1 geändert, 0 entfernt; Änderungen gefunden; 149 nicht veröffentlicht, davon 0 ohne Grund.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Solothurn: Systematische Sammlung (bgs.so.ch)](https://bgs.so.ch/) | `<act>/` | täglich | 2026-11-25 07:51 UTC | Änderungen gefunden | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 07:42](checks/2026-11.md#ch-lexwork-solothurn-20261125t074225z) | lexwork-solothurn | 424 | 92 | 1 | 0 | 149 (0) | Änderungen gefunden | [81](https://github.com/lexifina/switzerland-solothurn-law/compare/186418574491...8c2f3d8f8357) |
| [2026-11-24 12:21](checks/2026-11.md#ch-lexwork-solothurn-20261124t122150z) | lexwork-solothurn | 712 | 242 | 0 | 0 | 187 (0) | Änderungen gefunden | [122](https://github.com/lexifina/switzerland-solothurn-law/compare/a1c4297d15b8...f14c5bbd931a) |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
