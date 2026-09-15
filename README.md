# Projet : AMG d'horreur

> Un ARG d'horreur et d'enquête policière interactif.


##  1. Le Jeu Envisagé (Concept Global)

### Synopsis
Vous incarnez un enquêteur ou un consultant externe affecté à une affaire non résolue au sein d'un commissariat sous tension. Un meurtre vient d'avoir lieu, revendiqué à demi-mot par une personne anonyme sur le dark web. Pour lever le voile sur cette affaire, vous devez croiser les preuves matérielles, les archives institutionnelles, les traces numériques de la victime et les indices disséminés par le tueur en série.

### Gameplay & Piliers
Le jeu adopte une approche **ARG transmédia** : l'enquête se déroule à la fois dans l'interface du commissariat et à travers des sites et réseaux sociaux externes (sites clandestins, codes cachés, réseau comme insta ou X).

* **Atmosphère :** Thriller psychologique, ambiance glauque et oppressante, horreur analogique/numérique.
* **Mécaniques clés :**
  * **Observation minutieuse :** Détecter des anomalies dans des photos, des métadonnées ou des arrière-plans.
  * **Croisement de données :** Comparer les alibis, les heures de publication et les rapports médico-légaux.
  * **Cryptographie & Fouille web :** Résoudre des énigmes pour accéder à des pages protégées ou contourner des verrous de sécurité.



## 2. Le Site Compagnon

Le site web compagnon sert de passerelle immersive pour les joueurs.

### 1. Vitrine & Hub d'Immersion
* **Page d'accueil narrative :** Entrée en scène dans l'ambiance du commissariat avec présentation du contexte de l'enquête.
* **Sélection d'affaires / chapitres :** Déblocage progressif des dossiers au fil de la progression.

### 2. Carte Interactive du Crime (Live Map)
* Carte  de la ville répertoriant les scènes de crime, les résidences des suspects, les derniers check-ins sur les réseaux sociaux et les caméras de surveillance.

### 3. Espace Enquêteur
* Sauvegarde de l'avancement de la partie et synchronisation en direct.
* Carnet de notes interactif avec inventaire des preuves collectées (documents PDF, enregistrements audio, captures d'écran décryptées).


## 3. Stack Technique Envisagée

* **Front-end :** Framework moderne réactif (React / Next.js ou Vue.js) pour la gestion fluide du tableau d'enquête (glisser-déposer, liaisons SVG/Canvas) et des fenêtres simulées.
* **Back-end :** Node.js / Symfony / Python pour la gestion de l'état du jeu, la validation des énigmes et l'API de classement.
* **Base de données :** Base relationnelle (MySQL) pour la progression des joueurs et les logs d'enquête.
