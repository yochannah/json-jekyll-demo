---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# My cats:

{% for kitty in site.data.cats %}

 ## A cat! 🐈‍⬛
 
 **Name:** {{kitty.cats.name}}
 
 **Colour:** {{kitty.cats.color}}

{% endfor %}
