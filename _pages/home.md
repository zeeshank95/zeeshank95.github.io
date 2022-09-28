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

I am an MS by research student at <a href="http://cvit.iiit.ac.in">CVIT, IIIT Hyderabad</a> deeply interested in Multimodal Deep Learning. Currently, I am working on dense video understanding involving vision, language, and people in challenging situations like movies. I am also working on Multilingual and Multimodal Neural Machine Translation. I am advised by <a href="https://faculty.iiit.ac.in/~jawahar/index.html">C.V. Jawahar</a>, <a href="https://makarandtapaswi.github.io">Makarand Tapaswi</a> and, <a href="https://vinaypn.github.io"> Vinay Namboodiri</a> at <a href="https://www.iiit.ac.in">IIIT Hyderabad</a>. Prior to this I was a Research Assistant in the Computer Vision lab at <a href="https://iitgn.ac.in">IIT Gandhinagar</a>, where I worked in Computational Photography and Generative Modelling, I was advised by <a href="https://people.iitgn.ac.in/~shanmuga/">Prof. Shanmuganathan Raman</a>. 

With a diverse research experience in multiple domains, I aim at building machines with multimodal sensing abilities that can understand and connect fine-grained aspects of long videos, like objects, humans, actions, intentions, location, emotions, and story plots.

<p align="center">
  <a href="./docs/Zeeshan_cv_2022.pdf">CV</a> /
  <a href="https://scholar.google.com/citations?user=uvhBVYoAAAAJ&hl=en">Google Scholar</a> /
  <a href="https://github.com/zeecoder606">Github</a> /
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


