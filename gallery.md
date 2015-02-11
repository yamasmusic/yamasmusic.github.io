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
---
{% for image in page.images %}
  ![](gallery/{{ image }})
{% endfor %}