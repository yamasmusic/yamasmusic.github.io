---
title: Gallery - גלריה
layout: page
position: 3
images:
    - hilton-tlv.jpg
    - masik.jpg
    - yamas-black.jpg
    - yamas-elevator.jpg
    - yamas-stairs.jpg
    - show-eyal-2.jpg
    - show-eyal.jpg
    - show-udi.jpg
    - show-uri-2.jpg
    - show-uri.jpg
    
---
{% for image in page.images %}
  ![](gallery/{{ image }})
{% endfor %}
