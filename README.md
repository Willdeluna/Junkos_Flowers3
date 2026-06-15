# Junkos_Flowers3

Cloud library for Atelier Bloom / Junko's Flowers.

## Folder layout

- `manifest.json` — list of flowers and vases the app can import
- `flowers/` — upload flower `.glb` or `.obj` files here
- `vases/` — upload vase `.glb` or `.obj` files here
- `thumbnails/` — optional preview images
- `builds/` — optional saved HTML builds

## GitHub raw manifest URL

Use this in the app:

```text
https://raw.githubusercontent.com/Willdeluna/Junkos_Flowers3/main/manifest.json
```

## Add a new flower

1. Upload the model to `flowers/`
2. Upload a thumbnail to `thumbnails/` if you have one
3. Add a new item under `"flowers"` in `manifest.json`

Example:

```json
{
  "id": "purpleorchid",
  "name": "Purple Orchid",
  "kind": "bloom",
  "file": "flowers/purpleorchid.glb",
  "thumbnail": "thumbnails/purpleorchid.png"
}
```

## Add a new vase

1. Upload the model to `vases/`
2. Upload a thumbnail to `thumbnails/` if you have one
3. Add a new item under `"vases"` in `manifest.json`

Example:

```json
{
  "id": "glassvase",
  "name": "Glass Vase",
  "kind": "vase",
  "file": "vases/glassvase.glb",
  "thumbnail": "thumbnails/glassvase.png"
}
```
