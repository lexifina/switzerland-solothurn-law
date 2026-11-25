<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Solothurn only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-25 07:51 UTC, Solothurn: systematic collection (bgs.so.ch): 424 addresses read; 92 added, 1 changed, 0 removed; changes found; 149 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Solothurn: systematic collection (bgs.so.ch)](https://bgs.so.ch/) | `<act>/` | daily | 2026-11-25 07:51 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 07:42](checks/2026-11.md#ch-lexwork-solothurn-20261125t074225z) | lexwork-solothurn | 424 | 92 | 1 | 0 | 149 (0) | changes found | [81](https://github.com/lexifina/switzerland-solothurn-law/compare/186418574491...8c2f3d8f8357) |
| [2026-11-24 12:21](checks/2026-11.md#ch-lexwork-solothurn-20261124t122150z) | lexwork-solothurn | 712 | 242 | 0 | 0 | 187 (0) | changes found | [122](https://github.com/lexifina/switzerland-solothurn-law/compare/a1c4297d15b8...f14c5bbd931a) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
