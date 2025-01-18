---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [Department of Psychology](https://case.fiu.edu/psychology/) at [Florida International University](https://www.fiu.edu/). Our research takes part at multiple locations in the [MMC Campus](https://www.fiu.edu/locations/mmc/index.html), but mostly in the 2nd floor of the Deuxieme Maison (DM) building.

{%
  include button.html
  type="email"
  text="fasoto@fiu.edu"
  link="fasoto@fiu.edu"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/fTBcWQCUFThaPYYY8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/dm.jpg"
  caption="DM building (data collection)"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/ahc4.jpg"
  caption="AHC4 building (office space)"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/ahc5.jpg"
  caption="AHC5 building (office space)"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}


