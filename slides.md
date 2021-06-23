<!--
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-->

<!-- .slide: class="slide-title" data-background-image="assets/title-slide.svg" data-background-color="#000000" data-background-repeat="no-repeat" data-background-position="center" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<!-- Main title page -->
<div class="lefted">

<h1 id="talk-title">
    A long talk title that may be several lines in the slide
</h1>

<p id="talk-authors">
    <span id="talk-speaker">Leonardo Uieda</span>
<span style="margin: 0 10px">•</span>
    Santiago Soler
<span style="margin: 0 10px">•</span>
    Agustina Pesce
</p>

<!-- Social media handles and links -->
<p id="talk-social">
<i class="fab fa-twitter fa-fw"></i>
<a href="https://twitter.com/leouieda">@leouieda</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="container talk-info">
<div class="col">

Event/host of the talk
<span style="margin: 0 20px">•</span>
XX Month 202X

<!-- Permission to reuse and CC-BY license logo -->
<p><a href="https://creativecommons.org/licenses/by/4.0/">
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>
CC-BY 4.0 License
</a></p>

<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse/remix this presentation

</div>
<div class="col">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
    <img src="assets/university-of-liverpool-white.png">
    <img src="assets/compgeolab-banner-light.svg">
</div>
</div>

</div>
</div>

</div>

---

<!-- .slide: data-background-image="assets/title-slide.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-right">

This is a little footnote.
<br>
The background is contained so that it won't crop the top/bottom if the browser
window isn't maximized.

</div>

---

<!-- .slide: class="slide-transition" data-background-color="#060629" -->

<div class="centered">
<div>

# A transition slide <br> with a centered title

</div>
</div>

---

<!-- .slide: data-background-video="assets/brasil-sao-paulo-rio.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch bottom-right">

This is how you use a video background.

</div>

---

<!-- .slide: data-background-image="assets/title-slide.svg" data-background-size="contain" data-background-opacity="0.5" data-background-repeat="no-repeat" data-background-color="#ffffff" -->

<div class="centered">
<div class="quote">

Big quote message with a faded background image.
Bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla.

</div>
</div>

---

<div class="container">
<div class="col-left">

## Two column layout

<ul class="fa-ul">

<li>
<span class="fa-li"> <i class="fa fa-lightbulb fa-fw"></i> </span>
State-of-the-art algorithms
</li>

<li>
<span class="fa-li"> <i class="fa fa-file-alt fa-fw"></i> </span>
Used in several thesis & papers (>70 citations)
</li>

<li>
<span class="fa-li"> <i class="fa fa-users fa-fw"></i> </span>
2-3 active contributors
</li>

<li>
<span class="fa-li"> <i class="fa fa-chalkboard-teacher fa-fw"></i> </span>
Enabled teaching through simulation
</li>

</ul>

</div>
<div class="col-right fragment" style="padding-left: 5%">

<h1 style="color: #dd0000;">
<i class="far fa-thumbs-down" style="margin-right: 20px;"></i>
The bad parts
</h1>

<hr>

<ul class="fa-ul">

<li>
<span class="fa-li"> <i class="fa fa-gamepad fa-fw"></i> </span>
Too many toy problems and experimental code
</li>

<li>
<span class="fa-li"> <i class="fas fa-vial fa-fw"></i> </span>
Not designed for testability
</li>

<li>
<span class="fa-li"> <i class="fa fa-tools fa-fw"></i> </span>
Difficult to maintain
</li>

<li>
<span class="fa-li"> <i class="fa fa-landmark fa-fw"></i> </span>
Unstable foundations for growth
</li>

</ul>
</div>

---

<!-- .slide: class="slide-transition" data-background-color="#000000" data-background-image="assets/demo-time.gif" data-background-repeat="no-repeat" data-background-position="center" data-background-opacity="70%" -->

<div class="centered">
<div>

# Demo time!

</div>
</div>

---

<!-- .slide: class="slide-transition" data-background-color="#060629" -->

<div class="centered">
<div>

<h1>
Ongoing
<br>
developments
<br>
<i class="fa fa-wrench"></i>
</h1>

</div>
</div>

---

<div class="container">
<div class="col-large">

# Equivalent sources

Using **gradient boosting** to scale to millions of data

Preprint on EarthArXiv (minor revision at GJI): [Soler & Uieda (2021)](https://doi.org/10.31223/X58G7C)

Code coming to Harmonica in the next few months

</div>
<div class="col-small">

<img src="assets/gradient-boosting.svg" style="width: 90%">

</div>
</div>

---

# In development

* Frequency domain transformation ([fatiando/harmonica#238](https://github.com/fatiando/harmonica/pull/238))
* Tri-axial ellipsoids ([fatiando/boule#76](https://github.com/fatiando/boule/issues/76))
* Re-organization of the documentation ([Pooch v1.4.0 was the first](https://www.fatiando.org/pooch/v1.4.0/))
* Gather open-access data for tutorials ([included in RockHound](https://github.com/fatiando/meeting-notes/blob/main/community-calls/2021.md#2021-05-13))
* Increase recruitment and diversity of our community

---

<!-- .slide: class="slide-transition" data-background-color="#060629" -->

<div class="centered">
<div>

<h1>
Come for the <strong>code</strong> <i class="fas fa-code"></i>
<br>
Stay for the <strong>community</strong> <i class="fas fa-users"></i>
</h1>

</div>
</div>

---

# Get started

<ul class="fa-ul">

<li class="fragment">
<span class="fa-li"><i class="fab fa-python"></i></span>
Not experienced with Python?
<ul style="margin: 1em 0 0 1em;">
<li>
  Software Carpentry has <a href="https://swcarpentry.github.io/python-novice-inflammation/">great open-access lessons</a>
</li>
</ul>
</li>

<li class="fragment">
<span class="fa-li"><i class="fab fa-youtube"></i></span>
Watch some tutorials on YouTube:
<ul style="margin: 1em 0 0 1em;">
<li>
  Verde (<a href="https://www.youtube.com/watch?v=-xZdNdvzm3E">Transform 2020 </a>) and
  Harmonica (<a href="https://www.youtube.com/watch?v=0bxZcCAr6bwab_channel=SoftwareUnderground">Transform 2021</a>)
</li>
</ul>
</li>

<li class="fragment">
<span class="fa-li"> <i class="fas fa-book"></i> </span>
Documentation for each library
(links at <a href="https://www.fatiando.org">fatiando.org</a>)
</li>

</ul>

---

# Get involved

There are many ways to participate:

<div class="container">
<div class="col-left">
<ul>
<li class="fragment">Write code</li>
<li class="fragment">Documentation and examples</li>
<li class="fragment">Give feedback</li>
</lu>
</div>
<div class="col-right">
<ul>
<li class="fragment">Join the conversation</li>
<li class="fragment">Share your expertise</li>
<li class="fragment">Guide future development</li>
</ul>
</div>
</div>

<div class="fragment">

**Your help is always welcome!**

</div>

---

# Where to find us

<ul class="fa-ul">

<li class="fragment">
<span class="fa-li"><i class="fab fa-slack"></i></span>
<a href="http://contact.fatiando.org/">Slack</a>:
where we chat about meetings, events, questions, experiences
</li>

<li class="fragment">
<span class="fa-li"><i class="fab fa-github"></i></span>
<a href="https://github.com/fatiando/">GitHub</a>:
where we discuss development details and review code
</li>

<li class="fragment">
<span class="fa-li"><i class="fa fa-microphone-alt"></i></span>
<div class="container">
<div class="col-left">
<a href="https://github.com/fatiando/meeting-notes">Video Calls</a>:
<b>Community Calls</b> (monthly) to socialize and plan,
<b>Development Calls</b> (weekly) to discuss the details
</div>
<div class="col-right">
<img src="assets/fatiando-community-call.jpg">
</div>
</div>
</li>

</ul>

---

<div class="centered huge">
<div>

About Fatiando:
[fatiando.org](https://www.fatiando.org)

Our research:
[compgeolab.org](https://www.compgeolab.org)

Slides + demo:
[github.com/leouieda/2021-06-22-gfz](https://github.com/leouieda/2021-06-22-gfz)

</div>
</div>

---

<!-- .slide: class="slide-license" -->

<div class="centered">
<div>

<p class="license-icons">
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
</p>

Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>
