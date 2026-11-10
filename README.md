# Scoop bucket

Apps by ZettaByte, installable with [Scoop](https://scoop.sh) on Windows.

```powershell
scoop bucket add zettabyte https://github.com/joyahmed/scoop-bucket
scoop install zettabyte/velkrys
```

| App | What it does |
|---|---|
| [Velkrys](https://github.com/joyahmed/velkrys) | A fast file explorer with real tabs, 100,000-file folders and instant search. Formerly Trove. |

Already have Trove? It was renamed to Velkrys. Switch with:

```powershell
scoop uninstall trove
scoop install zettabyte/velkrys
```

Your settings and tabs move over by themselves the first time Velkrys starts. The old `trove` manifest sits in `deprecated/` and gets no updates.