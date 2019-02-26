---
title: "People"
layout: default
---
{% for member in site.people %}

<article class="project">
  <div><strong>First name:</strong> {{ member.first_name }}</div>
  <div><strong>Family name:</strong> {{ member.family_name }}</div>
  <div><strong>E-Mail:</strong> {{ member.email }}</div>
  <div><strong>Web-site:</strong> {{ member.web }}</div>
  <div>
    <strong>Description:</strong>
    {{ member.content }}
  </div>
</article>

{% endfor %}
