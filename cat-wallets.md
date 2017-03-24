---
layout: page
title: "Altcoin Wallets"
description: "Wählen Sie Wallet für Ihre Altcoins. Auch Hardware-Wallets unterstützen jetzt Ethereum, DASH und ZCASH."
permalink: /category/wallets/
---

<p>{{ site.ads.trezorlong }}</p>

<span id="note">"Altcoin wallets"</span>

{% for post in site.posts %}
  {% if post.category contains "wallets" or post.categories contains "wallets" %}
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
          <amp-img itemprop="image" src="{{ post.image[0] }}" alt="Alt Coin Wallet" layout=""
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
