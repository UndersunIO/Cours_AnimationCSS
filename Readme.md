# CSS Animations Collection

Envie d'animer vos éléments HTML sans avoir à écrire du code JavaScript ?

Ce mini-projet propose une collection d'animations CSS simples et faciles à utiliser.
Chaque animation est définie en tant que classe CSS que vous pouvez appliquer à vos éléments HTML(ou JSX avec className) pour les animer.

## Liste des animations

Voici la liste des animations disponibles :

1. Rotate (rotation)
2. zoom in (zoom avant)
3. Zoom out (zoom arrière)
4. bounce (rebond)
5. swing (balancement)
6. translateY (translation verticale)
7. translateX (translation horizontale)
8. colorChange (changement de couleur)
9. scrollX (défilement horizontal)
10. scrollY (défilement vertical)

## Comment utiliser les animations

- Lié le fichier css dans votre fichier html ou jsx
- Ajouter la classe css correspondante à l'élément que vous souhaitez animer

- modifier les paramètres de l'animation dans le fichier css pour les adapter à vos besoins
- modifier la fonctionnalité css @keyframes pour modifier l'animation, ce sont toute les etapes de lanimation personnalisable.


Comment ajouter les animations à votre projet
Pour ajouter les animations à votre projet, suivez ces étapes :

Copiez le code CSS des animations que vous souhaitez utiliser (voir la section "Animations en détail" ci-dessus) et collez-le dans votre fichier CSS.

Ajoutez la classe CSS correspondante à l'élément HTML que vous souhaitez animer.

Voici un exemple d'utilisation de l'animation de rotation :

html
Copy code
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exemple d'animation de rotation</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="rotate">Element avec rotation</div>
</body>
</html>

## ressources
https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Animations/Using_CSS_animations
https://developer.mozilla.org/fr/docs/Web/CSS/@keyframes



Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le redistribuer selon les termes de la licence MIT.

