---
title: Good Practice (CSS)
date: 2014-02-25
tags: css, good practice
---

<article>
<h1>Good Practice in CSS</h1>
<h2>Reading Handcrafted CSS by Dan Cederholm</h2>

<p>Dan Cederholm talks about how good craftsmanship for the web is all about accounting for and anticipating any adjustments needed so that your design doesn't break. For me, its definitely been a struggle knowing the best approach to writing code in order to avoid this. 
</p>

<p>One of the first things that Cederholm dives into is the float property. If a floated element doesn't have a specified width, it'll expand as wide as it can. Adding a clearfix to the element that contains the floated items is one method of self clearing. These small bits of advice are just the tip of the iceberg. 
</p>

<h3>An Introduction</h3>
<p>Learning everything there is to know about floats is extremely intensive. So we'll start from the basics again! 

<h3>What Is It?</h3>
<p>Floated elements are elements that can be floated to the left or to the right. They are widely used for navigation, image galleries, and general page layouts. 
</p>
<script src="https://gist.github.com/CassieShumway/9398169.js"></script>

<p>However, you run into a lot of problems using floats. The main reason being, is that any floated element will be taken out of the natural flow of the document. Thus, "clearing" is required for all floats. 
</p>

<p>The method we will be focusing on is the clearfix approach. 

<img class="image" src="/images/floatimage.jpg">

<p>Adding this clearfix to the parent container of the floated items will help keep them contained. Taking a look at this sketch, you can see that the :before and :after are applied to top and bottom of the parent container. With this in place, it can now recognize the floated elements inside and expand accordingly.
</p>

<h3>The Visuals</h3>
<p>For the complete explanation on floats, <a class="underline" href="/project-floats/index.html">visit the projects page.</a>
</p>
</article>

