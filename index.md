---
---

# Welcome 

The DRACO Lab is a new and growing group of researchers at the University of Central Florida (UCF) focused on providing research-driven automated tools and techniques for the resilient design, development, and evaluation of tomorrow's electronic semi-conductor devices. 

{% include section.html %}

## News and Events

{% include list.html data="posts" component="post-excerpt" filters="tag: events, tag:news"%}



{% include section.html %}

## Highlights

{% capture text %}

We develop algorithms and processes to automatically design, develop, and assess the resilence, robustness, security electronic devices and systems. Our research includes topics at various stages of investigation:  advanced/novel cryptographic logic primatives (polymorphic, homomorphic, quantum-enhanced), symbiosis of AI designed constructs for AI applications, assessment and evalution of assitive technologies on  semiconductor design and post-manufacturing opperation, and developement and detection methods for AI-based sabbotage. 

All of our research and nearly all of our (~100) publications and presentations involve students. Also, most feature undergraduate and graduates as authors!
 
{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We work on a broad range of projects, funded by various federal and industry partners, while much of our work is open source, some of our work may remain embargoed or partially-redacted when neccesary.

We have opportunities for undergraduate (paid or experiential based on interest and time commitment) and graduate research (funded). Our research projects are tightly coupled with the topics listed above, but we also sponsor more applied projects which may be of interest to Senior Design Teams.


{%
  include button.html
  link="projects"
  text="Check out our active, available, and archived projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We're an open, collaborative, and welcoming group - if you're excited and want to be an active contributor to DRACO - check out some of our active projects above, current lab members below, and then read about how to [join us]({{ site.baseurl }}/join)!

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Meet the team!"
  text=text
%}
