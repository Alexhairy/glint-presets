# Glint presets

The preset list shown on the Library page of Glint, a colour adjustment app for Windows.

Glint downloads `presets.json` from this repository when you open its Library page. Nothing is sent
except the download request itself.

## Suggesting a preset
Make a profile in Glint, right-click it, choose **Copy share code**, and send the code with a name,
the game it suits and a one-line description. Presets are picked by hand before they appear here.

## Format
```json
{
  "format": 1,
  "presets": [
    { "name": "Vivid", "game": "Any game", "author": "Glint", "about": "One line.", "code": "GL-..." }
  ]
}
```
