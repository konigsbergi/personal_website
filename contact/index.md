---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

I am a research instructor in the Department of Biomedical Informatics at
the University of Colorado - Anschutz Medical Campus. Please feel free to 
contact me 

{%
  include button.html
  type="email"
  text="iain.konigsberg@gmail.com"
  link="iain.konigsberg@gmail.com"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Anschutz+Health+Sciences+Building/@39.7454762,-104.8444678,17z/data=!3m1!4b1!4m6!3m5!1s0x876c633a9c45be13:0x85f675e778fce18c!8m2!3d39.7454721!4d-104.8418929!16s%2Fg%2F11pzx9tmvh?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
