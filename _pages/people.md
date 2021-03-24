---
title: People
permalink: "/people"
layout: page
menubar: people_menu
show_sidebar: false
hero_height: is-fullwidth
---

## Project Team

(In alphabetical order)

{% for member in site.data.team %}
**{{ member.name }}**  
{{ member.title }}
{% endfor %}  

### Contact

Get in touch by emailing us at **{{ site.email }}**.
