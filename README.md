# hupueng-media

Public files for the หูผึ่ง (@hupueng) Shorts pipeline.

- Videos: one GitHub Release per clip, tag = episode id → `https://github.com/rtliz/hupueng-media/releases/download/<id>/<id>.mp4`
- `videos/<id>.json`: episode script, sources, captions
- `plan.json`: content plan read by the rtliz-cms dashboard

mp4 files are never committed (`.gitignore`): git keeps every version forever, Releases do not grow the repo.
