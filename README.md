# Moixódex

Your bird log, with photos and pixel sprites by [@regulus_ignicapilla](https://www.instagram.com/regulus_ignicapilla/).
*Moixó* is Catalan for "little bird".

## Estructura

- `index.html`: la web (estil i codi).
- `data/birds.js`: les dades dels ocells, un ocell per línia.
- `data/land.js`: contorns dels països per al mapa de "La meva dex".
- `img/sprites/NNN.png` (i `NNN_f.png` per a la femella), `img/photos/NNN.jpg`, `img/maps/NNN.png`.

## Afegir un ocell

1. Posa els fitxers d'imatge a `img/` amb el número de l'ocell.
2. Afegeix una línia a `data/birds.js` amb les dades (copia una línia d'un altre ocell com a model).

## Veure-la en local

Obre `index.html` directament al navegador, o des d'aquesta carpeta: `python3 -m http.server` i ves a http://localhost:8000.

## Publicar a GitHub Pages

Puja tota la carpeta a un repositori i, a Settings > Pages, tria la branca `main` i la carpeta arrel.
