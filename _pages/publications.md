---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2022, 2023, 2024, 2025]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>


<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### Conference Proceedings
{% bibliography --query @inproceedings %}
</div>


<div class="jumbotron">
### Journal articles
{% bibliography --query @article %}
</div>





