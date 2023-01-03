---
title: "Zeeshan Khan - Home"
layout: gridlay
excerpt: "Zeeshan Khan"
sitemap: false
permalink: /
---

<div class="container-fluid">

<div class="row">

<div class="col-sm-8">

Hi!! I am a MS research student in Computer Science at <a href="http://cvit.iiit.ac.in">CVIT IIIT Hyderabad</a> advised by <a href="https://faculty.iiit.ac.in/~jawahar/index.html">C.V. Jawahar</a> and <a href="https://makarandtapaswi.github.io">Makarand Tapaswi</a>. My research is focused on holistic video understanding. It involves vision-language interaction for jointly modeling multi-event action recognition, fine-grained human-object semantic relation reasoning, spatio-temporal grounding, and coreferencing of humans and entities in long videos. 

Prior to this I was a Research Assistant in the Computer Vision lab at <a href="https://iitgn.ac.in">IIT Gandhinagar</a>, advised by <a href="https://people.iitgn.ac.in/~shanmuga/"> Shanmuganathan Raman</a>. I worked in Computational Photography specifically in high dynamic range image and video reconstruction and, generative modeling in appearance consistent human pose transfer.  

I am interested in vision-language interaction in a self-supervised setting, for scalable holistic video representation learning that can capture actions, entities with their semantic roles, and their relations over time. With a goal of achieving human like cognition abilities for machines, I aim at building machines that can interact with the real world possessing multimodal sensing abilities, long term spatio-temporal reasoning, and the ability to generate natural language.

<p align="center">
  <a href="./docs/Zeeshan_cv_2022.pdf">CV</a> /
  <a href="https://scholar.google.com/citations?user=uvhBVYoAAAAJ&hl=en">Google Scholar</a> /
  <a href="https://github.com/zeeshank95">Github</a> /
  <a href="https://www.linkedin.com/in/khan-zeeshan-606-">LinkedIn</a> /
</p>

### News
****
{% for article in site.data.news limit:5 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
#### <a href="{{ site.url }}{{ site.baseurl }}/allnews.html">See all news</a>

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:left">

  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_pic.jpeg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->

  <A HREF="mailto:zeeshan.khan@research.iiit.ac.in">zeeshan.khan@research.iiit.ac.in</A> <br>
  CVIT-IIIT Hyderabad, India.<br>


</div>

</div>
</div>

<div class="col-sm-12">

### Publications
****

{% for publi in site.data.publist limit:10 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="250px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">See all publications</a>

</div>


