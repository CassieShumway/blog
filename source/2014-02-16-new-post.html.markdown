---
title: Middleman
date: 2014-02-16
tags: middleman, deploy
---
<article>
<h1>Middleman</h1>
<p>I've been working with Middleman for the first time and its been an enjoyable struggle. It's forced me to learn a wide range of things and become more competent with Terminal and Github while getting a little taste of some ruby along the way.</p>

<h3>1. Add the gem</h3>
<p>To start, add this to the Gemfile in the repository of our Middleman site:</p>

<script src="https://gist.github.com/CassieShumway/9073486.js"></script>

<p>Now you'll want to run this command in your terminal:</p> 

<script src="https://gist.github.com/CassieShumway/9076170.js"></script>

<h3>2. Build and Deploy</h3>
<p>To build your site, Middleman converts your dynamic code into static code. When you're ready to make your blog live, all your files are compiled, converted, and launched. The "build" command compiles and converts while the "deploy" command sends the files online to be live.</p>

<script src="https://gist.github.com/CassieShumway/9076067.js"></script>

<p>If you want to skip a step (and configure it to github), you can build while you deploy. Add the following code to your config.rb file:</p>

<script src="https://gist.github.com/CassieShumway/9075949.js"></script>

<h3>3. Save your dynamic and static code on Github</h3>
<p>In order to save both your static and dynamic files onto Github, you'll have to create two remote repositories within your local host folder. If you look below, you'll see that I named one of the repositories "blog" (for your dynamic code) while the other repository will default to the "master" branch of your blog (username.github.io) for your static code. By doing this, you're able to have a back-up of your blog instead of only keeping it in your local folder.</p>

<script src="https://gist.github.com/CassieShumway/9078484.js"></script>

<h3>4. Git Push vs. Middleman Deploy</h3>
<p>The difference between the two is using "git push" or "middleman deploy." When using git push, you'll be saving your dynamic code (the pre-built files) onto github. When using middleman deploy, you'll be sending the static code (remember that we combined the steps of building with deploying) that will be live online.</p>

<p>To check that you have the two remote repositories, run this command in your terminal:</p>

<script src="https://gist.github.com/CassieShumway/9078503.js"></script>

<p>You should see your username.github.io (for your live blog on the "master" branch) and the other repsoitory (for your dynamic code).</p>
</article>