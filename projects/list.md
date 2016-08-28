---
layout: default
title: Berkshires Technology Group
projects:
 - kickstarter
 - robot
---
<p>This is a list of our projects that we have worked on:</p>
<ul>
{% for project in page.projects %}
  <li><a href='/projects/{{ project }}'>{{ project | capitalize}}</a></li>
{% endfor %}
</ul>
