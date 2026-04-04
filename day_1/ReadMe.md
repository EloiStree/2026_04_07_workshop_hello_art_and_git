
# Matin: Des cubes et des ronds  

Git, Input Toy: https://github.com/EloiStree/2026_04_02_unity_input_and_toys

[<img width="1299" height="869" alt="image" src="https://github.com/user-attachments/assets/59df6f0e-f715-445b-b792-fa8307204f9a" />](https://github.com/EloiStree/2026_04_01_unity_hello_cube)   


Solution : [https://github.com/EloiStree/2026_04_01_unity_hello_cube](https://github.com/EloiStree/2026_04_01_unity_hello_cube)     
Vidéos :     
* Créer un cube et sauvegarder sur Git : https://youtu.be/KLYvMq1HCUM    

Download: [Piggy.zip](https://github.com/user-attachments/files/26422015/mon_cube_cross_for_piggy.zip)

> Plug long, mais le meme exercice : [WebGL](https://eloiteaching.itch.io/wownicecube) | [Git](https://github.com/EloiStree/2024_08_22_unity_wow_nice_cube)   
> [🎥 Faire Sauter  le Cube](https://youtu.be/zM4Rm8Cs_MU?t=1389) [🎥 Un cube multi-platform XR](https://youtu.be/Ncd4KBM3km8?t=267)  [📑Workshop->](https://github.com/EloiStree/2024_07_19_workshop_charleroi_xr/issues/169)

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

**Tadaam 🎊**   
À la fin de cet atelier, vous aurez un cube qui bouge proprement sur GitHub.      
Félicitations !    

Je ne me suis pas attardé sur le code,   
car c’est le sujet des cours d’Arnaud. 


-------------

# Apres-Midi:  Input, Translate and Rotate  

_Si l'exercice du matin est fini_   

[<img width="1358" height="335" alt="image" src="https://github.com/user-attachments/assets/383e4d7d-dbd0-4c62-8020-fb6841e4f228" />](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/issues/16)

## Learn about Input in Unity

[🎥; How To tutorial](https://youtu.be/1-5Cb5VWcY8)   
 
Try to move the car with the Input system of Unity3D:  
- Input: https://github.com/EloiStree/2025_06_02_upm_tick_collection.git  
  - Steer car: https://github.com/EloiStree/2023_11_01_upm_kid_toy_skid_steering_code.git
  - Helicopter: https://github.com/EloiStree/2023_02_19_upm_kid_toy_helicopter_code.git
  - Tello: https://github.com/EloiStree/2023_02_19_upm_kid_toy_drone_tello_code.git
  - Two wheel: https://github.com/EloiStree/2026_04_03_upm_kid_toy_two_wheel_code.git


## Rotate and Move Two Wheels Car

Voir atelier [ici](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/issues/16) ([Solution](https://github.com/EloiStree/2026_04_03_upm_kid_toy_two_wheel_code))   
[🎥How to](https://youtu.be/Bq60Q9n4NWk) 





---------------------

---------------------

# Archive

J'avais fait un Hello World C# un peu trop compliquer pour des debutants.  
> Un peu hard pour un premier jours.  [🎥](https://youtu.be/cmTlat0eYK4)  
_la video si vous voulez vous y essayer_  

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

  

