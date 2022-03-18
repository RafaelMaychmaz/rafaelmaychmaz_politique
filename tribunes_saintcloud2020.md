---
layout: rm_post
title: "Tribunes municipales"
subtitle: "Liste investie par la majorité présidentielle d'Emmanuel Macron."
header-img: assets/img/action/thumbnail.png
---
# Tribunes de notre groupe municipal

Voici nos tribunes parues chaque mois dans le *Saint-Cloud Mag'*, magazine officiel de la ville. *Saint-Cloud 2020!* est le nom de la liste investie par la majorité présidentielle d'Emmanuel Macron aux municipales 2020 à Saint-Cloud.

<div class="container" style="margin-top:10px; margin-bottom:10px;">
    {% for post in site.categories.tribune_saint_cloud_2020 offset:0 limit:240 %}
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
