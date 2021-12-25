---
layout: rm_post
title:  "Saint-Cloud paie le FSRIF"
subtitle: "En savoir plus sur cette péréquation."
header-img: assets/post/2021-10-14-finances-locales-fsrif/tableau_fsrif.jpg
author: rafael_maychmaz
date: 2021-10-14 09:00:00 +0100
categories: formation 
tags: finances
---

# Saint-Cloud paie le FSRIF

![Le FSRIF dans le budget de Saint-Cloud](/{{ page.header-img }} "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Avant propos : Cet article fait partie d'une série d'articles visant à présenter les **finances locales** de la ville de Saint-Cloud. C'est également l'occasion de replacer les notions abordées dans un contexte plus large ; par exemple en comparant la ville à des communes voisines.

## Qu'est ce que le FSRIF ?

FSRIF signifie *"fonds de solidarité des communes de la région d’Ile-de-France"*. 

Le FSRIF a été créé en 1991 pour contribuer à l’amélioration des conditions de vie dans les communes urbaines d’Ile-de-France supportant des charges particulières au regard des besoins sociaux de leur population sans disposer de ressources fiscales suffisantes.

Concrètement il s'agit d'une péréquation (dans le cas présent horizontale), c'est à dire d'un mécanisme financier de redistribution des richesses par lequel les communes les plus riches sont prélevées afin d'alimenter un fond au niveau Ile-de-France ; ce fond est ensuite reversé aux communes plus pauvres.

Cet article répond au questions suivantes :
* Où apparait le FSRIF dans les comptes de la ville de Saint-Cloud ?
* Qu'est ce qu'une commune riche/pauvre au sens du FSRIF ?
* Comment est calculé le prélèvement pour Saint-Cloud ?
* Comparaison avec des communes proches : Rueil-Malmaison, Garches et Neuilly-sur-Seine.

## Montant du FSRIF

Lors du vote du budget primitif (BP), et lors du vote du budget supplémentaire (BS) le cas échéant, le conseil municipal de Saint-Cloud vote un budget global incluant la ligne comptable du FSRIF ci-dessous :

![Le FSRIF dans le budget de Saint-Cloud](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_dans_bs2021.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

En 2021, le FSRIF représente donc pour Saint-Cloud un prélèvement de 2 600 000 € voté lors du BP + 278 547 € voté lors du BS, soit un total de **2 878 547 €**.

La présentation au conseil municipal fait également état des variations du FSRIF ces dernières années.

![variation du FSRIF de Saint-Cloud](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_variation.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}


## Communes riches et pauvres d'IDF

Le FSRIF a pour objectif de redistribuer les richesses entre les communes. La première étape est d'identifier quelles communes sont considérées riches ou comme pauvres au sens du FSRIF.

Le critère est un simple seuil : les communes contributrices (c'est à dire devant être prélevées) sont toutes les communes dont le **potentiel financier par habitant** est supérieur au potentiel financier moyen par habitant des communes de la région Ile-de-France.

En 2021, le potentiel financier moyen par habitant des communes de la région Ile-de-France est de **1 544,799782 €**.

Pour connaitre le potentiel financier d'une commune, on peut aller voir dans le document Excel "critères de repartition / communes" disponible sur le site de la DGCL "Direction Générale des Collectivités locales" dans la rubrique "Critères de dotations" (voir lien en bas de page). 

En 2021, voici les potentiels financiers par habitants de 4 communes des Hauts-de-Seine :

<table border="1">
  <thead>
    <tr>
      <th>Commune</th>
      <th style="text-align: center">Potentiel financiers / hab.</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Garches</td>
      <td style="text-align: right; color: green">1 543,160512 €</td>
    </tr>
    <tr>
      <td>Saint-Cloud</td>
      <td style="text-align: right">1 942,081590 €</td>
    </tr>
    <tr>
      <td>Rueil-Malmaison</td>
      <td style="text-align: right">2 216,086698 €</td>
    </tr>
    <tr>
      <td>Neuilly-sur-Seine</td>
      <td style="text-align: right">2 359,391457 €</td>
    </tr>
  </tbody>
</table>


On constate aussi que la ville de Garches n'est pas contributrice au FSRIF, à 1 € près ! A noter que dans le cas de Garches, le solde FSRIF est de 0 € car la commune n'est pas non plus bénéficiaire du FSRIF (id est n'est pas considérée pour autant comme une comme pauvre au sens du FSRIF).

On constate que les villes de Saint-Cloud, Rueil-Malmaison et Neuilly-sur-Seine sont contributrices au FSRIF. La suite de l'article se concentre donc sur ces 3 communes.

## Détail du calcul du prélèvement

### Contribution spontannée

La contribution spontanée représente le montant de base qui doit être prélèvé sur la commune pour abonder le FSRIF, en l'absence de mécanisme de plafonnement et d'abattement.

Voici ci-après le détail des étapes de calcul de la contribution spontanée.

<u>Formule globale</u>

<i>Nombre de points de la commune = (indice synthétique de prélèvement)² * population DGF 2021</i>

<i>Contribution spontanée = Nombre de points de la commune * valeur de point</i>

<u>Formule pour l'indice synthétique de prélèvement</u>

![calcul de l'indice synthétique de prélèvement](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_calcul_indice_synthetique.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

On trouve sur le [**site officiel de la DGCL / Critères de répartition**](http://www.dotations-dgcl.interieur.gouv.fr/consultation/criteres_repartition.php), au niveau des "Caractéristiques physiques et financières par catégorie" pour "commune" la valeur des paramètres suivants dans un tableau Excel :
* en colonne H : Population DGF de la commune
* en colonne T : Potentiel financier par habitant de la commune
* en colonne DR : Revenu moyen par habitant de la commune

Lorsque l'ensemble est placé dans une feuille de calcul ce donne le résultat ci-dessous.

<u>Valeur du point</u>

La loi fixe l’objectif annuel de ressources (c'est de prélèvement) pour le FSRIF.

En 2021, la loi fixe a fixé l'objectif à 350 000 000 €.

La valeur de point correspond au rapport entre la masse à prélever et la somme du nombre de points de chaque commune. En 2021, valeur de point = 156,510942 €

<u>Mise en pratique</u>
 
 Voici le calcul de la contribution spontanée réalisé pour Saint-Cloud, Rueil-Malmaison et Neuilly-sur-Seine.


![calcul du FSRIF](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_calcul.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Voici le récapitulatif de la contribution en 2021 des 3 communes étudiées :

<table border="1">
  <thead>
    <tr>
      <th>Commune</th>
      <th style="text-align: center">Contribution spontannée</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Saint-Cloud</td>
      <td style="text-align: right">2 878 546,55 €</td>
    </tr>
    <tr>
      <td>Rueil-Malmaison</td>
      <td style="text-align: right">6 160 701,99 €</td>
    </tr>
    <tr>
      <td>Neuilly-sur-Seine</td>
      <td style="text-align: right; color: red">25 003 490,95 €</td>
    </tr>
  </tbody>
</table>

Pour les villes de Saint-Cloud et Rueil-Malmaison, ce sont ces montants de contributions spontannées que l'on retrouve dans les budgets. Il en va différemment de la ville de Neuilly-sur-Seine (voir ci-dessous).

A noter que si la ville de Garches atteignait le seuil de prélèvement (potentiel financier par habitant augmentant de 2€ par exemple), sa contribution spontanée pourrait être de l'ordre de 700 000 € (estimation). Le seuil a donc un impact important sur les finances de cette commune.

### Plafonnement

Le prélèvement du FSRIF possède plusieurs mécanismes de plafonnement et d'abattement.

Dans le cas particulier de la ville Neuilly-sur-Seine, le plafonnement qui s'applique est le suivant : le FSRIF est plafonné à 11% des dépenses réelles de fonctionnement.

Ainsi le prélèvement du FSRIF pour Neuilly-sur-Seine est plafonné à 9 316 269 € pour l'année 2021. Le plafond a donc un rôle très important pour la commune de Neuilly-sur-Seine.

## Vue d'ensemble 92

En 2021, les communes **contributrices** au FSRIF dans les Hauts-de-Seine sont les suivantes :

![Contributrice du FSRIF](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_contributrices_92.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

En 2021, les communes **bénéficiaires** du FSRIF dans les Hauts-de-Seine sont les suivantes :

![Bénéficiaires du FSRIF](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_beneficaires_92.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

On constate que le département des Hauts-de-Seine est un département riche au sens du FSRIF puisque les communes qui le composent sont largement contributrices pour alimenter ce fond de péréquation.

A titre indicatif, la contribution de la ville de Saint-Cloud correspond environ à ce que reçoit la ville de Colombes dans le cadre de ce mécanisme de redistribution sur le territoire d'Ile-de-France. Cela s'explique en partie par la différence entre les critères de redistributions ci-dessous.

![FSRIF Saint-Cloud vs Colombes](/assets/post/2021-10-14-finances-locales-fsrif/2021-09-23_fsrif_saintcloud_colombes.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

La péréquation FSRIF est au niveau Ile-de-France et ces éléments permettent de se faire une idée des ordres de grandeur des différents paramètres.

## Conclusion

On observe ainsi que le FSRIF agit bien comme un mécanisme de redistribution des richesses entre les communes d'Ile-de-France.

J'espère que cet article vous a permis de mieux comprendre le fonctionnement du fonds de solidarité des communes de la région d’Ile-de-France et de son application à la commune de Saint-Cloud.

Vous n'habitez pas Saint-Cloud, le sujet vous intéresse et vous souhaitez en savoir plus pour conduire l'analyse sur votre commune ? Je vous invite à vous rendre sur le site DGCL et lire la [**note d'information FSRIF**](http://www.dotations-dgcl.interieur.gouv.fr/consultation/informations_repartition.php) afin d'avoir tout les détails, notamment sur les mécanismes de plafonnement et par le calcul le versement aux bénéficiaires (Saint-Cloud n'étant pas concernée, ces parties n'ont pas été présentées ici). 

Source : [**DGCL - Dotations en ligne**](http://www.dotations-dgcl.interieur.gouv.fr/consultation/dotations_en_ligne.php)

