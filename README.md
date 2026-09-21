# Heated Rivalry S2 · le décompte

Page de fans non officielle : le compte à rebours de Damien & Romain avant la saison 2 de Heated Rivalry.

Site statique, un seul `index.html`. Aucune image de la série : tout est dessiné en SVG, CSS et canvas.

## Changer la date

En haut du script, dans `index.html` :

```js
var SORTIE = {
  iso: '2027-04-01T06:00:00+02:00',
  estimee: true
};
```

Mettre l'instant exact de la sortie dans `iso` (avec le décalage horaire), puis passer `estimee` à `false` quand la date officielle est connue.

## Aperçu local

```bash
python3 -m http.server 4173
```
