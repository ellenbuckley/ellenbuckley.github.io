---
---

# The Buckley Lab at University of Illinois



{% include section.html %}

## Highlights

{% capture text %}

Read about some of the missions, data, and problems that inspire our work and check out our publications.
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
  image="images/dms.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Learn more about the people (and pets) that make up our research group.

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
  image="images/marvin_office.png"
  flip=true
  link="team"
  title="Our Team"
  text=text
%}

{% capture text %}

See what products we have created.

{%
  include button.html
  link="projects"
  text="Check out projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/fsd.png"
  link="projects"
  title="Check out our projects"
  style="bare"
  text=text
%}

{% capture lab_text %}
**Lab Expectations.** In this group, I expect everyone to take ownership of their educational and research experiences, to think about their work in the context of long-term career goals, and to contribute to a supportive, collaborative environment where colleagues are not competitors. Respect, inclusivity, and a zero-tolerance policy for harassment or discrimination are central to our group and community. We will not tolerate any verbal or physical harassment or discrimination on the basis of gender, gender identity and expression, sexual orientation, disability, physical appearance, race, or religion. A full list of lab member expectations can be found <a href="{{ '/docs/BuckleyLabExpectations.pdf' | relative_url }}">here</a>. 
{% endcapture %}

{% include section.html %}
<div class="prose">
  {{ lab_text | markdownify}}
</div>
{% include section.html %}




