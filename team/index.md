---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The DRACO lab is brand new to UCF so we're growing and looking for undergraduate and graduate researchers alike to join us. While we're new, we're dedicated to building a diverse, collaborative, and supportive research team. Our team works hard, welcomes those who want to engage in research and outreach, and above all we treat each other with respect and support one another in our similarities and unique differences.

{% include tags.html tags="role: director, phd, ms, undergrad, capstone-senior" %}

{% include search-info.html %}

{% include section.html %}
## Director

{% include list.html data="members" component="portrait" filters="role: director, group:" %}


{% include section.html %}
## Graduate Student Researchers

{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: ms, group: " %}

{% include section.html %}
## Undergraduate Students

{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}


{% include list.html data="members" component="portrait" filters="role: capstone-senior, group: " %}

{% include section.html %}

{% include section.html background="images/background.jpg" dark=true %}

## Join Us
Are you interested in joining us as a researcher, developer, or supporter? We're looking to push the envelope of design automation for semi-conductor technologies of the future - from design, to verification, to test, we're interesting in developing algorithms and software that increase the development, security, and resilence of next-generation devices.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join DRACO"
  link="join"
  style="button"

%}

{% include section.html %}

## Funding and Support

The work, projects, publications, materials, and members represented have been funded by a variety of federal, state, local, and corporate entitied. We are greatful for their support and look forward to continuing to develop mutually beneficial relationships. Have a project you're interesting in supporting? Contact [Dr. Mike]({{ site.baseurl }}/contact).

{% capture content %}

 {% include figure.html image="images/sponsors/nsf.png"   link="http://nsf.gov" %}
{% include figure.html image="images/sponsors/nsa.png" link="http://nsa.gov" %}
{% include figure.html image="images/sponsors/gencyber.jpg" link="http://gen-cyber.com" %} 
{% include figure.html image="images/sponsors/doe.png" link="http://energy.gov"%} 
{% include figure.html image="images/sponsors/inl.png" link="http://inl.gov"%} 
{% include figure.html image="images/sponsors/iog.png" link="http://iog.io" %} 
{% include figure.html image="images/sponsors/kraken.png" link="http://kraken.com"%} 
{% include figure.html image="images/sponsors/ripple.png" link="http://ripple.com" %} 


{% endcapture %}

{% include grid.html style="square" content=content %}
