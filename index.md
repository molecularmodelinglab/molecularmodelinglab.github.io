---
title: Home
---

# Supporting Drug Discovery with Data Science

The Molecular Modeling Lab (MML) at UNC Chapel Hill Eshelman School of Pharmacy works at the intersection of 
pharmaceutical development and data science to accelerate the discovery of novel drugs. Our focus is split between 
development of open source, innovative computational methods and applications of such methods in tangible discovery 
campaigns. 

{%
  include link.html
  type="github"
  icon=""
  text="Checkout our GitHub"
  link="molecularmodelinglab"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon="fa-solid fa-prescription"
  text="UNC Eshelman School of Pharmacy"
  link="https://pharmacy.unc.edu/"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/lab_photo.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
We use machine learning and data science to investigate the relationship between chemicals and their various biological
activities. We strive to not only make advancements in methodology, but to develop robust workflows for using these
tools. 

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/reserach.jpg"
  link="research"
  title="QSAR and Cheminformatics"
  text=text
%}

{% capture text %}
Tools are useless if no one can use them. All of our tools and code is freely available for anyone to utilize and build
upon. Further, many of our tools have easy to use web interfaces to enhance accessibility for the public.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/talking.jpg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
We are a group of diverse researchers with a broad range academic backgrounds. Our team is able to approach problems from 
multifaceted viewpoints to increase the robustness of our solutions.

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/thing.jpg"
  link="team"
  title="Our Team"
  text=text
%}

If you're interested in joining the MML, [click here!](join)
