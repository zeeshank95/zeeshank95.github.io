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

Hi! I am a first year PhD student in the <a href="http://www.di.ens.fr/willow">Willow</a> team at <a href="https://www.inria.fr/en">Inria</a> and  <a href="https://www.ens.psl.eu/en">École Normale Supérieure</a> in Paris, advised by <a href="https://antoyang.github.io">Antoine Yang</a>, <a href="https://www.di.ens.fr/~laptev/">Ivan Laptev</a> and, <a href="https://www.di.ens.fr/willow/people_webpages/cordelia/">Cordelia Schmid</a>. I will be working in vision-language models for Video Understanding. 

I did my Masters by Research in Computer Science with a specalization in AI from <a href="http://cvit.iiit.ac.in">CVIT IIIT Hyderabad</a> advised by <a href="https://faculty.iiit.ac.in/~jawahar/index.html">C.V. Jawahar</a> and <a href="https://makarandtapaswi.github.io">Makarand Tapaswi</a>. My thesis was on Situation Recognition for Holistic Video Understanding.

Prior to this I was a Research Assistant in the Computer Vision lab at <a href="https://iitgn.ac.in">IIT Gandhinagar</a>, advised by <a href="https://people.iitgn.ac.in/~shanmuga/"> Shanmuganathan Raman</a>. I worked in Computational Photography specifically in high dynamic range image and video reconstruction and generative modeling in appearance consistent human pose transfer.  

I am interested in holistic video representation learning, and its application in both vision-language perception and generation. I I aim at building machines that can interact with the real world, possessing multimodal sensing abilities, long term spatio-temporal reasoning, and the ability to generate natural language.

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


