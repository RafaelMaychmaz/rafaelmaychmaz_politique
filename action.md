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

### 2022 : Loi 3DS
Reforme territorial : les apports de la loi 3DS (Decentralisation, Différentiation, Déconcentration, Simplification) pour Saint-Cloud et à l'échelle du territoire.

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/X2hr45-fSJI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### 2022 : Logement social : Attachement à la loi SRU.

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/6xIo0VzErek" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### 2021 : Egalité F/H : Charte européenne pour l'égalité F/H dans la vie locale

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/ctpoPzaTz7g" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### 2021 : Egalité F/H : Féminisation des noms de rues
Pour une meilleure représentation des femmes dans les noms de rues et lieux publics

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/BWfFmGP41xM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### 2021 : Petite enfance : Prime au 3ème enfant
Pour une étude d'impact sur la prime au 3ème enfant et pour une reflexion sur cette ligne budgétaire

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/56UtBGXXzWU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### 2021 : Urbanisme : parcelle ex Capgemini
Pour un meilleur usage de la parcelle de l'ancien site Cap Gemini.

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/SXkC0KsKXOU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### 2021 : Mobilitées douces : RD7 / Pour une piste cyclable côté Seine
Pas de vidéo disponible.

*En résumé : avis déposé auprès du commissaire enquêteur pour l'enquête publique.*

### 2020 : Mobilitées douces : Dailly / Calvaire / Chevrillon
Pas de vidéo disponible.

*En résumé : Pour des pistes cyclables sécurisées Rue Dailly / Rue du Calvaire / Avenue André Chevrillon en dimmensionnant le futur parking de manière à pouvoir supprimer du stationnement de surface.*


### 2020 : Egalité F/H : Rapport de situation à Saint-Cloud

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/-2_JzBdtODk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### 2020 : Fiscalité : Taxe d'habitation / surtaxe sur les résidences secondaires

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/hYei9RRt5g4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### 2020 : Commerces : Aides aux commerçants (Covid)

<div style="text-align: center">
<iframe
width={{ site.data.navigation.youtube_width }}
height={{ site.data.navigation.youtube_height }}
src="https://www.youtube.com/embed/9p0nBOk5yPY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


## Ma participation au CCAS
*En cours de construction*

Qu'est ce que le CCAS, qui y participe, qu'est-ce qu'il s'y passe ?

## Ma présence à vos côtés
*En cours de construction*

Grand débat / Opération "Merci à nos commerçants" / Présence sur le terrain

## Mon bilan annuel

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.categories.action offset:0 limit:20 %}
        {% if post.tags contains "bilan" %}
            <div class="row" style="margin-top:10px;">
                <div class="col-5">
                    <img src="{{ post.header-img }}" width="100%" height="90px" class="img-fluid rounded">
                </div>
                <div class="col-7">
                    <a href="{{ post.url }}">{{ post.title }}</a><br>
                    {{ post.date | date_to_french }}
                </div>
            </div>
        {% endif %}
    {% endfor %}
</div>

## Comprendre la vie municipale

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

*En cours de construction*

Fonctionnement du conseil municipal

Le rôle d'un élu d'opposition

## Autres articles

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.categories.action offset:0 limit:20 %}
        {% unless post.tags contains "bilan" %}
            <div class="row" style="margin-top:10px;">
                <div class="col-5">
                    <img src="{{ post.header-img }}" width="100%" height="90px" class="img-fluid rounded">
                </div>
                <div class="col-7">
                    <a href="{{ post.url }}">{{ post.title }}</a><br>
                    {{ post.date | date_to_french }}
                </div>
            </div>
        {% endunless %}
    {% endfor %}
</div>


