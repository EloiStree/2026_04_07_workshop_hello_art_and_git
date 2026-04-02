
# Des cubes et des ronds  

Git, Input Toy: https://github.com/EloiStree/2026_04_02_unity_input_and_toys

[<img width="657" height="124" alt="image" src="https://github.com/user-attachments/assets/372d77a4-aa9e-4a93-9f20-392c2368f649" />](https://github.com/EloiStree/2024_08_05_upm_uv_drawable_drones)  
[<img width="1299" height="869" alt="image" src="https://github.com/user-attachments/assets/59df6f0e-f715-445b-b792-fa8307204f9a" />](https://github.com/EloiStree/2026_04_01_unity_hello_cube)   
[<img width="570" height="366" alt="image" src="https://github.com/user-attachments/assets/6aeaf768-8751-4aa6-aa14-9d025bfe5d57" />](https://github.com/EloiStree/2024_08_05_upm_uv_drawable_drones)  
[<img width="416" height="285" alt="image" src="https://github.com/user-attachments/assets/de10b046-512f-45b3-9ad0-aee78ebd23f0" />](https://www.youtube.com/watch?v=jpczFTSQmsA)     
Robot vidéo : [https://www.youtube.com/watch?v=jpczFTSQmsA](https://www.youtube.com/watch?v=jpczFTSQmsA)        
  
Solution : [https://github.com/EloiStree/2026_04_01_unity_hello_cube](https://github.com/EloiStree/2026_04_01_unity_hello_cube)     
Vidéos :     
* Créer un cube et sauvegarder sur Git : https://youtu.be/KLYvMq1HCUM    
* Survol de comment bouger et tourner : https://youtu.be/cmTlat0eYK4  

Download: [Piggy.zip](https://github.com/user-attachments/files/26422015/mon_cube_cross_for_piggy.zip)

---

## Objectif

### Principal 

* **Résultat** : Avoir un simulateur de cube sur GitHub avec Unity3D  
* **Savoirs** : 
  * Comprendre la différence entre *Mesh*, *Color*, *Material*, *Texture* et la lumière
  * Savoir sauver sur GitHub via Git

### Secondaire : faire tourner et bouger le cube

* **Résultat** : Faire bouger notre objet (piggy)
* **Savoirs** :
  * Apprendre à créer un script avec un *Hello World*, une fonction `Update` et des inputs
  * Comprendre la différence entre `.Translate` du `Transform` et `.Move` du `CharacterController`


**Bonjour Unity :**
* C’est quoi Unity ?
* C’est quoi une scène ?
* Comment on bouge ?
* C’est quoi un point vide ?
* C’est quoi un cube ?
* C’est quoi une caméra ?
* C’est quoi une lumière ?
* C’est quoi un collider ?
* C’est quoi un Rigidbody ?
* C’est quoi une couleur ?
* C’est quoi une image ?
* C’est quoi une texture ?
* C’est quoi un dépliage ?
* C’est quoi un matériau URP ?
* C’est quoi un matériau unlit ?
* C’est quoi ShaderToy ?
* C’est quoi une couleur d’environnement ?
  * Noir transparent vs Skybox ?
* C’est quoi un prefab ?

**Bonjour Git :**
* C’est quoi Git ?
  * Comment on l’installe ?
  * C’est quoi la version du Git installé ?
  * C’est quoi un git config ?
  * C’est quoi un git config --global ?
  * C’est quoi un merge rebase ?
* C’est quoi GitHub ?
  * Comment on crée un compte ?
  * Comment on crée un répertoire ?
* Comment on télécharge ce répertoire ?
* Comment on voit les fichiers cachés et les extensions ?
* Comment on le déplace dans notre projet Unity ?
* Comment on ajoute un `.gitignore` pour ne pas uploader 1 Go ?
* À quoi sert un gitignore ?
* Comment on sauvegarde localement ?
* Comment on sauvegarde en ligne ?
* Comment on change le README sur GitHub ?
* Comment je récupère le README.md localement ?
* Comment on ajoute une licence à un projet ?

**Builder :**
* Comment on build pour Windows ?
* Comment on change le nom ?
* Comment on change l’icône ?
* C’est quoi itch.io ?
 
---------------------

- Tick: https://github.com/EloiStree/2025_06_02_upm_tick_collection.git
- Car: https://github.com/EloiStree/2023_11_01_upm_kid_toy_skid_steering_code.git
- Helicopter: https://github.com/EloiStree/2023_02_19_upm_kid_toy_helicopter_code.git
- OVNI: https://github.com/EloiStree/2025_04_15_upm_kid_toy_ovni_code.git
- Tello: https://github.com/EloiStree/2023_02_19_upm_kid_toy_drone_tello_code.git
- Boat : https://github.com/EloiStree/2024_09_23_upm_kid_toy_boat_code.git
- Tank : https://github.com/EloiStree/2024_10_05_upm_kid_toy_tank_code.git
- UV Drawable Drones: https://github.com/EloiStree/2024_08_05_upm_uv_drawable_drones.git

As package to use
```
    "be.elab.tickcollection": "https://github.com/EloiStree/2025_06_02_upm_tick_collection.git",
    "be.elab.skidtoycar": "https://github.com/EloiStree/2023_11_01_upm_kid_toy_skid_steering_code.git",
    "be.elab.hellocopter": "https://github.com/EloiStree/2023_02_19_upm_kid_toy_helicopter_code.git",
    "be.elab.ovnitoy": "https://github.com/EloiStree/2025_04_15_upm_kid_toy_ovni_code.git",
    "be.elab.tellotoy": "https://github.com/EloiStree/2023_02_19_upm_kid_toy_drone_tello_code.git",
    "be.elab.toyboat": "https://github.com/EloiStree/2024_09_23_upm_kid_toy_boat_code.git",
    "be.elab.toytank": "https://github.com/EloiStree/2024_10_05_upm_kid_toy_tank_code.git",
    "be.elab.uvdrawabledrones": "https://github.com/EloiStree/2024_08_05_upm_uv_drawable_drones.git",
```

As submodules to work on
```
git submodule add https://github.com/EloiStree/2025_06_02_upm_tick_collection.git Packages/2025_06_02_upm_tick_collection
git submodule add https://github.com/EloiStree/2023_11_01_upm_kid_toy_skid_steering_code.git Packages/2023_11_01_upm_kid_toy_skid_steering_code
git submodule add https://github.com/EloiStree/2023_02_19_upm_kid_toy_helicopter_code.git Packages/2023_02_19_upm_kid_toy_helicopter_code
git submodule add https://github.com/EloiStree/2025_04_15_upm_kid_toy_ovni_code.git Packages/2025_04_15_upm_kid_toy_ovni_code
git submodule add https://github.com/EloiStree/2023_02_19_upm_kid_toy_drone_tello_code.git Packages/2023_02_19_upm_kid_toy_drone_tello_code
git submodule add https://github.com/EloiStree/2024_09_23_upm_kid_toy_boat_code.git Packages/2024_09_23_upm_kid_toy_boat_code
git submodule add https://github.com/EloiStree/2024_10_05_upm_kid_toy_tank_code.git Packages/2024_10_05_upm_kid_toy_tank_code
git submodule add https://github.com/EloiStree/2024_08_05_upm_uv_drawable_drones.git Packages/2024_08_05_upm_uv_drawable_drones
```

**Comme des gamins**

> Allons bouger des jouettes avec du code.

- Ajouter au package manager via interce une boite a outils:
  - [Tick Collection](https://github.com/EloiStree/2025_06_02_upm_tick_collection)  
- Ajoutons des jouettes aux packages manager via fichier package.json :
  - [Car Skid](https://github.com/EloiStree/2023_02_19_upm_KidToyHelicopterModeCode)
  - [OVNI](https://github.com/EloiStree/2025_04_15_upm_KidToyOvniCode)
  - [Tello](https://github.com/EloiStree/2023_02_19_upm_KidToyDroneTelloModeCode)
  - [Helico](https://github.com/EloiStree/2023_02_19_upm_KidToyHelicopterModeCode)
  - [UV Drawable Drones](https://github.com/EloiStree/2024_08_05_upm_uv_drawable_drones.git)
  - Honoroable Mention:
    - [Boat](https://github.com/EloiStree/2024_09_23_upm_KidToyBoatModeCode)
    - [Tank](https://github.com/EloiStree/2024_10_05_upm_KidToyTankTreadModeCode)
      
`Package.json`  

```
  
```
 



---------------------

> Un peu hard pour un premier jours.  
Video si vous voulez vous y essayer[🎥](https://youtu.be/cmTlat0eYK4)  
 
**Hello World :**
* À quoi sert de créer un dossier "_" ?
* Comment on crée du code Unity ?
* Pourquoi un dossier Scripts ?
* C’est quoi un fichier .cs ?
* C’est quoi un MonoBehaviour ?
* C’est quoi Start ?
* C’est quoi Debug.Log ?
* C’est quoi un string ?
* C’est quoi Update ?
* C’est quoi une frame ?
* C’est quoi un delta ?
* Comment on fait avancer notre cube ?
* Comment on le fait tourner ?
* C’est quoi un Unity Range ?
* Comment on évite qu’il traverse les murs ?
* C’est quoi un Character Controller ?
* Comment on tourne avec un Character ?
* Comment on avance avec un Character ?
* Comment on empêche mon joueur de tomber sur le côté ?

**Input Tick :**
* Comment j’écoute mon joystick ?
* Comment je transmets les joysticks à mon script ?
* C’est quoi une méthode ?
* C’est quoi un paramètre ?

**Tadaam 🎊**   
À la fin de cet atelier, vous aurez un cube qui bouge proprement sur GitHub.      
Félicitations !    

Je ne me suis pas attardé sur le code,   
car c’est le sujet des cours d’Arnaud.   


------------------------


# Draft

- Link used with kids https://github.com/EloiStree/2025_02_24_ForFunDrones300
```
    "be.elab.forfun300": "https://github.com/EloiStree/2025_02_24_ForFunDrones300.git",
    "be.elab.irctoy": "https://github.com/EloiStree/2024_09_15_IToyControllerRC.git",
    "be.elab.outership": "https://github.com/EloiStree/2025_02_18_OuterWildsShip.git",
    "be.elab.quickfollowit": "https://github.com/EloiStree/2024_09_16_QuickFollowIt.git",
    "be.elab.tellotoy": "https://github.com/EloiStree/2023_02_19_KidToyDroneTelloModeCode.git",
    "be.elab.uvdrawabledrones": "https://github.com/EloiStree/2024_08_05_UvDrawableDrones.git",
    "be.elab.xinputdotnet": "https://github.com/EloiStree/2020_11_26_XInputDotNet.git",
    "be.elab.quickfollowit": "https://github.com/EloiStree/2024_09_16_QuickFollowIt.git",
```

```
git submodule add https://github.com/EloiStree/2025_02_18_upm_outer_wilds_ship.git Packages/2025_02_18_upm_outer_wilds_ship
git submodule add https://github.com/EloiStree/2024_09_06_upm_best_time_score.git Packages/2024_09_06_upm_best_time_score
git submodule add https://github.com/EloiStree/2024_09_03_upm_sky_riding_path.git Packages/2024_09_03_upm_sky_riding_path
git submodule add https://github.com/EloiStree/2024_10_16_upm_blocks_color.git Packages/2024_10_16_upm_blocks_color
git submodule add https://github.com/EloiStree/2024_06_31_upm_air_circuit_step.git Packages/2024_06_31_upm_air_circuit_step
git submodule add https://github.com/EloiStree/2023_02_17_upm_digital_score_and_clock Packages/2023_02_17_upm_digital_score_and_clock

```

```
https://github.com/EloiStree/2025_01_11_upm_22_minutes_ntp.git
https://github.com/EloiStree/2023_11_27_upm_set_point_board.git
https://github.com/EloiStree/2023_02_17_upm_digital_score_and_clock
https://github.com/EloiStree/2024_10_02_upm_patoune_race

```

https://eloistree.github.io/r/discord

Used in private workshop:  
- https://github.com/EloiStree/2025_02_05_P_NaturePack300  



```
git submodule add https://github.com/EloiStree/2024_08_10_upm_developer_note.git Packages/2024_08_10_upm_developer_note
git submodule add https://github.com/EloiStree/2024_10_16_upm_find_missing_script.git Packages/2024_10_16_upm_find_missing_script
git submodule add https://github.com/EloiStree/2025_06_02_upm_tick_collection.git Packages/2025_06_02_upm_tick_collection
git submodule add https://github.com/EloiStree/2025_04_02_upm_primitive_relay.git Packages/2025_04_02_upm_primitive_relay
git submodule add https://github.com/EloiStree/2024_04_18_upm_watch_execute_time.git Packages/2024_04_18_upm_watch_execute_time
git submodule add https://github.com/EloiStree/2019_07_24_upm_quick_git_utility.git Packages/2019_07_24_upm_quick_git_utility
git submodule add https://github.com/EloiStree/2019_07_21_upm_unity_package_facilitator.git Packages/2019_07_21_upm_unity_package_facilitator
```

