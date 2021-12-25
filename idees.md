---
layout: rm_post
title: "Idées"
subtitle: "Propositions & Prises de position"
header-img: assets/img/idees/thumbnail.jpg
---
# Idées pour Saint-Cloud

![texte alternatif à l'image](/assets/img/idees/thumbnail2.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Vous êtes concerné par une problématique et vous souhaiter qu'on échange ensemble pour co-construire une solution concrète ? Je suis à votre disposition.

## Mes propositions pour Saint-Cloud

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.categories.idee offset:0 limit:9 %}
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


