---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
To be short and clear I am a computer science enthusiast and I am curious about almost everything there exist when it comes to the field of web development. I have worked my ass around on understanding how the web has evolved and where it will take me to in the near future.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
