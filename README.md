# Bonairian

Interactieve kaart van Bonaire — snorkelplekken, restaurants, hotels, bezienswaardigheden en activiteiten op één pagina.

🌐 **Live:** https://bonairian.com

## Stack

- Single static HTML (`index.html`)
- [Leaflet.js](https://leafletjs.com/) voor de interactieve kaart
- CartoDB Voyager + Esri World Imagery (satelliet) als tegellagen
- Geen build, geen dependencies — gewoon deployen

## Deployment

Automatisch via Vercel bij iedere `git push` naar `main`.

## Lokaal previewen

```bash
# Optie 1: open direct in browser
open index.html

# Optie 2: simpele lokale server (Python)
python3 -m http.server 8000
# → http://localhost:8000
```

## POI's bewerken

Alle locaties staan in de `POIS` array in `index.html`. Elke entry heeft:

```js
{
  cat: 'snorkel',                         // categorie
  name: 'Naam van de plek',
  coords: [12.1234, -68.2345],            // [lat, lng]
  desc: 'Korte beschrijving voor de popup.'
}
```

Categorieën: `snorkel`, `restaurant`, `hotel`, `bezienswaardigheid`, `activiteit`.
