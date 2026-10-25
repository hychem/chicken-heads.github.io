Chicken Heads For Human Consumption — Site web statique
Site vitrine d'une startup algérienne (incubateur de l'Université de Guelma) qui exporte des têtes de poulet vers l'Asie. Le site reproduit le site d'origine : mêmes textes, mêmes couleurs, même organisation.
Contenu
Le site tient en une seule page HTML qui affiche 5 vues selon le menu :
Vue	Contenu
Home	Bannière, Welcome, Insights & Updates (Our Customers, Quality First), 2 articles (25 et 22 déc.)
About us	Présentation, mission, Cultural Connection
Products	Fiche produit (10 $ / 1 kg), Key Features, tableau nutritionnel
Contact Us	Formulaire « Request A Call Back »
Subscription	Offre d'abonnement (2 à 6 semaines)
Le pied de page (réseaux sociaux, adresse, téléphone, email, newsletter) apparaît sur toutes les vues.
Fichiers
```
chicken-heads-clone.html   page unique : HTML + CSS + JavaScript
img/
  hero.jpg                 fond de la bannière d'accueil
  logo-dark.png            logo pour fond sombre (accueil)
  logo-coral.png           logo pour bandeau corail (autres pages)
  dish.jpg                 plat de têtes de poulet (Welcome)
  plate.jpg                assiette de riz (Insights & Updates)
  person1.jpg, person2.jpg photos des deux articles
  machine1.jpg, machine2.jpg  photos de la page About us
  video.jpg                image de la section Cultural Connection
  pack.jpg                 photo du paquet (Products)
```
Technique
Aucun framework ni étape de build : HTML, CSS et JavaScript simples.
Polices Google Fonts : Poppins, Raleway, Dancing Script.
Navigation par JavaScript avec les ancres `#home`, `#about`, `#products`, `#contact`, `#subscription`.
Adapté au mobile, avec des colonnes qui passent sur une seule ligne sous 820 px.
Palette : corail `#FF6262`, violet `#B83BA0`, rouge `#FF0000`, orange `#F7920C`, pied de page `#2B2B2B`. Elle est définie dans `:root` en haut du CSS.
Modifier le site
Textes : modifier directement le HTML de la vue concernée.
Images : remplacer les fichiers de `img/` en gardant les mêmes noms. Pour une bonne netteté, utiliser des images d'au moins 800 px de large (1600 px pour `hero.jpg`).
Prix et tableau nutritionnel : vue Products. Remplacer les valeurs par une analyse de laboratoire.
Coordonnées : dans le pied de page (adresse, téléphone, email).
Mise en ligne
La page est un fragment sans `<html>`, `<head>` ni `<body>`. Pour l'héberger sur un serveur classique (GitHub Pages, Netlify, hébergeur web), enveloppez-la dans une page complète :
```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- placer ici le <title>, les <link> et le <style> du fichier -->
</head>
<body>
  <!-- placer ici le reste du fichier, <script> compris -->
</body>
</html>
```
Puis déposer ce fichier et le dossier `img/` au même endroit sur le serveur.
À faire avant de publier
Formulaires : le formulaire de contact et celui de la newsletter n'envoient rien. Les relier à un service (Formspree, Netlify Forms, etc.) ou à votre propre serveur.
Chiffres et avis : « Join over 498 happy customers » et la phrase sur les clients satisfaits viennent du site d'origine. Ne les garder que s'ils sont vrais.
Tableau nutritionnel : valeurs non sourcées, à faire vérifier par un laboratoire.
Droits des images : les images actuelles viennent de captures d'écran et sont de petite taille. Les photos de personnes et de machines viennent probablement de tiers. Les remplacer par vos propres photos ou par des images libres de droits.
Conformité export : ajouter les certifications obtenues (halal, certificat vétérinaire, HACCP).
Réseaux sociaux : les icônes du pied de page ne mènent nulle part. Ajouter vos liens.
Nom du fondateur : vérifier l'orthographe de « Mr Ghoul Abdallah » (lu sur une capture).
Texte du logo : le texte circulaire du logo est celui de l'image d'origine et peut être illisible.
Contact
Adresse : Incubator, University of Guelma, 8 May 1945
Téléphone : +213 697729408
Email : chicken-heads-human-consumption@gmail.com
© 2024 Chicken Heads For Human Consumption Inc.
