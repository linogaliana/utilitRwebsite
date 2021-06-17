---
title: "doremifasol : un package R facilitant l'accès aux données Insee"
author: admin
date: 2021-06-16
description: "Une présentation du package doremifasol, sur lequel s'appuie la documentation utilitR"
draft: false
categories: ["doremifasol"]
tags: ["doremifasol","package"]
featured: true
image:
  caption: ""
  focal_point: ""
slug: doremifasol
---

## Qu'est-ce que doremifasol ?

Le package `doremifasol` (_Données en R Mises à disposition par l’Insee et Facilement Sollicitables_) permet d'importer facilement dans R des données Insee.

Il offre deux fonctionnalités principales :

* télécharger et importer dans `R` des fichiers disponibles sur insee.fr (Base Permanente des Équipements, Recensement de Population, Filosofi...) ;
* requêter l'[API](https://api.insee.fr/catalogue) Sirene et recupérer les résultats dans `R`.

L'objectif du package est de rendre transparentes les différentes tâches à réaliser avant de pouvoir traiter les données : recherche sur le site, téléchargement, décompression, import dans `R`....

Le fonctionnement du package et la liste des données disponibles est consultable sur le [site du package](https://inseefrlab.github.io/doremifasol).

## Quel rapport avec utilitR ?

Afin de se rapprocher le plus possible des situations de travail rencontrées par les agents de l’Insee, la plupart des exemples de la documentation `utilitR` reposent sur des données produites par l’Insee.

Le package `doremifasol` a été utilisé pour récupérer des données dans R et créer un petit package de données appelé `doremifasolData`. C'est ce dernier package qui est utilisé pour disposer d'exemples reproductibles dans la documentation.
