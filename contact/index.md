---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

{%
  include link.html
  type="email"
  icon=""
  text="zhaoxinf@andrew.cmu.edu"
  tooltip=""
  link="zhaoxinf@andrew.cmu.edu"
  style="button"
%}

{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

PAPittsburgh 5000 Forbes Ave, 15213
USA
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Center for Wit and Sagacity"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Metaphor"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
