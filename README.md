# AeroQuizz ✈️

AeroQuizz est un jeu de culture aéronautique en français, conçu comme un site statique et publiable gratuitement avec GitHub Pages.

## Fonctionnalités
- Trois modes : Identification, Mode expert et Contre-la-montre.
- Questions à choix multiples, indices, explications après réponse et progression.
- Score, séries de bonnes réponses, bonus de rapidité et écran de résultats.
- Record personnel sauvegardé dans le navigateur via `localStorage`.
- Interface responsive pour ordinateur et mobile.
- Aucun framework ni installation nécessaire.

## Publier sur GitHub Pages
1. Crée un dépôt sur https://github.com/new, par exemple `aeroquizz`.
2. Décompresse cette archive et ajoute `index.html` et `README.md` à la racine du dépôt.
3. Dans le dépôt, ouvre **Settings → Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
5. Après quelques instants, le site sera accessible à l'adresse indiquée dans la section Pages, généralement `https://TON-PSEUDO.github.io/aeroquizz/`.

## Personnaliser
Les questions sont dans le tableau `questions` du fichier `index.html`. Les questions du mode expert sont dans `expertQuestions`. Tu peux modifier les noms, les indices, les explications et les propositions directement dans ces tableaux.

## Note sur les visuels
Cette première version utilise des symboles illustratifs, pas des photographies d'appareils. Pour un vrai jeu d'identification visuelle, remplace les symboles par des photos correctement identifiées et vérifie les licences de réutilisation de chaque image.


## Photographies d'appareils
Le jeu recherche les photographies au fil de la partie via l'API de Wikimedia Commons, avec une recherche liée au modèle de l'avion. Les crédits ouvrent la page source de chaque image. Une connexion Internet est nécessaire pour charger les photographies; si le service est indisponible, le quiz reste jouable avec un symbole de secours. Les licences et les métadonnées peuvent varier selon chaque fichier : consulte la page source avant toute réutilisation hors du jeu.
