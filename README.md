> https://maximlopez.github.io/404-Page/
git 
# Page 404
<p>Une page "Erreur 404".</p>

## Langages utilisés ? 
* HTML 5
* CSS3
* SASS 

## Qui est l'auteur ? 
Ce projet a été réalisé par Maxim Lopez, alors en formation chez BeCode.<br>
[Voir le GitHub](https://github.com/maximlopez)

## De quoi s'agit-t-il ? 
Il s'agit d'une page 404 réalisé avec de l'HTML5 et du CSS3. Le projet utilise du SASS compilé pour minifier le CSS.<br>

## Quanda t-il été réalisé ? 
Ce projet a été réalisé le 24 avril 2019. Il a fallu une heure pour le réaliser<br>

## Dans quel cadre ce projet a vu le jour ? 
Il s'agit d'un exercice réalisé lors de la période de "Prairie" chez BeCode.<br>

## Voir le projet ?
Il est possible de voir le projet grâce à GitHub Pages.<br>
[Voir la page](https://maximlopez.github.io/404-Page/)

## Progression ? 
Le projet est terminé, cependant des versions annexes pourraient arriver, suivant la progression de ma formation, d'un éventuel nettoyage du code, ou même de futur commentaire afin de préciser mon code.<br>

## Que contient t'il ? 
La page 404 contient une image de fond, un Gif et un bouton animé.<br>

## Comment le récupérer ? 
Il suffit de cloner le dépôt ou de télécharger le zip de ce dernier. Il est également possible de le voir en ligne.<br>

## Présentation du code 

* Affichage de l'HTML

``` markdown

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" type="text/css" href="./assets/css/style.min.css">
    <link rel="shortcut icon" href="./assets/img/favicon.ico" type="image/x-icon">
    <title>404 Page</title>
</head>

<body>
    <!-- Main -->
    <main>
        <!-- Image -->
        <img src="./assets/img/404.webp" alt="Animation 404" class="gif">
        <!-- Titre de la page -->
        <h1>Ici n'est pas la page que tu cherches.</h1>
        <!-- Bouton retour GitHub -->
        <p> 
            <a href="https://github.com/MaximLopez" target="_blank" rel="noopener noreferrer">Retour</a>
        </p>
    </main>
    <!-- Main-Fin -->
</body>

</html>
<!-- Page web réalisé par Maxim Lopez -->

```

* Affichage du CSS

``` markdown
@charset "UTF-8";
/* Réglage du texte */
h1 {
  font-size: 30px;
}

h1, p {
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  color: white;
}

p {
  font-size: 18px;
}

.credits {
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  color: white;
  font-size: 12px;
}

/* Réglage de la page */
body {
  background-image: url("../img/background.jpg");
}

/* Réglage du Gif */
.gif {
  width: 30%;
  padding-bottom: 1%;
  display: block;
  margin: auto;
  margin-top: 9%;
}

/* Réglage de l'animation */
:root {
  --mainColor: #ff9800;
}

a {
  background: -webkit-gradient(linear, left top, left bottom, from(var(--mainColor)), to(var(--mainColor)));
  background: -webkit-linear-gradient(top, var(--mainColor) 0%, var(--mainColor) 100%);
  background: -o-linear-gradient(top, var(--mainColor) 0%, var(--mainColor) 100%);
  background: linear-gradient(to bottom, var(--mainColor) 0%, var(--mainColor) 100%);
  background-position: 0 100%;
  background-repeat: repeat-x;
  background-size: 4px 4px;
  color: white;
  text-decoration: none;
  -webkit-transition: background-size .2s;
  -o-transition: background-size .2s;
  transition: background-size .2s;
}

a:hover {
  background-size: 4px 50px;
}

```