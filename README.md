# Super_Edu

Plateforme web educative orientee vers l'apprentissage, la collaboration academique et l'accompagnement des etudiants.

## Sommaire

- [Objectif](#objectif)
- [Public cible](#public-cible)
- [Fonctionnalites](#fonctionnalites)
- [Apercu des pages](#apercu-des-pages)
- [Structure du projet](#structure-du-projet)
- [Demarrage rapide](#demarrage-rapide)
- [Utilisation](#utilisation)
- [Technologies](#technologies)
- [Organisation du contenu](#organisation-du-contenu)
- [Roadmap](#roadmap-proposition)
- [Contribution](#contribution)
- [Licence](#licence)

## Objectif

Super_Edu a pour but d'aider les etudiants a renforcer leurs competences academiques et professionnelles via une experience numerique moderne.

## Public cible

- Etudiants en formation initiale ou continue.
- Enseignants souhaitant partager des contenus et collaborer.
- Mentors/encadrants accompagnant les parcours de progression.

## Fonctionnalites

- Parcours de contenu pedagogique (videos, cours, supports).
- Espaces de collaboration entre etudiants et enseignants.
- Accompagnement autour du developpement personnel et professionnel.
- Integration d'un assistant IA pour guider l'apprentissage.

## Apercu des pages

- `index.html` : point d'entree principal de l'interface.
- `Wpages/certification.html` : informations liees aux certifications.
- `Wpages/conseils.html` : conseils et recommandations.
- `Wpages/mentor IA.html` : espace dedie au mentor IA.
- `Wpages/prototype.html` : version/prototype d'interface.
- `Wpages/weeeelcom.html` : page d'accueil alternative.

## Structure du projet

```text
Super_Edu/
|-- index.html
|-- README.md
|-- config/
|-- imgs/
|-- media/
|-- src/
|   |-- presentaions/
|   `-- video/
`-- Wpages/
```

## Lancer le projet en local

Ce projet est statique (HTML/CSS/JS) et ne necessite pas de build complexe.

## Demarrage rapide

1. Cloner le depot.
2. Ouvrir le dossier dans VS Code.
3. Lancer `index.html` avec une extension de serveur local (exemple : Live Server) ou ouvrir directement le fichier dans le navigateur.

Option via terminal (Python, si disponible) :

```bash
python -m http.server 8080
```

Puis ouvrir : `http://localhost:8080`

## Utilisation

1. Ouvrir la page d'accueil (`index.html`).
2. Naviguer vers les pages de contenu dans `Wpages/`.
3. Explorer les sections pedagogiques (videos, conseils, certifications, mentor IA).
4. Adapter les textes/styles dans les fichiers HTML/CSS selon vos besoins.

## Technologies

- HTML5
- CSS3
- JavaScript (vanilla)
- Font Awesome (CDN)
- Google Fonts (CDN)

## Organisation du contenu

- `imgs/` : images et illustrations.
- `media/` : assets medias (audio/video/documents selon usage).
- `src/video/` : ressources video source.
- `src/presentaions/` : ressources de presentation (nom de dossier conserve tel quel dans le projet).
- `config/` : fichiers de configuration additionnels.
- `Wpages/` : pages web secondaires et prototypes.

## Roadmap (proposition)

- Ajouter une architecture frontend modulaire.
- Connecter les contenus a une API backend.
- Mettre en place un systeme d'authentification.
- Ajouter des tests de non-regression UI.

## Contribution

Les contributions sont bienvenues.

1. Fork du projet
2. Creation d'une branche de fonctionnalite
3. Commit des modifications
4. Ouverture d'une pull request

Bonnes pratiques recommandees :

- Garder les commits atomiques et explicites.
- Verifier l'affichage desktop et mobile avant PR.
- Eviter les regressions visuelles sur `index.html` et les pages dans `Wpages/`.

## Licence

Ce projet est distribue sous tri-licence au choix :

- GPL-3.0-or-later
- MIT
- Apache-2.0

Voir les fichiers `LICENCE`, `LICENSE-GPL-3.0-or-later`, `LICENSE-MIT` et `LICENSE-APACHE-2.0`.
