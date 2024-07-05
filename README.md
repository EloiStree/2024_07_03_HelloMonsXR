  # Hello Mons XR

Bonjour à la réalité virtuelle

Nous avons des casques XR/VR prenant la poussière.

Des appareils XR :
- 5 Oculus Quest 2
- 5 Pico 4

D'autres formats :
- 2 Vive XR Elite
- 2 Pimax
- 1 Lynx

Le but de l'atelier :
- Apprendre à développer sur les appareils Android XR
- Apprendre à utiliser le profiler Unity3D et optimiser
- Pratiquer la création de boîtes à outils
- Pratiquer le système d'input via les contrôleurs XR et Xbox
- Tester le Quest 3 en AR et le Pimax sur Alyx


# Scope et simplicité

## Thomas

Il y a une personne qui représente la simplicité : [Thomas Van Bouwel](https://www.linkedin.com/in/thomas-van-bouwel-ba06233b/?originalSubdomain=be) avec Cubism
- [Cubism](https://youtu.be/aDCbdJBHqw4) : https://youtu.be/aDCbdJBHqw4

[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/9e1ffbd9-69ef-4b09-a0bb-5c0efb352af2)](https://youtu.be/aDCbdJBHqw4)
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/aa08b9a0-22e7-4430-b559-90285e2f1439)](https://youtu.be/0UowL5cjhaI)

## Eloi 

[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/76ed60ed-cc65-41ae-869e-73708e370fc9)](https://youtu.be/3Q8TbYVGjpE)
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/78923b7f-ede6-4a0f-827c-4b5ba56e2cd5)](https://youtu.be/4Gk-2IwnEEo)
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/62a16c68-ded1-40d7-95b1-777dcf693d89)](https://youtu.be/nvMY04GPniE)
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/ddc72d09-f9c5-4a2f-956c-f84c83d17085)](https://youtu.be/YkGAWxjKQFQ)
Scratch: https://scratch.mit.edu/projects/966307753/editor/

## Mini-Jam : Drone Bullet Hells

**Quatre piliers** : Bullet, Hell, Drone, XR  
**CCC** : Camera XR, Drone avoiding bullets, Controller

### Planning :
- Mercredi : Avoir un jeu XR avec un drone basique
- Jeudi : Avoir beaucoup de "bullets" et être confronté à de l'optimisation via le profiler
- Vendredi : SideQuest et alternatives au Quest : Lynx R1, Vive XR Elite, Pimax ([Half Life Alyx](https://www.youtube.com/watch?v=ZX-03yBcm3k))

### Tâches :

- Toucher : Créer une boîte à outils qui active un objet par le toucher
- Regarder : Créer une boîte à outils qui active un objet par le regard prolongé
- Gamepad : Créer une boîte à outils qui écoute à deux joysticks Xbox, Quest et Pico 4
- Drone : Créer une boîte à outils qui permet de bouger un drone à 4 axes
- Bullet : Créer une boîte à outils qui permet de faire apparaître des bullets linéaires
  - LOD : Appliquer le LOD de Unity pour changer l'aspect du projectile
  - Beaucoup de bullets :
    - Junior : Créer un "pool" de bullets basiques
    - Medior : Créer un "pool" de bullets utilisant JobTransform
    - Medior+ : Créer un pool utilisant un mesh

XR spécifique:
- Pincher & Grabber : Créer un outil permettant de pincher ou grabber sans dépendance à une librairie XR ([Exemple](https://gitlab.com/eloistree/2020_02_01_MagnetSnapping.git))
- Setup Room sans SDK: Permetter avec la main (ou autre) de définir le sol sans SDK (voir les murs si vous sentez de niveau et créatif)

-------------------------------------------------------------------

# What is VR

![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/50139707-e4bb-44dc-bd3e-1e48a1891c5b)

- https://www.youtube.com/watch?v=wRCS2-AAyNM
- https://www.youtube.com/watch?v=8rVnkWbLnk8



## MRTK, VRTK, Unity Toolkit 3

MRTK: Corporation
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/d6225597-7052-4e58-96a1-fea25cd653f7)](https://learn.microsoft.com/fr-fr/windows/mixed-reality/mrtk-unity/mrtk3-overview/)
https://learn.microsoft.com/fr-fr/windows/mixed-reality/mrtk-unity/mrtk3-overview/

VRKT: Community
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/3ca8024e-fca6-4945-b248-752bc8a99ea1)](https://www.youtube.com/@VirtualRealityToolkit)
https://github.com/ExtendRealityLtd/VRTK


XRTK 3: Unity SDK
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/84d32dec-fc8c-4aaf-8192-03927f60fd99)](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.0/manual/index.html)
https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.0/manual/index.html

Meta Block: Natif SKD   
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/ac178eb8-8b6f-4ba0-bf40-e18a06e0a8d3)
](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657)  
https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657  
  


# Faire un jeu en VR ?

Tutorial Youtube:
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/42a7aca1-3b5d-44db-b63a-803a594b25d1)
](https://www.youtube.com/watch?v=HhtTtvBF5bI&list=PLpEoiloH-4eP-OKItF8XNJ8y8e1asOJud&index=2)  


Udemy (free)
[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/7468ff51-9d41-431d-8de6-4cbac6766a7f)](https://www.udemy.com/course/mixedreality/?couponCode=METASDK)  
[https://www.udemy.com/course/mixedreality/](https://www.udemy.com/course/mixedreality/?couponCode=METASDK)  
https://www.xrhack.com   


## Start point

- Pico 4: https://developer.picoxr.com/resources/   ([Open XR version](https://youtu.be/eyHl34vxm3c))
- Quest 2: [New way](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657)  ([Old way](https://assetstore.unity.com/packages/tools/integration/oculus-integration-deprecated-82022))
- Pimax: https://github.com/wearvr/pimax-vr-unity-sdk-instructions ?
- Elite XR: https://developer.vive.com/resources/vive-wave/tutorials/installing-wave-xr-plugin-unity/
- Lynx R1: https://portal.lynx-r.com/downloads/

--------------


## Mes débuts

[![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/8be23a36-b9f8-412e-9846-905016604125)](https://youtu.be/QqeDQi5-pTQ)
[Doudou Rumble](https://youtu.be/QqeDQi5-pTQ) - _[Snooppy](https://youtu.be/cB1fjEJqvo8)_ 




----------------


## Game Jam / Group

![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/922864d3-5571-437d-80af-ad7ad0aa5dfb)
"Ce n'est pas en prenant neuf femmes que l'on peut faire un enfant en un mois."

-----------------------------

## Jam 

![image](https://github.com/EloiStree/2024_07_03_HelloMonsXR/assets/20149493/4b999eba-7503-4f2c-bf29-821841199b86)
- L'important dans une jam c'est pas la fin, c'est le moment et de s'accorder. 
- L'important dans un hackathon c'est pas de gagner le prix du jury, c'est de hacker. 
  
- Tool pour hackathon: https://github.com/EloiStree/2022_04_20_PitchGuideHackathon  
