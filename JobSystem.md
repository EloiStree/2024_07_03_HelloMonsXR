Salut à tous :)


-------


- https://github.com/EloiStree/2020_05_28_JimmyScreamFPS.git
- https://github.com/EloiStree/2020_06_17_VirtualRealityTags.git
- https://github.com/EloiStree/2024_04_18_WatchExecuteTime.git

-----


# Move the drone

Pour le fait de bouger le drone.

Trois possibiltées:
- boite à outil qui utiliser deux transformes pour les mains
- boite à outil qui utiliser des transforme pour la main du joueur
- Apprendre à utiliser la bibliothèque de OVR pour lire les 4 axes.

Example, Pincher avec deux transforms :https://gitlab.com/eloistree/2020_02_01_MagnetSnapping.git



# MonoBehaviour et Transform is "bad"

Pour comprendre l'utilité d'utiliser le Job System, il faut d'abord comprendre le point faible de Unity3D.

Créé une boite à outil (non job system avec le pool d'Arnaud d'avoir le plus de projectile possible afficher à l'écran que vous puissier)
Pour permet cela utiliser le LOD de Unity et utiliser un Quad that look at the camera quand loin de vous.

Travailler par du sur le Quest 2.
Example, vous travailler sur la boite à outil sur le PC d'un et importer tester sur le PC du seconds.


# Job System for 16000 projectil

- Bouger 16k astéroide 
- Orianté 16k Squad d'astéroide.
- Géré 16k collision avec les deux mains du joueur et son drone.





Être en capacité de calculer sur le CPU à la place du GPU est un pouvoir immense sur Quest et Android.


Le but est d'explorer les bases du job system pour que vous puissiez l'utiliser.



Bullet FTL : https://github.com/EloiStree/2021_08_19_FTLBullets_CapsuleCollisionWithMathAndJob



[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/89c25136-09d0-4c89-b284-ce6f3ef2c023)
](https://youtu.be/CE1B7tdGCw0)

Restons simple sur les examples d'utilisations. 




//16 native array .
https://github.com/EloiStree/2024_04_16_IMMO_Player_Generic16K
// Trop compliqué mais en example.
https://github.com/EloiStree/2024_04_16_IMMO_ShieldDrone




--------------





# Light Baking et unlit
See magic door

# Transparent problem

See Quest game style cartoon 

# Mat 

Enable GPU

# Mesh Baking

 See Mesh Baker



