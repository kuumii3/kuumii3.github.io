---
title: Discografía Rojuu

---

# Discografía Rojuu


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for persona in site.data.personas %}
  # Nombre: {{ persona.nombre }} - Año: {{ persona.year }} - Canciones {{ persona.canciones }}
{% endfor %}