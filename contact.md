---
layout: default
title: contact
subtitle: Say Hi!
fineprint: use the form below
---
<br>
  <div class="btn-group" >
    {% for item in site.data.contact %}
      <a href="{{ item.url }}" class="btn btn-outline-light">{{item.name}}</a>
    {% endfor %}
  </div>
<br>
{% include contact_form.html %}
