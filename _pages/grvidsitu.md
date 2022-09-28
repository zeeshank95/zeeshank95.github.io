---
title: "Zeeshan Khan - Grounded VidSitu"
layout: gridlay
excerpt: "Zeeshan Khan: Grounded VidSitu"
sitemap: false
permalink: /grvidsitu/
---

[comment]: Title
<h2 align="center">Grounded Video Situation Recognition</h2>

[comment]: Authors
<p style="text-align: center;">
<a href="https://zeecoder606.github.io" style="color: #E71A06; font-size:17px;"> Zeeshan Khan</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://faculty.iiit.ac.in/~jawahar/index.html" style="color: #E71A06; font-size:17px;"> C.V. Jawahar</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://makarandtapaswi.github.io" style="color: #E71A06; font-size:17px;"> Makarand Tapaswi</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<p style="text-align: center;"><a href="http://cvit.iiit.ac.in" style="color:#E71A06; font-size:17px;">CVIT, IIIT Hyderabad</a></p>

<p style="text-align: center;"><a href="https://neurips.cc" style="color:#E71A06; font-size:17px;">NeurIPS 2022</a></p>

<p style="text-align: center;">

[Paper](https://zeecoder606.github.io/grvidsitu){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

[Dataset](https://zeecoder606.github.io/grvidsitu){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

[Code](https://zeecoder606.github.io/grvidsitu){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</p>

<!-- [comment]: ProcedureLearning -->
<!-- <h3>GVSR Task</h3> -->
<h3>GVSR Task</h3>
<div style="text-align: justify">
GVSR is built on top of <a href="https://vidsitu.org">VidSitu</a>. A large scale dataset containing videos of 10 seconds from complex movie scenes. A video is divded in multiple events of ~2 seconds each. Each event is associated with a salient action verb, each action verb is associated with a semantic role frame eg: agent, patient, tool, location, manner etc. Each role is is annotated using a free form text caption.


<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/Neurips.jpg" width="700px" />
		</div>
    <p>&nbsp;</p>
    <figcaption>
      Holistic understanding of video requires to localise and recognise all the salient events, and answer questions, like who did what to whom with what how why and where. GVSR affords this by recognising the action <b>verbs</b>, their corresponding <b>roles</b>, and <b>localising</b> them in the spatio-temporal domain. Entities are coreferenced in all the events.
    </figcaption>
</figure>
</center>

<!-- The GVSR task involves the following structured peridctions in an end-to-end setting.
- <b>Verb classificatin per event</b>
- <b>Role classification and semantic role labelling through caption generation</b>
- <b>Grounding all the visual semantic roles in the spatio-temporal domain</b> -->

<br>
<h3 align="center"><span style="color:DodgerBlue">VideoWhisperer</span></h3>
<!-- <h3 align="center">VideoWhisperer</h3> -->
<br>
<!-- <h3 align="center"><span style="color:DodgerBlue">VideoWhisperer</span></h3> -->
<div style="text-align: justify">

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/Model_Diagram_Final.pdf" width="700px" />
		</div>
    <p>&nbsp;</p>
    <figcaption>
      We propose a new 3-stage Transformer based model for joint structured prediction of Verbs, Role-Captions, and Groundings. Stage-1 learns the contextualised object and event embeddings through a video-object transformerm that is used to predict the verb-role pairs for each event. Stage-2 models all the predicted roles by creating role queries contextualised by event embeddings, and attends to all the object proposals through the role-object transformer decoder, to find the best entity that represents a role. The output embeddings of the roles are fed to the caption generation module. The cross-attention of the role-object decoder ranks all the object proposals enabling localization of each role.
    </figcaption>
</figure>
</center>

<br>
<!-- <h3>VideoWhisperer in action</h3> -->
<h3 align="center"><span style="color:DodgerBlue">VideoWhisperer in action</span></h3>
<br>
<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/project_page.gif" width="700px" />
		</div>
    <p>&nbsp;</p>
    <figcaption>
    </figcaption>
</figure>
</center>

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/Arrow.png" width="300px" />
		</div>
    <p>&nbsp;</p>
    <figcaption>
    </figcaption>
</figure>
</center>

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/Neurips_results.png" width="1100px" />
		</div>
    <p>&nbsp;</p>
    <figcaption>
    </figcaption>
</figure>
</center>


BibTeX

<!-- ```
@InProceedings{EgoProceLECCV2022,
author="Khan, Zeeshan 
and Jawahar, C.V.,
and Tapaswi, Makarand"
title="Grounded Video Situation Recognition",
booktitle = "Neural Information Processing Systems(NeurIPS)",
year="2022"
}

``` -->

<p>&nbsp;</p>
<p>&nbsp;</p>
