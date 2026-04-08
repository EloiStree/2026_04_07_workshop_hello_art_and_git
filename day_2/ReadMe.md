
Grayboxing, no audio 🔇: https://youtu.be/wsBQlPwDZCA

- Documentation sur les composants : https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor  
- Pratique de l’exercice : https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity  
- Export final en GLB : https://github.com/EloiStree/2026_04_07_gdp_charleroi_xr_micro_bit_sensors  

-----------------------

# Blocs de couleur, Greyboxing et capteurs

> Travail sur Git et les branches au sein d’un même projet afin de créer plus de 12 prototypes de capteurs Keyestudio en une journée.

L’objectif de cet atelier est de s’entraîner davantage à Git et à la gestion de branches dans Unity 3D.  
Il prépare également au futur atelier sur Godot sur le sujet de modder un simulateur Micro:bit en XR.

<img width="1490" height="1479" alt="image" src="https://github.com/user-attachments/assets/2634fe22-fa4b-4f48-9e9a-6afe717e6c53" />



**ProBuilder** : [🎥](https://youtu.be/IIC3IFKKoFQ?t=4755) | [📑](https://github.com/EloiStree/2024_07_19_workshop_charleroi_xr/issues/167) [📕](https://docs.unity3d.com/Packages/com.unity.probuilder@6.0/manual/index.html)  
**Blocks Color** : [🐙](https://github.com/EloiStree/2024_10_16_upm_blocks_color.git)

**Checklist :**  
- [ ] [Texture](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/174)  
- [ ] [UV](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/220)  
- [ ] [Matériaux](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/175)  
- [ ] [Shaders](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/176)  
- [ ] [Shader Graph](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/65)  
- [ ] [MeshFilter](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/177)  
- [ ] [Mesh](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/67)  
- [ ] [Collisions](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/76)  
- [ ] [Prefab](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/5)  
- [ ] [Nested Prefab](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/4)  
- [ ] [Particule](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/47)  
- [ ] [Un triangle](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/147)  

---

## Objectifs

### Principal : Prototyper des capteurs avec Git  
**Résultat** : Un dépôt GitHub de groupe avec des capteurs Keyestudio en greyboxing visibles sur Quest 3.  

**Compétences** :  
- Pratiquer `git add`, `commit`, `pull`, `push`  
- S’exercer au travail avec des branches  
- Suivre les conventions du groupe  
- Se familiariser avec l’interface GitHub et Unity 3D  

### Secondaire : Se familiariser avec Fork  
**Résultat** : Installer et utiliser Fork.  

**Compétences** :  
- Sauvegarder en local  
- Sauvegarder en ligne  
- Résoudre les conflits  
- Créer une branche  
- Publier une branche sur la branche principale  

**Exercice de Charleroi XR proche 2024** :  
_Faire une île avec ProBuilder_ :  
- ProBuilder pour apprendre les bases :  
  https://github.com/EloiStree/2024_07_19_CharleroiXR/issues/167  
- Travailler dans la même scène par boîte à outils :  
  https://github.com/EloiStree/2024_07_19_CharleroiXR/issues/163  

----------------

# Atelier : Step by step

**Objectif** : Créer un projet Unity avec une boîte à outils liée à Git et y faire un capteur en greybox avec ProBuilder et Blocks Color.  

**Point de passage** : Faire une page de bienvenue GitHub pour votre compte.  

_Note : Nous allons travailler sur un projet XR à partir d’une boîte à outils non XR dans un projet non git._

Pour ne pas attendre plus tard dans l’exercice :  
- [ ] Vérifier que tout le monde utilise la même version d’Unity 3D  
- [ ] Créer un projet Unity dans le dossier `C:/U/Q/`  
  - [ ] `Unity Hub > URP 3D > Local` Nom : `Q_Blocks`  
  - [ ] Vous devriez avoir : `C:/U/Q/Q_Blocksr`

Allons-y !

- [ ] Créer un compte GitHub  
  - [ ] Caractères alphanumériques et caractères spéciaux autorisés.  
  - [ ] `-` et `_` sont tolérés mais vivement déconseillés.  

- [ ] Dites bonjour [ici →](https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity/issues/2)  

- [ ] Créer une page d’accueil  
  - [ ] Créer un répertoire avec le même nom que votre nom d’utilisateur.  
  - [ ] Ajouter un `README.md`  
  - [ ] Éditer le `README.md` en ligne pour vous présenter 😉  
  - [ ] Ajouter vos liens sociaux : LinkedIn, Portfolio…  
    - [ ] Ou pas.  
  - [ ] Aller personnaliser l’icône GitHub de votre compte.  

- [ ] Créez votre premier « site web / blog » avec les GitHub Pages  
  - [ ] Aller dans le répertoire  
  - [ ] Settings > Pages > Configurer une page 😉  
  - [ ] Vous devriez avoir cela maintenant :  
    - https://eloistree.github.io/EloiStree/  

- [ ] Noter que vous pouvez faire de même pour :  
  - [ ] Un portfolio ou votre CV :  
    - [ ] https://github.com/EloiStree/CV  
    - [ ] https://github.com/EloiStree/Video  
      - [ ] https://eloistree.github.io/Video 😅…🐦‍⬛  
      - [ ] https://eloistree.github.io/Video/t--Y65tE-lc  
      - [ ] https://eloistree.github.io/Video/t--Y65tE-lc/ReadMe.md  
  - [ ] Créer une redirection pour votre carte de visite  
    - [ ] https://eloistree.github.io/r/discord  

- [ ] Retourner dans votre projet Unity et l’ouvrir.  

- [ ] Ajoutons l’outil que je vous ai préparé : **Blocks Color**  
  - [ ] Vérifier que Git est bien installé sur votre machine (`cmd` > `git`)  
  - [ ] Top Menu > Window > Package Manager > `+` > Install from Git URL  
  - [ ] Copier : https://github.com/EloiStree/2024_10_16_upm_blocks_color.git  
  - [ ] Vous avez maintenant dans votre projet une palette de couleurs  
    - [ ] Aller voir dans `Project > Packages > Blocks Color > Materials > Lit / Unlit`  

- [ ] Testons cela  
  - [ ] Prendre une scène Unity vide  
  - [ ] Ajouter deux cubes  
  - [ ] Aller dans le dossier **Lit** et déposer le matériau sur un cube  
  - [ ] Aller dans le dossier **Unlit** et déposer le matériau sur l’autre cube  
  - [ ] Aller dans le dossier **Prefab** et faire un drag & drop de **Block Color**  
  - [ ] L’idée ici est de faire du greyboxing mais avec un peu de couleur.  
  - [ ] Tant qu’un projet ne fonctionne pas avec des cubes et des ronds de couleur, pas besoin de plus.

- [ ] Des cubes et des ronds  
  - [ ] Créez-vous un petit dossier avec une scène : `_/NOM_PRENOM/Scenes/HelloLed`  
  - [ ] Allez chercher dans la boîte à capteurs un objet simple à faire avec des cubes et des ronds.  
    - [ ] Ou prenez un [LED rouge](https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor/tree/main/assets/keyestudio/red_led_module) en exemple.  

  - [ ] Créer un point vide dans votre scène **LedRouge**  
  - [ ] Ajouter un quad face vers le haut  
  - [ ] Télécharger une image du composant  
  - [ ] Couper et tourner l’image dans un éditeur d’image  
    - [ ] Éditer pour que l’image soit rectangulaire et multiple de 2 (ex. 256×256)  
  - [ ] Placer l’image dans votre dossier  
  - [ ] Créer un matériau `Mat_RedLedModule`  
  - [ ] Déposer votre image dans **Base Map**  
  - [ ] Déposer le matériau sur le Quad  
  - [ ] Mesurer dans la vraie vie ou trouver les dimensions sur Internet  
    - [ ] Ajouter un point vide avec les dimensions en mm (trouvable en mesurant ou sur un datasheet)  
    - [ ] Garder le Quad à 1×1×1  
  - [ ] Créer un cube que vous aplatissez par-dessus l’image pour avoir le ratio du circuit  
  - [ ] Ajouter une couleur verte **Lit** (ou noir/bleu selon l’objet)  
  - [ ] Ajouter un cylindre par-dessus l’image de la LED  
  - [ ] Donner une couleur rouge **Unlit** à la LED  
  - [ ] Sauvegarder notre objet en prefab  
    - [ ] Créer un dossier **Prefabs**  
    - [ ] Drag & dropper votre objet de la Hierarchy vers le Project  
    - [ ] Vous avez un beau cube bleu 😉

**Sauvegardons votre premier LED rouge dans notre boîte à outils**

- [ ] Aller à la racine du projet Unity (à côté du dossier Library)  
- [ ] Ouvrir le terminal à cet endroit (`CMD` dans la barre d’adresse de l’explorateur Windows)  
- [ ] Copier-coller :  
  ```bash
  git clone https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity.git Packages/2026_04_07_upm_charleroi_xr_art_on_unity
  ```  
- [ ] Revenir dans Unity : vous devriez voir le package `🏭 Charleroi XR Art`  

- [ ] Dans le dossier **Team**, créer un dossier à votre nom  
  - [ ] `NOM_PRENOM` en majuscules alphanumériques  

- [ ] Créer dans votre dossier :  
  - [ ] Un dossier **Scenes** et un dossier **Prefabs**  
    - [ ] **Scenes** = vos scènes de démo  
    - [ ] **Prefabs** = les objets utilisables par l’équipe  
  - [ ] Ajouter un `README.md` dans votre dossier pour vous créditer  
  - [ ] Vous pouvez y ajouter une **ProfilPicture.jpg** pour personnaliser le README  

- [ ] (Option développeur) Créer un dossier **Runtime** avec un Assembly Definition `be.nom.prenom.artxr.Runtime`  
  - [ ] Cliquez sur l’assembly et éditez le **Root Namespace** : `Nom.ArtXR`  

- [ ] Créer un dossier **Feature**  
  - [ ] Créer dedans un dossier `RedLedModule`  
  - [ ] Déposer ce que vous avez créé dans `_/VOTRE_DOSSIER`  
  - [ ] Déplacer votre prefab dans votre dossier `NOM_PRENOM/Prefabs` (pour que l’intégrateur sache où le trouver)  

  **Comparer avec la version exemple que j’ai faite** :  
  `Team/STREE_ELOI/Feature/RedLedModule`  
  https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity/tree/main/Team/STREE_ELOI/Feature/RedLedModule  

- [ ] Il faut maintenant faire : **Add → Commit → Pull → Add → Commit → Pull → Push**  

**Pour les développeurs (terminal) :**  
```bash
git config --global user.name "VOTRE NOM"
git config --global user.email "votre@email.com"
git status
git add .
git commit -m "[3D] Ajout d’une LED rouge"
git pull
git push
```

**Pour les artistes (avec Fork) :**  
- Ouvrir Fork (en anglais)  
- File > Open Repository → `C:\...\Packages\2026_04_07_upm_charleroi_xr_art_on_unity`  
- Local Changes → Stage all  
- Ajouter un message de commit clair  
- Pull → (si conflit → commit de merge) → Push  

> Félicitations ! Vous venez de faire votre premier `Add → Commit → Pull → Push` d’un asset pour le jeu vidéo 🎉

## Les branches

Comme vous l’avez constaté, travailler tous sur la même branche n’est pas très fun.  
Les **branches** permettent de dire : « Je vais travailler dans une pièce à côté, je reviens quand je suis prêt. »

**Dans Fork :**  
- Clic droit sur **Branch** → **New Branch**  
- Donner votre `nom_prenom` → Create  
- Double-clic sur votre branche pour y passer  
- Clic droit sur **main** → **Merge into** votre branche  
- Travailler tranquillement dans votre dossier  
- Stage → Commit → Pull → Push  

La première fois, Git vous demandera de vous authentifier sur GitHub.  
Vous voilà avec votre branche en ligne 🪵  

Maintenant vous pouvez travailler aussi « salement » que vous voulez, c’est chez vous !  

Quand vous avez terminé :  
- Add → Commit → Pull → Push (pour sauvegarder chez vous)  
- Double-clic sur **main** pour revenir sur la branche principale  
- Clic droit sur votre branche → **Merge into main**  
- Pull pour vous mettre à jour  

Si vous avez modifié le fichier d’un autre, il y aura un conflit. Sinon, un petit Pull/Push et c’est bon 😉

On peut aller beaucoup plus loin avec Git, mais c’est suffisant pour aujourd’hui 😅.

## Suite ?

### Essayer d’exporter votre création  
Vous pouvez utiliser ce que vous avez créé ici dans Godot.  
Pour cela, exportez en FBX, ouvrez dans Blender, ajustez et exportez en GLB.  
Ou utilisez tel quel (même si le FBX n’est pas le format le plus beau).

Déposez votre export ici pour le projet Godot :  
https://github.com/EloiStree/2026_04_07_gdp_charleroi_xr_micro_bit_sensors/issues/2

### Explorer ProBuilder  
Unity dispose d’un éditeur 3D simplifié parfait pour les développeurs et débutants.  
Je vous invite à regarder ProBuilder et à refaire le même exercice avec un autre composant :  
- https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/202  
- https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/173  

### Le même exercice (xD)  
L’apprentissage passe par la répétition.  
Refaites l’exercice avec un autre composant !
