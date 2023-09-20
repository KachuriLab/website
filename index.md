---
---

# KachuriLab's Website

A 1-3 sentence description of your lab.

{% include section.html %}

## Highlights


{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/publications.png"
  link="publications"
  title="Our Lab Publications"
  text=text
%}


{% capture text %}
**Research** Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
{%
  include button.html
  link="research"
  text="Browse research projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/projects.png"
  link="research"
  title="Our Research Projects"
  style="bare"
  text=text
%}


{% capture text %}
**TEAM** Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
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
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}
