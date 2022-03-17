---
layout: rm_index
title: "Accueil"
subtitle: "Élu à Saint-Cloud"
header-img: assets/img/index_overview.jpg
---

## Actualité
Voici les 4 derniers articles. Pour plus d'articles, se rendre dans la rubrique associée.

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.posts offset:0 limit:5 %}
        {% unless post.categories contains "tribune_saint_cloud_2020" %}
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
        {% endunless %}
    {% endfor %}
</div>

# Tribunes

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.categories.tribune_saint_cloud_2020 offset:0 limit:20 %}
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