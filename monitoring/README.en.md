<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Fribourg only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 06:08 UTC, Fribourg: systematic collection (bdlf.fr.ch): 512 addresses read; 0 added, 0 changed, 0 removed; no change; 21 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Fribourg: systematic collection (bdlf.fr.ch)](https://bdlf.fr.ch/) | `<act>/` | daily | 2026-11-28 06:08 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:59](checks/2026-11.md#ch-lexwork-fribourg-20261128t055948z) | lexwork-fribourg | 512 | 0 | 0 | 0 | 21 (0) | no change `verify-differ` | — |
| [2026-11-27 06:04](checks/2026-11.md#ch-lexwork-fribourg-20261127t060408z) | lexwork-fribourg | 616 | 0 | 0 | 0 | 20 (0) | no change `verify-differ` | — |
| [2026-11-26 06:10](checks/2026-11.md#ch-lexwork-fribourg-20261126t061042z) | lexwork-fribourg | 599 | 0 | 0 | 0 | 21 (0) | no change `verify-differ` | — |
| [2026-11-25 06:32](checks/2026-11.md#ch-lexwork-fribourg-20261125t063226z) | lexwork-fribourg | 735 | 0 | 0 | 0 | 21 (0) | no change | — |
| [2026-11-24 12:05](checks/2026-11.md#ch-lexwork-fribourg-20261124t120502z) | lexwork-fribourg | 635 | 18 | 0 | 0 | 20 (0) | changes found `verify-differ` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
