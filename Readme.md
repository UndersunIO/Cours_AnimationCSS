# CSS Animations Collection

Envie d'animer vos éléments HTML sans avoir à écrire du code JavaScript ?

Ce mini-projet propose une initiation autour des collection d'animations CSS simples et faciles à utiliser.
Chaque animation est définie en tant que classe CSS à appliquer sur vos éléments HTML(ou JSX avec className) pour les animer.

## Liste des animations

Voici la liste des animations de ce projet :

- rotate
- pulse
- bounce
- fade
- slide
- shake
- loading
- colorChange


## Comment ajouter les animations à votre projet
Pour ajouter les animations à votre projet, suivez ces étapes :

- Lié votre fichier CSS dans votre projet.
- Ajoutez le code CSS des animations que vous souhaitez utiliser (voir la section "Animations en détail" ci-dessous).
- Appliquez la classe CSS correspondante à l'élément HTML(ou JSX) que vous souhaitez animer.
- Jouer avec les animations !


## Animations en détail (2 premières animations)
### rotate
Cette animation permet de faire tourner un élément HTML(ou JSX) sur lui-même.

html
Copy code
<div class="rotate">Element avec rotation</div>

css
Copy code
.rotate {
  animation: rotate 2s linear infinite;
}

@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

### pulse
Cette animation permet de faire clignoter un élément HTML(ou JSX) en l'agrandissant et en le rétrécissant.

html
Copy code
<div class="pulse">Element avec clignotement</div>

css
Copy code
.pulse {
  animation: pulse 1s infinite;
}

@keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.2);
  }
  100% {
    transform: scale(1);
  }
}


## ressources
https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Animations/Using_CSS_animations
https://developer.mozilla.org/fr/docs/Web/CSS/@keyframes



Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le redistribuer selon les termes de la licence MIT.

