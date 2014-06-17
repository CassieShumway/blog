---
title: Git Reminders
date: 2014-06-14	
tags: github
---

<article>

<h1>Git Reminders</h1>

<p>In the beginning of the apprenticeship, we wanted to instill good practices. For example, the importance of indenting a line and properly nesting. In this instance, there are a few more practices we should always keep in mind in terms of our Github processes!</p> 

<hr class="divider-short">

<h3>.gitignore</h3>

<p>There are many files that might show up in your repository. But there are some files that you don't want to show....so we want to make sure that we properly hide them! Adding and using the gitignore will help us keep junk files out of our pretty repository.</p>

<p>Simply add the following to your .gitignore:</p>

<script src="https://gist.github.com/CassieShumway/d610ee3d70029286086a.js"></script>

<hr class="divider-short">

<h3>Making/Editing your .gitignore</h3>

<p>If you already have some files in your repository that you need getting rid of, follow these steps:</p>

<ol>
	<li>touch .gitignore</li>
	<li>add the code above into your .gitignore file</li>
	<li>rm .DS_Store (and/or any other junk files)</li>
	<li>push your files back up to github for completed edits</li>
</ol>

<hr class="divider-short">

<h3>Make A Repository for each project</h3>

<p>It's been a while since I've worked in Github since Middleman makes it all too easy. So making a new repository was good review. In order to create a new repository for each project page, this is what I did:</p>

<ol>
	<li>Navigate through your terminal</li>
	<li>Go to the folder you wish to create a new repository for</li>
	<li>Type git init</li>
	<li>Add all your files</li>
	<li>git commit -m "type message here"</li>
	<li>git remote add origin git@github.com:CassieShumway/test.git</li>
	<li>git push -u origin master</li>
</ol>

<p>Now you've just made a new repository from your existing folder. Easy!</p>

<p>I'm sure I'll come across many more Git practices that are essential to good practices, but for now, this is a good start when creating new projects!</p>

</article>

