---
title: members

---

# Members


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for album in site.data.albumes %}
  ## {{ album.nombre }} - {{ album.year_lanzamiento }} - {{ album.numero_canciones }} - {{ album.genero_musical }}
{% endfor %}