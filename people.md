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
  <div><strong> Social links </strong>
     <div><strong>dblp:</strong> {{ member.dblp }}</div>
     <div><strong>orcid:</strong> {{ member.orcid }}</div>
    <div><strong>googlescholar:</strong> {{ member.googlescholar }}</div>
    <div><strong>bitbucket:</strong> {{ member.bitbucket }}</div>
    <div><strong>github:</strong> {{ member.github }}</div>
    <div><strong>stackoverflow:</strong> {{ member.stackoverflow }}</div>
    <div><strong>twitter:</strong> {{ member.twitter }}</div>
    <div><strong>orcid:</strong> {{ member.orcid }}</div>
    <div><strong>orcid:</strong> {{ member.orcid }}</div>
  </div>
  <div>
    <strong>Bio:</strong>
    {{ member.content }}
  </div>
</article>

{% endfor %}
