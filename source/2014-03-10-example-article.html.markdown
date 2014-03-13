---
title: Pseudo Classes
date: 2014-03-10
tags: pseudo, classes
---

<article>
<h1>Pseudo Classes</h1>
<script src="https://gist.github.com/CassieShumway/9479800.js"></script>
<p>Pseduo classes are used to modify specific selectors. The beautiful thing about pseudo classes is that there's no markup needed in your HTML file. Just add it to a selector in your CSS file and make way for cleaner code.</p>

<p>There are many pseudo class selectors and pseudo elements. However, we will only focus on a few class selectors that are frequently used.</p>

<h3>:first-child and :last-child</h3>
<p>The pseudo class <code>:first-child</code> targets the first child element of its parent element. Similar to that is <code>:last-child</code> that targets the last child element of its parent element.</p>

<h3>How Do You Use Them?</h3>
<p>One of the biggest struggles I had when I first started this apprenticeship was columns. Ah, the dreaded margin that would always misalign my columns! Knowing what I know now, this would be the perfect opportunity to demonstrate what I've learned.</p>

<p>Looking at the columns below, I've highlighted the <code>:first-child</code> in green.</p>

<div class="box cf">
  <div class="column-example1">
    <p>column 1</p>
  </div>
  <div class="column-example1">
    <p>column 2</p>
  </div>
  <div class="column-example1">
    <p>column 3</p>
  </div>
</div>

<p>By using <code>:first-child</code> on the first column, we can remove any extra margin that would otherwise misalign the columns in the parent container.</p>

<script src="https://gist.github.com/CassieShumway/9487482.js"></script>

<p>Imagine if we hadn't used <code>:first-child</code> to clear the extra margin space. We would end up with a margin space on every column that would throw everything off center:</p>

<div class="box cf">
<div class="column-example2">
  <p>column 1</p>
</div>
<div class="column-example2">
  <p>column 2</p>
</div>
<div class="column-example2">
  <p>column 3</p>
</div>
</div>

<p>Notice how there's more space to the left of column 1? Frustrating, I know. But now that we know better, we can use <code>:first-child</code> to clear any margin space for all future projects.</p>

<h3>:before and :after</h3>
<p>The pseudo class <code>:before</code> inserts content before an element. Similar to that is the pseudo class <code>:after</code> which inserts content after an element. For both, they only show themselves under specific elements you've selected in your CSS file.</p>

<p>In this example, we'll apply these pseudo classes to the <code>p</code> element.</p>

<script src="https://gist.github.com/CassieShumway/9500641.js"></script>

<div class="box cf">
  <p class="animal-before">This cat has been inserted using <code>:before</code> in this sentence</p>
  <p class="animal-after">This bear has been inserted using <code>:after</code> in this sentence</p>
</div>

<h3>:nth-child(N)</h3>
<p>This pseudo class matches elements of the nth child. This could be a keyword, number or formula. To keep things simple we'll choose (N) to match to any odd numbered columns. Looking below, you'll now see that column 1 and column 3 are highlighted in brown.</p>

<script src="https://gist.github.com/CassieShumway/9520699.js"></script>

<div class="box cf">
  <div class="column-example3">
    <p>column 1</p>
  </div>
  <div class="column-example3">
    <p>column 2</p>
  </div>
  <div class="column-example3">
    <p>column 3</p>
  </div>
</div>

<p>Super easy!</p>

<h3>Sources</h3>
<ul>
  <li><a href="http://www.ebooktrove.com/coding/cssref1pdf.pdf">The Ultimate CSS Reference by Tommy Olsson & Paul O'Brien</a></li>
  <li><a href="http://www.w3schools.com/">CSS Pseudo-Classes</a></li>
  <li><a href="http://css-tricks.com/">Meet the Pseudo Class Selectors</a></li>
</ul>
</article>

