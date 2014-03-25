---
title: A Little More Positioning
date: 2014-03-25
tags: positioning, absolute
---

<article>
<h1>Absolute Positioning</h1>

<p>I wanted to make a quick post to expand on positioning with a small example.</p>

<p>Taking a look below, I decided to create a small list demonstrating absolute positioning. By referencing Cederholm's book on CSS we have a layout where "absolute positioning makes good sense."</p>

<p>By applying <code>position: relative</code> to the parent element, it now acts as a container. Now we're able to control and position all the absolute elements within. Remember that we need to use the top, right, bottom, and left properites to reposition any elements.</p>

<div class="animal-box">
  <ul class="animal-list">
    <li>Monkey<span class="animal-image"><img src="/images/monkey.jpg"><img src="/images/monkey.jpg"><img src="/images/monkey.jpg"></span></li>
    <li>Otter<span class="animal-image"><img src="/images/otter.jpg"></span></li>
    <li>Cat<span class="animal-image"><img src="/images/cat.jpg"></span></li>
    <li>Bear<span class="animal-image"><img src="/images/bear.jpg"><img src="/images/bear.jpg"><img src="/images/bear.jpg"><img src="/images/bear.jpg"></span></li>
  </ul>
</div>

<p>It should be noted that using left/right or top/bottom for the same element is pointless. This is because the content direction for the element determines which value is used. For example, if your content direction is left to right, the <code>left</code> value will be used and the <code>right</code> value will be ignored.</p>

<p>Similarily, you cannot use both top/bottom values on the same element. Ultimately the <code>top</code> value will be used and <code>bottom</code> will be ignored.</p>

<h3>The Visuals</h3>
<p>If you'd like a more explanation on positioning, please <a class="underline" href="/project-position/index.html">visit the projects page.</a></p>

<h3>Source</h3>
<p>Handcrafted CSS by Dan Cederholm</p>
</article>

