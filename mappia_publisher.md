---
layout: mappia_publisher
title: Learn how to publish interactive Maps online.
tagline: We will add all the plugins created here

permalink: /mappia_publisher/
hasYoutube: true
apiConfig:
  startPropertiesOpen: true
---
<div class="container"> 
  {% assign api = '' | split: '' %}
  {% for apiHash in site.data.api %}
    {% assign api = api | push: apiHash[0] %}
  {% endfor %}
  {% include api.html api=api %}
</div>
 
