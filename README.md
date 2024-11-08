<h1 align=center>Expérimentations du Lab Acropolix</h1>

<br />


>L'ensemble des expérimentations du Lab Acropolix dans le domaine de la Robotique Mobile.

<br/>

Tous les codes sources se trouvent dans le dossier **_src_**. 
Pour comprendre leur fonctionnement, je vous invite à lire la [documentation du Lab Acropolix]().<br />
Libre à vous de les adapter à vos propres besoins.

<br />

# Prérequis

Pour pouvoir compiler les différents programmes présents dans ce dépôt, il vous faudra installer les paquets suivants :
- _Git_ : pour pouvoir récupérer tous les codes sources
- une chaîne de cross-compilation pour _Raspberry Pi_ (j'utilise celle fournie par _Buildroot_ car mon petit RPi tournera sur un kernel Linux personnalisé, mais il en existe d'autres, vous trouverez de nombreuses ressources sur le sujet sur le Net)
- _libgpiod-dev_ (sur _Debian_, à adapter en fonction de votre distribution _GNU/Linux_) : c'est la bibliothèque qui nous permettra de "jouer" avec les GPIO du _Raspberry Pi_

---
#### ℹ️ _**Remarque**_

A titre d'information, j'utilise la distribution _Debian_ (en version _CLI_, ie sans interface graphique), en machine virtuelle sur un _Macbook Pro 16"_ (de 2021), équipé d'un processeur _M1 Pro_ et de 32 Go de RAM. Un dossier partagé entre le _Macbook Pro_ et la machine virtuelle a été créé afin de pouvoir stocker les codes sources sur la machine hôte et éviter ainsi d'avoir une machine virtuelle trop volumineuse.
Les codes sources sont écrits à l'aide de _VS Code_ sur le _Mac_, et pour les compiler, j'accède à la machine virtuelle en SSH.

---
<br />

# Installation

Pour installer les codes sur votre machine, il vous suffit dans un premier temps de cloner ce dépôt :

```shell
git clone https://github.com/LabAcropolix/Experimentations.git
```

Puis, rendez vous dans le dossier nouvellement créé :
```shell
cd Experimentations
```

A suivre
