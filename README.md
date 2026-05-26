# 📱 Lab 10 – Navigation Drawer et Fragments
### Cours : Programmation Mobile – Android avec Java
### ENSA marrakesh

---

## 🎯 Objectif

Créer une application Android intégrant un menu latéral de navigation **(Navigation Drawer)** et gérer dynamiquement plusieurs fragments dans une seule activité.

---

## 🎬 Vidéo Démo

[![Voir la démo](https://img.youtube.com/vi/lZGuL4xRql8/0.jpg)](https://youtu.be/lZGuL4xRql8?si=leebfc-sM2QOKYPT)

> Cliquez sur l'image pour voir la démonstration de l'application.

---

## 🛠️ Technologies utilisées

| Technologie | Version |
|---|---|
| Langage | Java |
| Min SDK | API 24 (Android 7.0) |
| IDE | Android Studio |
| UI | DrawerLayout + NavigationView |
| Navigation | FragmentManager |

---

## 📁 Structure du projet

```
app/
├── java/com.example.lab10/
│   ├── MainActivity.java
│   ├── BlankFragment.java
│   ├── BlankFragment2.java
│   └── FragmentList.java
└── res/
    ├── layout/
    │   ├── activity_main.xml
    │   ├── fragment_blank.xml
    │   └── fragment_blank2.xml
    ├── menu/
    │   └── activity_main_drawer.xml
    └── drawable/
        ├── ic_home.xml
        ├── ic_dashboard.xml
        └── ic_list.xml
```

---

## 📋 Fonctionnalités

- ✅ Menu latéral (Navigation Drawer) avec 3 items
- ✅ **Fragment 1** – Fond rose avec texte centré
- ✅ **Fragment 2** – Fond bleu avec texte centré
- ✅ **Fragment List** – Liste de 10 éléments avec ListFragment
- ✅ Navigation fluide entre les fragments via FragmentManager

---

