---
title: Inline & Block-Level
date: 2014-02-20
tags: inline, block level, elements
---

<article>
<h1>Inline Elements & Block-Level Elements</h1>

<p>Its definitely been a struggle knowing the best approach to writing code when you don't have the basics down. Something as simple as knowing the appropriate use of inline elements and block elements is essential. So let's go over the differences in these elements and get some basic rules down.</p>

<h3>Inline Elements</h3>
<p>They can live <em>inside</em> of block-level elements or other inline elements.</p>

<p>In terms of width, they'll take up the width of their content. They'll also ignore any width and height properties. For better understanding, I find it easiest to think of inline elements as text. If you put an inline element next to text, it simply flows with the text. Just think: text based!</p>

<p>Knowing this brings to light the next characteristic of inline elements: they will display without starting on a new line (there is no line break).</p>

<p>Here are some HTML tags you may already be familiar with:</p>
<script src="https://gist.github.com/CassieShumway/9210346.js"></script>

<h3>Block-Level Elements</h3>
<p>Block-level elements cannot live inside inline elements because they're literally a block of content. However, they can <em>contain</em> inline elements and other block-level elements.</p>

<p>Just think: blocks...literally, just blocks! Block-level elements will always create a line break before and after itself. Similar to legos, they will simply build on top of each other.</p>  

<p>In terms of width, they will take up the width of their container. So if you don't set a width, it'll naturally expand to fill its parent container.</p>

<p>Here are some examples of block-level elements:</p>
<script src="https://gist.github.com/CassieShumway/9210876.js"></script>

<h3>The Visuals</h3>
<p>For a more comprehensive explanation of inline and block-level elements, <a class="underline" href="/project-inlineblock/index.html">visit the projects page.</a></p>

<h3>Sources</h3>
<ul>
	<li><a href="http://www.impressivewebs.com/difference-block-inline-css/">The Difference Between "Block" and "Inline"</a></li>
	<li><a href="https://developer.mozilla.org">Mozilla Developer Network</a></li>
</ul>
</article>

