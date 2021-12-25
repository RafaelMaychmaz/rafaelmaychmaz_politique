---
layout: rm_post
title: "Action"
subtitle: "L'action de Rafaël Maychmaz, conseiller municipal à Saint-Cloud"
header-img: assets/img/action/thumbnail.png
---
# Mon Action

![texte alternatif à l'image](/assets/img/action/thumbnail.png "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Sur cette page :
* Mes prises de position au Conseil Municipal
* Ma participation aux CCAS
* Ma présence dans Saint-Cloud aux côtés des acteurs locaux et des habitants
* Mon bilan annuel
* Vulgarisation du fonctionnement de la commune et du rôle/des missions d'un conseiller municipal d'opposition

Vous êtes concerné par une problématique et vous souhaitez qu'on échange ensemble pour co-construire une solution concrète ? Je suis à votre disposition.

## Mes prises de position au Conseil Municipal
Liste des articles à ce sujet
* 2020 : Fiscalité : Pour mettre en place une surtaxe d'habitation sur les résidences secondaires à Saint-Cloud
* 2020 : Egalité F/H : Pour un rapport de situation en matière d'égalité F/H pour la ville
* 2020 : Mobilitées douces : Pour des pistes cyclables sécurisées Rue Dailly / Rue du Calvaire / Avenue André Chevrillon en dimmensionnant le futur parking de manière à pouvoir supprimer du stationnement de surface.
* 2021 : Mobilitées douces : RD7 / Pour une piste cyclable côté Seine (avis déposé auprès du commissaire enquêteur pour l'enquête publique)
* 2021 : Urbanisme : Pour un meilleur usage de la parcelle de l'ancien site Cap Gemini.
* 2021 : Petite enfance : pour une étude d'impact sur la prime au 3ème enfant et pour une reflexion sur cette ligne budgétaire
* 2021 : Egalité F/H : Pour une meilleure représentation des femmes dans les noms de rues et lieux publics
* 2021 : Egalité F/H : Charte européenne pour l'égalité F/H dans la vie locale

## Ma participation au CCAS
Qu'est ce que le CCAS, qui y participe, qu'est-ce qu'il s'y passe ?

## Ma présence à vos côtés
Grand débat

Merci à nos commerçants

Sur le terrain

## Mon bilan annuel
2020 : apprentissage (x votes POUR, y votes ABS, z votes CONTRE)

2021 : nouveaux sujets (x votes POUR, y votes ABS, z votes CONTRE)

## Comprendre la vie municipale
Comment est structuré un conseil municipal

Quel est le rôle d'un élu d'opposition

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.categories.formation offset:0 limit:9 %}
        <div class="row" style="margin-top:10px;">
            <div class="col-5">
                <img src="{{ post.header-img }}" width="100%" height="90px" class="img-fluid rounded">
            </div>
            <div class="col-7">
                <a href="{{ post.url }}">{{ post.title }}</a><br>
                {{ post.date | date_to_french }}
            </div>
        </div>
    {% endfor %}
</div>



