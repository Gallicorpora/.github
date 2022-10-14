# Gallic(orpor)a

## Projet

Gallicorpora propose de consolider et d'appliquer une chaîne de traitement pour les documents anciens de Gallica en diachronie longue, des premiers manuscrits français aux imprimés révolutionnaires. Au-delà de la simple extraction de texte en masse, nous améliorerons les jeux de données d'entraînement pour l'apprentissage machine, les outils et les modèles déjà existants pour l'extraction, l'annotation et la diffusion de données richement annotées provenant des collections de la Bibliothèque nationale de France (BnF).

## Script AltoToTEI
Dans le cadre du projet, Kelly Christensen a développé un script python permettant de créer à partir des images de la BnF des textes pré-éditorialisé en XML-TEI. Le script est présent actif dans les différents dépôts et permet de générer des fichiers XML TEI d'exemple à partir des données d'entrainement.

## Données HTR

Les données se trouvent dans les différents répertoires(classé par siècle) du projet au chemin ‘./data/*/*.xml‘.
Elles sont au format alto (v.4) et suivent les normes de segmentation SegmOnto (https://segmonto.github.io). Toutes les données sont cataloguées sur HTR-United (https://htr-united.github.io). Les données ont été produites à l'aide de l'interface eScriptorium.

## Données lemmatisation 

Les données se trouvent au chemin ‘./data/*.xml ou *.tsv‘. L'ensemble des données sont au format XML TEI et tsv. Les données suivent les normes d'annotation du manuel suivant : Simon Gabay, Jean-Baptiste Camps, Thibault Clérice. Manuel d'annotation linguistique pour le français moderne (XVIe -XVIIIe siècles) : Version B. 2022. ⟨hal-02571190v2⟩.

## Modèles HTR et segmentation

Les modèles entrainés dans le cadre du projet sont disponibles dans le dépot : Segmentation-and-HTR-Models. Ils ont été entrainé des données produites dans eScriptorium et du moteur HTR Kraken (version 4).

## Financeur

Ce projet est financé par le dataLab de la BnF (https://www.bnf.fr/fr/bnf-datalab).

## Infrastructure

Il est produit sur l'infrastructure du projet CREMMA et de l'INRIA (https://www.dim-map.fr/projets-soutenus/cremma/).
Les données pour l'HTR sont produites à l'aide de l'interface eScriptorium (https://gitlab.com/scripta/escriptorium).
Les données de lemmatisation sont produites à l'aide de l'interface Pyrrha (https://dh.chartes.psl.eu/pyrrha/).

## Citer le projet 

*Gallic(orpor)a: extraction, annotation et diffusion de l'information textuelle et visuelle en diachronie longue*, Benoît Sagot, Laurent Romary, Rachel Bawden, Pedro Javier Ortiz Suárez, Simon Gabay, Ariane Pinche, and Jean-Baptiste Camps, https://github.com/Gallicorpora/Gallicorpora.github.io.

## Communications sur le sujet

Ariane Pinche, Kelly Christensen, Simon Gabay, « Between automatic and manual encoding: towards a generic TEI model for historical prints and manuscripts », *TEI Conference and Members’ Meeting 2022*, 12-16 septembre, Newcastle, UK.

Kelly Christensen, Ariane Pinche, Simon Gabay. Gallic(orpor)a: Traitement des sources textuelles en diachronie longue de Gallica. DataLab de la BnF, Jun 2022, Paris, France. ⟨hal-03716534⟩

