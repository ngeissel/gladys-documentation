# Installation

## Description

*Installation de Gladys via une image raspbian*

## Prérequis

- [x] Savoir installer une image raspbian
- [x] Savoir se connecter en ssh sur son raspberry

## Matériel

- [x] Raspberry v3
- [x] Micro SD (>8Gb)

## Tutorial

### Installation

1. Récupérer [l'image raspbian](https://gladysproject.com/fr/installation/)
2. Installer l'image sur la carte micro sd (en utilisant [etcher](https://etcher.io/) )
3. Mettre la carte dans le raspberry

### Configuration espace disque
Se connecter sur le raspberry en ssh.
```Shell
sudo raspi-config
```
Sélectionner le menu "7.Advanced Options" puis l’option “A1. Expand Filesystem”.
Rebooter pour prendre en compte la nouvelle configuration.

### Accéder à Gladys
http://ip:8080
ip : à remplacer par l'ip de son rasberry

## Ressources

  * [Lien du tutoriel](https://gladysproject.com/fr/installation/)
  * Outil pour installer une image iso : [etcher](https://etcher.io/) )
  * Utilitaire permettant de se connecter en ssh à partir de windows : putty
