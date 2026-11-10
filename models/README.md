# Modèles 3D

Dépose ici un fichier `.glb` par voiture. Dès qu'un fichier est présent, il remplace la silhouette dessinée dans le garage, la fiche et la vignette. Sans fichier, la silhouette reste affichée.

| Voiture | Nom du fichier |
|---|---|
| Audi R8 V10 Performance | `audi-r8.glb` |
| Audi RS5 Sportback | `audi-rs5.glb` |
| Lamborghini Huracán STO | `lamborghini-huracan-sto.glb` |
| Ferrari LaFerrari | `ferrari-laferrari.glb` |
| BMW M3 Competition | `bmw-m3.glb` |
| Rolls-Royce Phantom | `rolls-royce-phantom.glb` |
| Bugatti Chiron Sport | `bugatti-chiron.glb` |
| Porsche 911 GT3 RS | `porsche-911-gt3-rs.glb` |
| Mercedes-AMG G 63 | `mercedes-g63.glb` |
| McLaren 720S | `mclaren-720s.glb` |
| Ferrari SF90 Stradale | `ferrari-sf90.glb` |

## Conseils

- Format `.glb` (glTF binaire), compression Draco acceptée. Vise moins de 10 Mo par voiture, sinon le site sera lent sur téléphone.
- Le modèle est redimensionné et posé au sol automatiquement. L'avant doit pointer vers +Z (le standard glTF). Si une voiture est de travers, ajoute `modelRot: Math.PI/2` (ou `Math.PI`) sur sa ligne dans `CARS` dans `index.html`.
- Pour que le configurateur puisse changer la teinte, le matériau de la carrosserie doit contenir `paint` ou `body` dans son nom.
- Vérifie la licence de chaque modèle (par exemple CC-BY sur Sketchfab, qui demande de citer l'auteur) avant de mettre le site en ligne.
