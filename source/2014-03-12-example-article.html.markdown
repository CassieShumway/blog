---
title: Code Guide by @mdo
date: 2014-03-12
tags: code guide
---

<article>
<h1>Code Guide by @mdo</h1>

<p>I was given a great reference guide by Adam on code standards that make way for more sustainable HTML and CSS. I wanted to talk about some methods that I recently learned and plan to start implenting in my daily practice.</p>

<h3>Using Shorthand</h3>
<p>I've learned that its good to use shorthand in CSS. Instead of declaring multiple properties (and using multiple lines of code) on a single element, you can streamline the process.</p> 

<p>Here's a bad example:</p>

<script src="https://gist.github.com/CassieShumway/9521616.js"></script>

<p>Now take a look at how we can condense this using shorthand:</p>

<script src="https://gist.github.com/CassieShumway/9521850.js"></script>

<h3>Shorthand Notation</h3>
<p>Using shorthand is good practice, but its also good to limit the times when you lay out all the values when you don't need to.</p> 

<p>For example:</p>

<script src="https://gist.github.com/CassieShumway/9522074.js"></script>

<p>While this is considered very clean, do you notice how the only thing we're targeting is the bottom margin? If that's the case, why not just target the bottom margin <em>only?</em></p>

<script src="https://gist.github.com/CassieShumway/9522080.js"></script>

<p>In this article, mdo mentions that "excessive use of shorthand properties often leads to sloppier code with unnecessary overrides and unintended side effects."</p>

<p>Knowing this, it seems best to target specific properties. I didn't realize that HTML headings only set top and bottom margin. So only when it's necessary should you override those two values.</p>

<h3>Class Names</h3>
<p>I've found that naming classes have been a bit tricky. I still haven't gotten used to the fact that other people must be able to read my code and work off it. Therefore I must make sure that others can find their way around with proper class names.</p>

<p>Here's a bad example:</p>

<script src="https://gist.github.com/CassieShumway/9530002.js"></script>

<p>If someone were to look at this class...do you think they would know what it was for? It's good to keep classes short and to the point but make sure you're still able to convey what element your'e targeting!</p>

<p>Here's a better example:</p>
<script src="https://gist.github.com/CassieShumway/9530056.js"></script>

<p>If your class name happens to run longer than you'd like or require two words, make sure to add a hyphen in between. This allows for more readability:</p>

<script src="https://gist.github.com/CassieShumway/9530249.js"></script>

<h3>CSS Syntax</h3>
<p>CSS has two main parts which consists of a selector and its declarations:

<script src="https://gist.github.com/CassieShumway/9530735.js"></script>

<p>Here are some good practices:</p>

<ul>
  <li>Always use soft tabs with two spaces.</li>
  <li>Lowercase all hex values.</li>
  <li>Use hex values instead of preset colors (white, red, green, etc).</li>
</ul>

<h3>HTML Syntax</h3>
<p>HTML stands for Hyper Text Markup Language. HTML documents contain tags/elements and plain text.</p>

<p>Here are some good practices:</p>
<ul>
  <li>Always use soft tabs with two spaces.</li>
  <li>Nest your elements with an indent of two spaces.</li>
  <li>Aim for the least amount of markup.</li>
  <li>Avoid unnecessary parent elements.</li>
  <li>Close your tags.</li>
</ul>

<h3>Source</h3>
<p><a href="http://mdo.github.io/code-guide/">Code Guide by @mdo</a></p>
</article>

