---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
software engineer with 5 years of experience in software development using the newest technologies
and best design patters. This blog includes my own reflections and experiences regarding software
development and related topics drawn from my work, personal projects and elsewhere. It also serves
as a place where i can record lessons learned and other interesting tidbits.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
