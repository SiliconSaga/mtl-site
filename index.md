---
layout: page
title: Mountain Top League
---

The Mountain Top League is an all-volunteer organization which has served the
children of West Orange, NJ since it was founded in 1959. We offer recreational
sports programs focused on sportsmanship, skill development, and fun.

## Our Sports

<div class="sport-grid">
{% for sport in site.data.sports %}
  <a href="{{ site.baseurl }}/{{ sport.slug }}/" class="sport-card">
    {{ sport.name }}
  </a>
{% endfor %}
</div>

## Soccer Season

MTL Soccer serves over 1,000 children across spring, summer, and fall seasons.
Our program emphasizes sportsmanship and fostering a love for the game through
volunteer coaches and commissioners.

[View Soccer Programs &rarr;]({{ site.baseurl }}/soccer/)

## Get Involved

MTL is run entirely by volunteers. If you're interested in coaching, refereeing,
or helping out, reach out at [MTLsoccer@gmail.com](mailto:MTLsoccer@gmail.com)
or visit our [Contact page]({{ site.baseurl }}/contact/).
