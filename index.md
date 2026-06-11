---
layout: home
---

# 📚 Bienvenidos a Lecturas Mágicas

Este es un espacio personal donde comparto poemas, cuentos y libros que me encantan para leer con los más pequeños. 

## 📖 Últimas lecturas:

{% for post in site.posts %}
- **[{{ post.title }}]({{ site.baseurl }}{{ post.url }})**
  *Autor: {{ post.author }} | Recomendado para: {{ post.edad_recomendada }}*
  {{ post.excerpt }}
{% endfor %}
