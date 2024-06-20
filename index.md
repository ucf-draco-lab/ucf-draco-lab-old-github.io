---
---

# Welcome 

Welcome to the Design of Resilient Architectures for Computing (DRACO) lab website. We're a part of the [Electrical and Computer Engineering Department](http://ece.ucf.edu) at the [University of Central Florida](http://ucf.edu) located in spectacular Orlando, Florida.


{% include section.html %}

{% capture text %}

We develop algorithms and processes to automatically design, develop, and assess the resilience, robustness, security electronic devices and systems. Our research includes topics at various stages of investigation:  advanced/novel cryptographic logic primitives (polymorphic, homomorphic, quantum-enhanced), symbiosis of AI designed constructs for AI applications, assessment and evaluation of assistive technologies on  semiconductor design and post-manufacturing operation, and development and detection methods for AI-based sabotage. 

All of our research and nearly all of our (~100) publications and presentations involve students. Also, most feature undergraduate and graduates as authors!
 
{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-left"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research/research-highlight.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We work on a broad range of projects, funded by various federal and industry partners, while much of our work is open source, some of our work may remain embargoed or partially-redacted when necessary.

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
  image="images/projects.png"
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
  icon="fa-solid fa-arrow-left"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/meet-the-team.jpg"
  link="team"
  title="Meet the team!"
  text=text
%}
