---
layout: default
title: {{ page.date | date_to_string }}
subtitle: {{ page.author | capitalize }}
fineprint: {{ page.date | date_to_string }}
---
<p class="lead">{{ page.date | date_to_string }} - <small class="text-muted">{{ page.author | capitalize }}</small></p>

{{ content }}
