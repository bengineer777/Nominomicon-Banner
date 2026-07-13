# Nominomicon Banner

Remote message catalog for the Nominomicon Android app.

Edit [`heckles.json`](heckles.json) to change the banner rotation. Each entry needs a unique `id`
and nonblank `text`. Keep the document valid JSON; the app retains its last valid catalog whenever
an update is unavailable or malformed.

The app reads the catalog from:

```text
https://raw.githubusercontent.com/bengineer777/Nominomicon-Banner/main/heckles.json
```
