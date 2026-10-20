# bb_icon – Icon-Set für Home Assistant

Eigenes Icon-Set mit dem Präfix `bb:` für die Home-Assistant-Instanzen von Bewegte Bilder.

![Übersicht](preview.png)

## Icons

| Name | Icon |
|---|---|
| `bb:douser-closed` | <img src="svg/douser-closed.svg" width="32"> |
| `bb:douser-open` | <img src="svg/douser-open.svg" width="32"> |
| `bb:atmos-off` | <img src="svg/atmos-off.svg" width="32"> |
| `bb:grading` | <img src="svg/grading.svg" width="32"> |
| `bb:protools` | <img src="svg/protools.svg" width="32"> |
| `bb:edit` | <img src="svg/edit.svg" width="32"> |
| `bb:cinema` | <img src="svg/cinema.svg" width="32"> |
| `bb:cinema-1` | <img src="svg/cinema-1.svg" width="32"> |
| `bb:cinema-2` | <img src="svg/cinema-2.svg" width="32"> |
| `bb:cinema-3` | <img src="svg/cinema-3.svg" width="32"> |
| `bb:scan` | <img src="svg/scan.svg" width="32"> |
| `bb:subtitle` | <img src="svg/subtitle.svg" width="32"> |
| `bb:bewegtebilder` | <img src="svg/bewegtebilder.svg" width="32"> |

`bb:bewegtebilder` ist zweistufig (`secondaryPath`): Der zweite Teil wird von Home Assistant halbtransparent gezeichnet.

## Einbinden

1. `bb-icons.js` in Home Assistant als Dashboard-Ressource vom Typ **JavaScript-Modul** eintragen
   (Einstellungen → Dashboards → Ressourcen), z. B. nach `/config/www/bb-icons.js` kopieren und `/local/bb-icons.js?v=1` eintragen.
2. Browser hart neu laden.
3. Icons wie gewohnt verwenden, z. B. `icon: bb:grading`.

## Aufbau

- `bb-icons.js` – das Icon-Set, so wie es in Home Assistant geladen wird
- `svg/` – jedes Icon einzeln als SVG

## Hinweis

`atmos-off`, `grading` und `protools` basieren auf Logos der jeweiligen Hersteller (Dolby, Blackmagic Design, Avid)
und sind nur für den internen Einsatz gedacht. Die Markenrechte liegen bei den Herstellern.
