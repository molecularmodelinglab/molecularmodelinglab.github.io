---
title: Lab Members
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Lab Members


{% capture content %}

{%
  include button.html
  text="Current Members"
  link="team/#current-members"
  style="button"
%}

{%
  include button.html
  text="Collaborators"
  link="team/#collaborators"
  style="button"
%}

{%
  include button.html
  text="Alumni"
  link="team/#alumni"
  style="button"
%}

{% endcapture %}

{% include qrid.html style="buttons" content=content %}

## Current Members

Our lab is a team of highly skilled interdisciplinary scientists and scientists-in-training. Cheminformatics is a field
that requires effective and clear communication between a wide array experts in different areas, from biology to 
synthetic chemistry. We work to approach our work from as many different viewpoints as possible so that it is the most
impact to our colleagues that utilize it.

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: assistant_prof, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: intern, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{:.center}

{% include section.html dark=true %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives.
We want to push the frontier of data science and train the next generation of data scientists.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="&nbsp;Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Collaborators 

As computer loving people, we don't often get to see the insides of chemical lab. Instead, in the pursuit safety, we 
leave this work up to out lovely collaborators, both at UNC and across the globe and experts in all various domains. 
We also collaborate closely with several other computational groups and companies. 

{% include list.html data="members" component="portrait" filters="role: pi, group: colab" style="small" %}
{% include list.html data="members" component="portrait" filters="role: adjunct, group: colab" style="small" %}
{% include list.html data="members" component="portrait" filters="role: org, group: colab" style="small" %}

{% include section.html %}

## Alumni

Alumni from the MML have found success at all kinds of futures, from academic to industrial.
These are past lab members who have moved on for our group to further innovate elsewhere

{% include list.html data="members" component="portrait" filters="role: assistant_prof, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: intern, group: alum" style="small" %}

{% include section.html %}

{%
  include figure.html
  image="images/lab_photo.jpg"
  caption="The MML managed to have 60% attendance on picture day (NEW RECORD!)"
  width="100%"
%}
