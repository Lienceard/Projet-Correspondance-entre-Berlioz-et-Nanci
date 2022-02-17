# Projet de transcription de la correspondance active de Hector Berlioz à sa sœur Nanci Berlioz

[![DOI](https://zenodo.org/badge/433904174.svg)](https://zenodo.org/badge/latestdoi/433904174)

## Contexte
Ce projet a été créé dans le cadre du module Git dispensé par [M.Thibault Clérice](https://github.com/PonteIneptique) pour le master 2 TNAH (Technologies Numériques Appliquées à l'Histoire) de l'École nationale des chartes, pour l'année 2021-2022.

L'objectif de ce devoir était de collaborer à plusieurs pour monter un projet de sources numériques tout en choisissant et utilisant des outils numériques nouveaux, en contrôlant la qualité des données.

Il s'agissait de définir un corpus, et de le soumettre à un processus d'HTR (*Handwritten Text Recognition*) à l'aide de l'outil eScriptorium. Ce dernier est un logiciel libre permettant de segmenter un document, de le transcrire automatiquement à l'aide d'un modèle (voir [ce lien](https://lectaurep.hypotheses.org/documentation/prendre-en-main-escriptorium) pour un tutoriel). Les données ainsi obtenues ont ensuite été corrigées, afin d'obtenir une transcription la plus pertinente possible. Ce dépôt présente et organise la restitution de ce travail.

## Corpus retenu

Nous avons choisi de travailler sur la correspondance active de Hector Berlioz adressée à sa sœur Anne-Marguerite "Nanci" Berlioz. Cette correspondance est disponible [en ligne](https://gallica.bnf.fr/services/engine/search/sru?operation=searchRetrieve&exactSearch=false&collapsing=true&version=1.2&query=((dc.creator%20adj%20%22berlioz%20hector%22%20or%20dc.contributor%20adj%20%22berlioz%20hector%22%20)%20and%20(dc.creator%20adj%20%22berlioz%20nanci%22%20or%20dc.contributor%20adj%20%22berlioz%20nanci%22%20)%20)%20&suggest=10&keywords=berlioz%20hector%20berlioz%20nanci) (Source gallica.bnf.fr / Bibliothèque nationale de France). L'ensemble des lettres adressées à Nanci Berlioz représentait un volume trop important pour notre projet, aussi nous les avons sélectionnées, par souci de cohérence, selon un ordre chronologique (voir le tableau de gestion) pour la liste exacte des lettres transcrites).

Au sein d'eScriptorium, nous avons choisi de soumettre notre corpus au modèle d'entraînement `Modèle Manuscrit 19e Lectaurep`, fruit du projet Lectaurep (LECTure Automatique de REPertoires).

Les vérités de terrain produites par ce projet pourraient servir par la suite à entraîner des modèles d'HTR.

## Collaboratrices

Pour l'alignement, la transcription, la gestion de projet, les corrections :

- [Ceard Lien](https://github.com/Lienceard)
- [Lebreton Fanny](https://github.com/FannyLbr)
- [Sajdak Cécile](https://github.com/SjdkC)


## Architecture du dépôt

Ce dépôt est organisé de la manière suivante :

1. Un dossier de comptes rendus de réunions : ce dossier contient de la documentation sur les réunions ayant permis de mettre en place le projet. D'autres choix ont, eux, été discutés dans les issues.
2. Un dossier "donnees" contenant un dossier par lettre transcrite, qui comprend :
    * Les transcriptions de la lettre au format XML (standard ALTO).
    * Les images de la lettre.
    * Un sous-dossier pour les transcriptions finales de la lettre au format texte.
    * Un sous-dossier pour les transcriptions brutes, telles que générées par HTR sur eScriptorium, non corrigées.
3. Un README de présentation du projet (le présent fichier).
4. Un fichier qui présente les choix d'exports et les conventions de nommage que nous avons adoptés.
5. Un tableau de gestion qui récapitule les lettres transcrites, leurs liens vers Gallica. Il permet également une gestion et une visualisation des étapes du projet.
6. Un fichier qui récapitule les normes de transcription que nous avons adoptées.

## État du projet

Ce projet est terminé. Cependant, il pourrait être poursuivi par la suite afin de prendre en compte de nouvelles lettres de Berlioz.



