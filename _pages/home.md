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

Hi! I am a second year PhD student in the <a href="http://www.di.ens.fr/willow">Willow</a> team at <a href="https://www.inria.fr/en">Inria</a> and  <a href="https://www.ens.psl.eu/en">École Normale Supérieure</a> in Paris, advised by <a href="https://cordeliaschmid.github.io">Cordelia Schmid</a> and <a href="https://cshizhe.github.io">Shizhe Chen</a>. I am working on Diffusion models for vision-language generation. 

I did my Masters by Research in Computer Science from <a href="http://cvit.iiit.ac.in">CVIT IIIT Hyderabad</a> advised by <a href="https://faculty.iiit.ac.in/~jawahar/index.html">C.V. Jawahar</a> and <a href="https://makarandtapaswi.github.io">Makarand Tapaswi</a>. My thesis was on Situation Recognition for Holistic Video Understanding, exploring structured representations to enable deeper semantic understanding of dynamic scenes. Prior to this I was a Research Assistant in the Computer Vision lab at <a href="https://iitgn.ac.in">IIT Gandhinagar</a>, where I worked with <a href="https://shanmuga.people.iitgn.ac.in"> Shanmuganathan Raman</a>. My work centered around Computational Photography, specifically in high dynamic range (HDR) image and video reconstruction.

I am broadly interested in unified large multimodal diffusion models particularly at the intersection of vision and language for joint understanding and generation across text, images, and videos. Currently I am exploring compositional representations for high fidelity and interpretable text-to-image/video diffusion models.

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

<div class="col-sm-4" style="display:table-cell; vertical-align:left; text-align:left">

  <div class="text-left">
  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_pic.jpeg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->
  <A HREF="mailto:zeeshan.khan@inria.fr">zeeshan.khan@inria.fr</A> <br>
  Office: C-412<br>
  Address: 2 Rue Simone IFF, 75012 Paris France<br>

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


