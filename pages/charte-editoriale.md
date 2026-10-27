---
id: 01M5MQ4T8W00FJM7R527SJ75QE
slug: charte-editoriale
titre: Charte éditoriale et méthodologie
description: Comment FoodOracle construit ses fiches, quelles données sont calculées par le code, quel rôle joue l'IA, et comment les erreurs sont corrigées.
langue: fr
statut: brouillon
publie_le: null
modifie_le: 2026-10-23T00:00:00+02:00
auteur: fabrizio-guerrini
relu_par: null
relu_le: null
assistance_ia: assistee
gabarit: editoriale
sommaire: true
image: null
mots_cles:
  - charte éditoriale
  - méthodologie
  - intelligence artificielle
  - table Ciqual
  - allergènes
noindex: false
---

Cette charte décrit la manière dont FoodOracle est construit. Elle sert au lecteur, qui doit pouvoir savoir d'où vient une information, et à l'équipe, qui doit appliquer les mêmes règles à chaque fiche.

## Ce qu'une fiche contient

Une fiche de recette indique son univers (cuisine, pâtisserie ou boulangerie), son niveau de difficulté, ses temps de préparation, de cuisson et de repos, sa liste d'ingrédients avec les quantités, ses étapes, ses points de contrôle critiques et ses conditions de conservation. Une fiche d'ingrédient donne sa famille, ses saisons, ses modes de conservation et ses accords. Une fiche de cocktail précise si la boisson contient de l'alcool.

Chaque fiche porte une date de publication et une date de modification. La date de modification ne change que si le contenu change réellement.

## Ce que le code calcule

Certains chiffres ne sont jamais écrits par une personne ni par le modèle d'IA. Le code les calcule à partir des ingrédients et des quantités :

- le coût matière et le coût par portion, à partir des prix d'achat saisis ;
- le rendement, à partir des pertes déclarées ;
- les valeurs nutritionnelles par portion ;
- les allergènes dérivés des ingrédients ;
- le degré d'alcool final d'un cocktail, et le coût du verre.

Le code tient compte des quantités réellement indiquées. Un chiffre calculé indique sa méthode et sa source, et il est recalculé à chaque modification de la fiche.

## Table Ciqual

Les valeurs nutritionnelles viennent de la table Ciqual, publiée par l'Anses. Chaque ingrédient est rattaché à son code Ciqual quand il existe. Un ingrédient sans code Ciqual ne reçoit aucune valeur nutritionnelle inventée : la fiche le signale. Les valeurs de la table décrivent un aliment générique, pas une marque ni un produit précis.

## Allergènes

Les allergènes sont dérivés des ingrédients. Une fiche déclare au moins un élément, et l'absence d'allergène est écrite de manière explicite. Une fiche ne dit jamais « sans gluten » ou « sans allergène » sans vérification de chaque fiche produit qui la compose. Les produits du commerce changent de composition : l'étiquette fait foi.

## Contrôles automatiques

Avant qu'un contenu soit publié, un contrôle automatique vérifie notamment :

- que tous les champs obligatoires sont présents et au bon format ;
- que les listes fermées (univers, types de plat, techniques, saisons, régimes) ne contiennent que des valeurs connues ;
- que les liens internes pointent vers des pages existantes ;
- que chaque article d'actualité cite au moins une source ;
- que la fiche ne contient aucun HTML brut ni caractère de mise en forme interdit.

Un contenu qui échoue à un contrôle n'est pas publié. Le contrôle ne corrige pas silencieusement : il refuse, et l'erreur est corrigée à la source.

## Usage de l'intelligence artificielle

Les textes sont rédigés avec l'aide d'un modèle d'IA, à partir de règles d'écriture et de modèles de fiche. Le modèle ne calcule aucun chiffre et ne produit pas le balisage final de la page : ces tâches relèvent du code.

Chaque contenu indique son niveau d'assistance :

- « aucune » : contenu rédigé sans IA ;
- « assistée » : rédigé avec l'aide d'une IA, puis contrôlé par le code ;
- « générée » : produit par une IA, sans relecture humaine nommée.

Le libellé « relu par la rédaction » n'apparaît qu'après une relecture humaine réelle, avec le nom ou l'équipe qui l'a faite et la date. Aucune relecture n'est affichée par défaut.

Conformément à l'article 50 du règlement européen sur l'intelligence artificielle, un texte publié pour informer le public sur une question d'intérêt général porte la mention de son origine assistée par IA.

Le chat du site répond à partir des contenus publiés. Il indique qu'il est automatisé, et il peut se tromper. Il ne demande aucune donnée personnelle.

## Sources et corrections

Les articles d'actualité citent leurs sources : titre, adresse, date de consultation. Un chiffre d'article renvoie à une source primaire quand elle existe, et la date de consultation est notée.

Une erreur peut être signalée par la page [contact](/contact/). Une correction de fond est datée et visible sur la fiche. Quand une fiche est retirée, elle ne reste pas en ligne sous une autre forme : l'adresse répond par une page de retrait.

## Indépendance

FoodOracle ne publie pas de contenu contre rémunération sans le signaler. [RÈGLES DE PARTENARIAT ET DE PUBLICITÉ À CONFIRMER PAR LA DIRECTION] Le site ne vend pas de données et n'affiche aucune publicité à la date de cette charte. [À CONFIRMER AVANT PUBLICATION]

## Évolution de la charte

Cette charte est revue quand une règle change. La date de dernière modification figure en bas de page.
