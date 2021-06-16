---
title: "Research team"
layout: single
classes: wide
permalink: /team/
---

TU Delft and MIT will collaborate in order to create synergies with the expertise from each side.
TU Delft has expertise in autonomous shipping (Negenborn, Haseltalab), fleet management (Atasoy, Beirigo), robotics and data-driven methodologies for autonomy (Alonso-Mora, Babuska).
Department of Maritime and Transport Technology at TU Delft is well recognized in the domain of ship design and concepts for intermodal transport and logistics.
On the MIT side expertise on urban planning (Duarte) together with artificial intelligence and robotics (Rus) has a both complementing and reinforcing nature.


<div class="grid__wrapper">
    {% for author_hash in site.data.authors %}
    {% assign author = author_hash[1] %}
    {% assign affiliation = "TU Delft" %}
    {% include author-cell.html %}
    {% endfor %}
</div>
