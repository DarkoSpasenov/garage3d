# Onze, showroom 3D

Site vitrine d'un garage de voitures de sport, avec un showroom en 3D temps réel (Three.js).

- Garage 3D : sol miroir, plafond lumineux hexagonal, onze places numérotées.
- Glisser pour parcourir le garage, cliquer sur une voiture pour l'ouvrir.
- Fiche voiture : vue 3D qui tourne, onglets Louer / Acheter / Configurer (teinte, jantes, étriers), calcul du prix de location et de la mensualité.
- Collection filtrable, formules, formulaire de contact (démo, rien n'est envoyé).
- Responsive téléphone.

Les voitures et les marques sont fictives, les modèles 3D sont générés dans le code.

## Lancer en local

Un seul fichier, `index.html`. Three.js est chargé depuis jsDelivr, donc il faut un serveur local et une connexion internet :

```
python3 -m http.server 8000
```

puis ouvrir http://localhost:8000.

## Mettre en ligne

GitHub Pages : Settings → Pages → Deploy from a branch → `main` / root.
