
- Documentation sur les composants: https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor
- Pratique de l exercice: https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity
- Export final en GLB: https://github.com/EloiStree/2026_04_07_gdp_charleroi_xr_micro_bit_sensors

-----------------------

# Blocs de couleur, Greyboxing et capteurs

> Travail sur Git et les branches au sein d’un même projet afin de créer plus de 12 prototypes de capteurs Keyestudio en une journée.

L’objectif de cet atelier est de s’entraîner davantage à Git et à la gestion de branches dans Unity3D.    
Il prépare également au futur atelier sur Godot sur le sujet de modder un simulateur Micro:bit en XR.  

<img width="1490" height="1479" alt="image" src="https://github.com/user-attachments/assets/2634fe22-fa4b-4f48-9e9a-6afe717e6c53" />

Vidéo : -  
Solution : -  


Pro-Buidler: [🎥](https://youtu.be/IIC3IFKKoFQ?t=4755) | [📑](https://github.com/EloiStree/2024_07_19_workshop_charleroi_xr/issues/167) [📕](https://docs.unity3d.com/Packages/com.unity.probuilder@6.0/manual/index.html) 
Blocks Color: [🐙](https://github.com/EloiStree/2024_10_16_upm_blocks_color.git)   
Checklist:
- [ ] [textures](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/174)
- [ ] [UV](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/220)  
- [ ] [matériaux](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/175)
- [ ] [shaders](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/176)
- [ ] [Shader Graph](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/65) 
- [ ] [MeshFilter](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/177) 
- [ ] [Mesh](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/67)  
- [ ] [collisions](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/76)
- [ ] [Prefab](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/5 )
- [ ] [Nested Prefab](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/4)
- [ ] [Particule](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/47)
- [ ] [Un triangle](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/147)
          

---

## Objectifs

### Principal : Prototyper des capteurs avec Git

* **Résultat** : Un dépôt GitHub de groupe avec des capteurs Keyestudio en greyboxing visibles sur Quest 3
* **Compétences** :
  * Pratiquer `git add`, `commit`, `pull`, `push`
  * S’exercer au travail avec des branches
  * Suivre les conventions du groupe
  * Se familiariser avec l’interface GitHub et Unity3D

### Secondaire : Se familiariser avec Fork

* **Résultat** : Installer et utiliser Fork
* **Compétences** :
  * Sauvegarder en local
  * Sauvegarder en ligne
  * Résoudre les conflits
  * Créer une branche
  * Publier une branche sur la branche principale



**Exercice de Charleroi XR proche 2024**:  
_Faire une ile avec ProBuilder_:  
- Pro Builder pour apprendre les bases:
  - https://github.com/EloiStree/2024_07_19_CharleroiXR/issues/167
- Travailler dans la meme scene par boite a outils
  - https://github.com/EloiStree/2024_07_19_CharleroiXR/issues/163

----------------


# Atelier: Step by step

Objectif: Creer un projet Unity avec un boite a outil lier a git et y faire un senseur en Greybox avec ProBuilder et Blocks Color.
Point de passage: Faire un page de bienvenu GitHub pour votre compte.  

_Note: Nous allons travaillez sur un projet XR a partir d'une boite a outils non XR dans un projet non git_

Pour pas attendre plus tard dans l'exercice:
- [ ] Verifier que tout le monde utiliser le meme version Unity3D
- [ ] Creer un project Unity dans le dossier `C:/U/Q/`
  - [ ] `Unity Hub > URP 3D > Local`  Nom: `Q_BlocksProBuilder` 
  - [ ] Vous deviz avoir: `C:/U/Q/Q_BlocksProBuilder`

Allons y allonzo :
- [ ] Creer un compte GitHub
  - [ ] AlphaNumeric sand character speciaux.
  - [ ] `-` `_` tolerer mais vivement deconseiller.
- [ ] Dit bonjour [ici ->](https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity/issues/2)
- [ ] Creer une page d acceuil
  - [ ] Creer un repertoire avec le meme nom que votre nom d utilisateur.
  - [ ] Ajouter y  un ReadMe.md
  - [ ] Editer les ReadMe.md en ligne pour vous presenter ;)
  - [ ] Ajouter vos liens sociaux: LinkedIn, Portfolio ...
    - [ ] Ou pas.
  - [ ] Aller personnaliser l icon GitHub de votre compte.
- [ ] Creez votre premiet "site web/blog" avec les page de GitHub
  - [ ] Aller dans le repertoir
  - [ ] Settings > Pages > Configurer une page 😉
  - [ ] Vous devriez avoir cela maintenant:
    - https://eloistree.github.io/EloiStree/
- [ ] Noter que vous pouvez faire de meme pour:
  - [ ] Un portfolio ou votre CV:
    - [ ] https://github.com/EloiStree/CV
    - [ ] https://github.com/EloiStree/Video
      - [ ] https://eloistree.github.io/Video 😅...🐦‍⬛
      - [ ] https://eloistree.github.io/Video/t--Y65tE-lc
      - [ ] https://eloistree.github.io/Video/t--Y65tE-lc/ReadMe.md
  - [ ] Creer une redirection pour votre carte de visit
    - [ ] https://eloistree.github.io/r/discord

 Allons 
- [ ] Retournon dans votre project Unity et ouvrer le.
- [ ] Ajoutons y un outils que je vous ai preparer: Block
  - [ ] Verifier que Git est bien sur votre machine "cmd" > git
  - [ ] Top Menu > Window > Package manager > `+` > Install un Git URL
  - [ ] Copier: https://github.com/EloiStree/2024_10_16_upm_blocks_color.git
  - [ ] Vouas avez maintenant dans votre projet une palette de couleur
    - [ ] Aller voir a `Project > Packages > Blocks Color` `Materisl Lit/Unlit`
  - [ ] Testons cela
    - [ ] Prenons une scene Unity vide
    - [ ] Ajoutons deux cubes
    - [ ] Aller dans le dossier lit et deposer le material sur le cube
    - [ ] Aller dans le dossier unlit et deposer le material sur le cube
    - [ ] Aller dans le dossier Prefab et drag and dropper Block Color
    - [ ] L'idee ici c est de faire des greybox mais avec un peu de couleur.
    - [ ] Tant qu'un project ne fonctionne pas avec des cubes et des ronds de couleur pas besoin de plus.
- [ ] Des cubes et des ronds.
  - [ ]  Creer vous un petit dossier avec une scene _/NOM_PRENOM/Scene/HelloLed
  - [ ]  Allez chercher dans la boite a senseur un object simple a faire avec des cubes et des ronds.
    - [ ] Ou prenez un [led rouge](https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor/tree/main/assets/keyestudio/red_led_module) en example
  - [ ]  Creer un point vite dans votre scene LedRouge
    - [ ] Ajouter un quad face vers le haut
    - [ ] Telecharger une image du composant
    - [ ] Couper et tourner l image and un editeur d image
      - [ ] Editer pour que l image soit rectangulaire multiple de 2 (256x256)
    - [ ] Placer l image dans votre dossier
    - [ ] Creer un material `Mat_RedLedModule`
    - [ ] Deposer votre image dans `Base map`
    - [ ] Deposer le material sur le Quad
    - [ ] Measurer dans la vrai vie ou trouver les dimensions sur internet
      - [ ] Ajouter un point vide avec les dimensions en mm
        - [ ] Trouvable en mesurant ou sur un 'Datashseet'
      - [ ] Garder le Quad a 1x1x1
    - [ ] Creer un cube que vous applatiser par dessus l image avoir le ratio du circuit
    - [ ] Ajouter y un couleur verte `lit` ( ou noir/bleu selon lobject)
    - [ ] Ajouton un cylindre par dessus l image de la led
    - [ ] Donnons une couleur rouge `unlit` a la led
    - [ ] Sauvons notre object en prefab
      - [ ] Creer un dossier prefab
      - [ ] Drag and dropper votre Object dans la hierarchy a Project
      - [ ] Vous avez un cube blue ;)

Sauvons votre premier led rouge dans notre boite a outils
- [ ] Aller a la racine du projet Unity a coter de Library
- [ ] Ouvrer le terminal a cette endroid la. `CMD` dans le chemain d access window
- [ ] Copier coller:
  - [ ] `git clone https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity.git Packages/2026_04_07_upm_charleroi_xr_art_on_unity`
- [ ] Revener dans Unity et vous deveiez voir dans package `🏭: Charleroi XR Art`
- [ ] Dans Team aller creer un dossier a votre nom
  - [ ] NOM_PRENOM en alphanumeric uppercase
- [ ] Creeons dans votre dossier:
  - [ ] Un dossier: Scene, Prefab
    - [ ] Scene c est vos scene de demo
    - [ ] Prefab les objets utilisables par l equipe
  - [ ] Ajoutons un ReadMe.md dans votre dossier pour vous crediter.
  - [ ] Vous pouvez y ajouter un ProfilPicture.jpg si vous voulez personnalisez le ReadMe.md
  - [ ] Si vous etes developer:
    - [ ] Un Dossier Runtime avec un assembly `be.nom.prenom.artxr.Runtime`
    - [ ] Cela vous creer un petit bulle pour votre code
    - [ ] Clicker sur l assembly et editer le Root Namespace: Nom.ArtXR
- [ ] Creeons un dossier Feature
  - [ ] Creeons y un dosssier RedLedModule
  - [ ] Deponsons y dedans ce que vous avez creer en `_/VOTRE_DOSSIER`
  - [ ] Deplacer votre prefab dans votre dossier NOM_PRENON/Prefab
    - [ ] Histoire que l integrateur puisse savoir ou trouver votre asset.
    - [ ] Comparer avec la version example que j ai fait;
      - [ ] Dans `Team/STREE_ELOI/Feature/RedLedModule`
      - [ ] https://github.com/EloiStree/2026_04_07_upm_charleroi_xr_art_on_unity/tree/main/Team/STREE_ELOI/Feature/RedLedModule
    - [ ] Il faut maintenant faire un Add > commit > pull > Add > commit > pull > push
      - [ ] Aller dans Unity|Packages/2026_04_07_upm_charleroi_xr_art_on_unity
      - Pour Developer: 
        - `cmd` pour ouvrir le terminal
        - `git config --global user.name "YOUR NAME"
        - `git config --global user.email "mail@ngmail.com"
        -  Git demandera de s authentifer au premier `push`
        - `git status` pour voir des changements
        - `git add .` pour ajouter a la prochaine sauvegarde
        - `git status` voir si ca a fonctionner
        - `git commit -m "[3D] Ajoute d une led rouge"` pour sauver localement
        - `git pull` pour se mettre a jour sur vos collegues
        - `git push` Si tout est a jours
        - Regler un conflit si il y en a un
        - Se mettre a jour peut toujours bien changer un fichier ou l autre.
        - `git status` pour voir des changements
        - `git add .` pour ajouter a la prochaine sauvegarde
        - `git status` voir si ca a fonctionner
        - `git commit -m "[3D] Ajoute d une led rouge"` pour sauver localement
        - `git pull` pour se mettre a jour sur vos collegues
        - `git push` Si tout est a jours
      - Pour les artistes:
        - Ouvrer Fork.
        - Passer le en Anglais
        - File > Open Reperitory `C:\...\Packages\2026_04_07_upm_charleroi_xr_art_on_unity`
        - Go in Local Changes
        - Stage all the element
        - Add a commit message: decrivant ce que vous avez faire
        - Clicker sur Pull
        - Si il y a des choses changees.
          - Refait un commit dit de merge
        - CLicker sur Pull
        - Clicker su Push
        
> Felicitation vous venez de faire votre premier `Add commit pull push` ;) d' un asset pour le jeu video🎊 


## Les branches

Comme vous avez pu le constater, Pull Push sur le meme endroit de travail.
C est pas super fun.

Les branches, est le concpet qui revient a dire:
"Je vais travailler dans une piece a coter, je reviens vers vous quand je suis bon"

Dans Fork:
- Click Droit sur `Branch` > `New Branch`
- Donner votre `nom_prenon`  > `Create`
- Double clicker sur `nom_prenom` pour changer de branch
- Click droit sur main > merge into `nom_prenom`
- Merge
- Travailler sur votre dossier
- Local > Stage > Commmit
- Pull > Push
- La premier fois, git vous demandra de vous ententifie depuis le site GitHub
- Et vous voila avec votre bramch en ligne 🪵
- Maintenant vous pouvez travaillez aussi salement que vous voulez.
  - C est votre chez vous.
- Un fois que vous avez fini de creer on veut faire l inverse
- Add commit pull push ( pour sauver chez nous )
- Double click sur main pour aller chez nos collegues
- Clique droit sur `nom_prenom` et Merge into `main`
- Pull pour vous mettre a jour.
- Si vous avez travaillez sur le fichier d un autre il y aura un conflit
- Sinon on se faire un petit pull push et on est bon 😉
  
On peut aller dans du plus compliquer.
Car il y a beaucoup de maniere different de travailler proprement en Git.
Mais c est bon pour aujourd'hui 😅.

## Suite ?

### Essayer d'exporter votre creation

Vous pouvez utiliser ce que vous avez creez ici sur Godot.
Mais pour ca il faut l exporter en FBX, ouvrir en Blender.
Ajuster et l'exporter en GLB.

Ou l'utilise telle quel.
Mais c est pas le plus beau des formats le FBX.

Pour cela utiliser l exporter de Unity.

**Google:** Unity Package Manager Export

Deposer votre export ici pour le projet Godot:  
- https://github.com/EloiStree/2026_04_07_gdp_charleroi_xr_micro_bit_sensors/issues/2

### Explorer Pro Builder

Unity a un editeur 3D simplifier qui permet au developer et debutant de debuter.
Je vous invite a regarder a Pro Builder et faire le meme exercice avec un autre composant.
- https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/202
- https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/173

### Le meme exercice xD

L apprentissage pas par le repetition.
Refaite le exercice avec un autre composant.


