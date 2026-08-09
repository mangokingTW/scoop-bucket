# scoop-bucket

A [Scoop](https://scoop.sh) bucket for
[ImeModePersistence](https://github.com/mangokingTW/ImeModePersistence) — a
Windows tray utility that carries your IME's native/alphanumeric mode across
windows and binds programs to a fixed input language, including anti-cheat
fullscreen games.

## Install

```powershell
scoop bucket add mango https://github.com/mangokingTW/scoop-bucket
scoop install ImeModePersistence
```

## Update

```powershell
scoop update ImeModePersistence
```

The manifest carries `checkver`/`autoupdate`, and an Excavator workflow refreshes
it automatically when a new release ships.

## Notes

- **Unsigned.** SmartScreen or antivirus may warn. Source, build, and per-release
  build provenance are public — verify a download with
  `gh attestation verify <file> --repo mangokingTW/ImeModePersistence`.
- **Anti-cheat games run elevated.** Use *Restart as administrator* from the tray
  menu so the utility can see and control them.
