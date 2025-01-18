---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html background="images/background.jpg" dark=true %}


We are always looking for highly motivated students with an interest in vision, learning, and/or computational modeling. If that's you, here's more information on how to apply.

{% include button.html icon="fa-solid fa-handshake-angle" text="Join the Team" link="join" style="button" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: phd, group: alumn" stile="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alumn" stile="small" %}