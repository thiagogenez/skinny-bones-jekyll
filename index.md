---
layout: glitch
permalink: /
title: "Hello World"
excerpt: "Making stuff one mistake at a time."
ads: false
---

<div class="typed__source">
  <h1 class="glitch__title">Hello, my name is&nbsp;Michael</h1>
  <div class="glitch__excerpt">
    <p>I am just another boring, tattooed, time traveling designer from Buffalo New York.</p>
    <p>I enjoy eating chicken wings, <a href="{{ site.url }}/paperfaces/">sketching on an iPad</a>, and playing Xbox.</p>
    <p>Here you will find a collection of <a href="{{ site.url }}/articles/">my writing</a>, <a href="{{ site.url }}/mastering-paper/">Paper by FiftyThree tutorials</a>, and other <a href="{{ site.url }}/work/">creative endeavors</a>.</p>
  </div>
  <nav class="glitch__secondary">
    <ul>
      <li><a href="#0" class="overlay__menu-trigger">Main Menu</a></li>
    {% for link in site.data.navigation.home-secondary %}
      <li><a href="{{ site.url }}{{ link.url }}">{{ link.title }}</a></li>
    {% endfor %}
    </ul>
  </nav>
</div>

<span id="js-home-typed" class="typed__dest glitch__excerpt"></span>