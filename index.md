---
layout: rm_index
title: "Accueil"
subtitle: "Élu à Saint-Cloud"
header-img: assets/img/index_overview.jpg
---
**SITE EN CONSTRUCTION**

## Actualité
Voici les 4 derniers articles. Pour plus d'articles, se rendre dans la rubrique associée.

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.posts offset:0 limit:4 %}
        <div class="row" style="margin-top:10px;">
            <div class="col-5">
                <img src="{{ post.header-img }}" width="100%" height="90px" class="img-fluid rounded">
            </div>
            <div class="col-7">
                <a href="{{ post.url }}">{{ post.title }}</a><br>
                {{ post.date | date_to_french }}<br>
                <b>&rarr;</b> <i>{{ post.subtitle }}</i>
            </div>
        </div>
    {% endfor %}
</div>

Sur cette page :
* Ma bio en bref (Père de famille, 36 ans, Val d'or, Ingénieur, acteur associatif)
* Formulaire de contact
* Présence sur les réseaux sociaux


