---
title: Looking Back
date: 2014-03-27
tags: positioning, absolute
---

<article>
<h1>Looking Back</h1>
<p>During my novice apprenticeship at 8th Light, I've learned a lot. It's exciting to look back and see how much I've learned in HTML and CSS but its even more exciting to know that there is <em>always</em> more to learn.</p>

<p>These projects and blog posts focus on setting good practices and understanding the basic fundamentals of HTML and CSS. Having Adam as my mentor has meant a lot to me because it's been so encouraging to problem solve together and develop best practices. I'm hoping to learn more from Adam's design approach by writing cleaner and more modular code while maintaining design integrity.</p>

<p>I'd like to make this blog post dedicated to all the things I've learned thus far.</p>

<hr class="divider">

<h3>CSS Syntax</h3>
<p>CSS stands for Cascading Style Sheets. It allows you to separate your HTML content from the styling. When using CSS, make sure to always apply good practice with class names, shorthand, hex values, and soft tabs.</p>
<script src="https://gist.github.com/CassieShumway/9530735.js"></script>
<ul>
  <li class="feather-image">The selector is our HTML element that you want to style.</li> 
  <li class="feather-image">The property is the property name you want to style with.</li>
  <li class="feather-image">The value is the style you're applying to the property.</li>
</ul>

<hr class="divider">

<h3>HTML Syntax</h3>
<p>HTML stands for Hyper Text Markup Language. HTML documents contain tags/elements and plain text. When using HTML, make sure to always apply good practice by closing your tags and applying soft tabs.</p>
<script src="https://gist.github.com/CassieShumway/9815420.js"></script>
<ul>
  <li class="feather-image">Nest your elements with an indent of two spaces.</li>
  <li class="feather-image">Aim for the least amount of markup.</li>
  <li class="feather-image">Avoid unnecessary parent elements.</li>
</ul>

<hr class="divider">

<h3>Inline &amp; Block Level Elements</h3>
<p>Inline elements flow like text. Block elements create a new line break before and after the element. They create "blocks" of content.</p>
<p>Here are some important CSS display properties:</p>

<h4>1. Inline Block</h4>
<script src="https://gist.github.com/CassieShumway/9253123.js"></script>
<p>This allows a block element to act as an inline element. These inline elements will obey height and width properties!</p>

<h4>2. Block</h4>
<script src="https://gist.github.com/CassieShumway/9254434.js"></script>
<p>This allows an inline element to display as a block element.</p>

<h4>3. Inline</h4>
<script src="https://gist.github.com/CassieShumway/9255164.js"></script>
<p>This allows a block element to display as an inline element. Don't forget that inline elements will still ignore width and height properties!</p>

<hr class="divider">

<h3>Floats</h3>
<p>Floats are a CSS positioning property. </p>
<script src="https://gist.github.com/CassieShumway/9398169.js"></script>
<ul>
  <li class="feather-image">Floats can only go left or right.</li>
  <li class="feather-image">They are typically used for flexible layouts.</li>
  <li class="feather-image">Floats can be used to wrap text around images or other elements.</li>
</ul>

<hr class="divider">

<h3>Clearfix</h3>
<p>By using a <code>clearfix</code> you can easily clear your floats. Otherwise, the parent container will collapse.</p>
<script src="https://gist.github.com/CassieShumway/9357122.js"></script>
<p>By applying a <code>clearfix</code> to your parent container, it can now recognize any floated elements within itself and expand accordingly.</p>

<hr class="divider">

<h3>Positioning</h3>
<p>Positioning is used to position elements using top, right, bottom and left properties.</p>

<h4>1. Static</h4>
<script src="https://gist.github.com/CassieShumway/9819110.js"></script>
<p>It's never necessary to declare a static position. Static elements already position themselves to the normal flow which is static.</p>

<h4>2. Absolute</h4>
<script src="https://gist.github.com/CassieShumway/9819215.js"></script>
<p>By applying abolsute positioning to an element, you remove it from the normal flow of the page. </p>

<h4>3. Relative</h4>
<script src="https://gist.github.com/CassieShumway/9825552.js"></script>
<p>When you use relative positioning on an element, it places it in the normal flow of your page. It will be placed as a static element, then it can be positioned using top, right, bottom, and left.</p>

<h4>4. Fixed</h4>
<script src="https://gist.github.com/CassieShumway/9825614.js"></script>
<p>Fixed positioning is similar to absolute postioning. However, unlike absolute positioning, it will not move with your browser window. Essentially, the brower window is its' parent element whether or not its nested inside another element</p>

<hr class="divider"> 

<h3>Pseudo Classes</h3>
<p>Pseudo classes are used to modify certain selectors without adding markup in your HTML file.</p>
<script src="https://gist.github.com/CassieShumway/9479800.js"></script>
<p>Here are some important pseudo class selectors:</p>
<h4>1. :first-child and :last-child</h4>
<script src="https://gist.github.com/CassieShumway/9826457.js"></script>
<ul>
  <li class="feather-image">:first-child targets the first child of its parent element.</li>
  <li class="feather-image">:last-child targets the last child element of its parent element.</li>
</ul>
<p>Both are most commonly used to clear extra margins or borders.</p>

<h4>2. :before and :after</h4>
<script src="https://gist.github.com/CassieShumway/9826461.js"></script>
<ul>
  <li class="feather-image">:before inserts content before an element.</li>
  <li class="feather-image">:after inserts content after an element.</li>
</ul>
<p>Both only show themselves under specific elements selected in your CSS file.</p>

<h4>3. :nth-child(N)</h4>
<script src="https://gist.github.com/CassieShumway/9826534.js"></script>
<ul>
  <li class="feather-image">Matches elements of the nth child.</li>
  <li class="feather-image">(N) could be a keyword, number or formula.</li>
</ul>


<hr class="divider"> 

<h3>From Here...</h3>
<p>I want to continue moving forward with 8th Light to better my practice and continue learning from other craftsmen with their experiences and different approaches. With that, continuing to problem solve and moving forward with the best solution. It's been thrilling to realize that 8th Light embraces this process which creates a constant environment of learning and opportunity to better your code. I'm looking forward to setting more advanced goals as I progress. 

<h3>What I Love</h3>
<p>Aside from my love of Chicago doughnuts, I am a huge fan of illustration. With a background in fine arts, I would love to design custom illustrations for future projects and push the boundaries of design. Having previous experience as a freelance graphic designer, I love brainstorming design ideas and helping clients discover the design direction that best fits their needs.</p>

<h3>Adding Love With Code</h3> 
<p>What I'm most interested in is responsive design. How can I keep design integrity while keeping practical and efficient code? How can I create the best experience for a user with exciting visuals and interactive responses? How can I create harmony with my love for graphics and code?</p>

<p>I'm hoping to always keep these questions in mind...But I'm also hoping to answer them!</p>

</article>