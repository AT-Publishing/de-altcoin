---
layout: page
title: "Börsen"
description: "Wo man Kryptowährung kaufen und handeln kann, wie hoch sind die Gebühren."
permalink: /category/exchanges/
---

<p>{{ site.ads.aads728 }}</p>

<span id="note">"Altcoinbörsen"</span>

{% for post in site.posts %}
  {% if post.category contains "exchanges" or post.categories contains "exchanges" %}
  <h4 class="post">
  <strong>
  <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title | capitalize }}</a>
  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <div class="row">

    <div class="nine columns">
      {{ post.description }}
    </div>

    {% if post.image[0] %}
    <div class="three columns">
      <a target="_blank" href="{{ post.url }}">
        <figure class="thumb">
          <amp-img itemprop="image" src="{{ post.image[0] }}" alt="Altcoin Trading Blog" layout=""
          width="150px" height="80px">
          </amp-img>
        </figure>
      </a>
    </div>
    {% endif %}



  </div>

  {% endif %}
{% endfor %}

{{ site.ads.aads728 }}
