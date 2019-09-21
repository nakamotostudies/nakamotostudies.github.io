---
layout: default
title: Nakamoto Studies Institute
---




<section id="newestarticles">
<h2>Welcome to the Nakamoto Studies Institute</h2>
	
<p>NSI is curating and organizing the best primary and secondary source material available on the history of Bitcoin and its multiple forks.	
	</p>
<ul style="
    list-style: none;
    padding-left: 0px;
">
{% for post in site.posts %}
	    <li><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
</ul>
</section>



<section id="list">
<h2>Satoshi Nakamoto's Emails </h2>
<p>
If you want the announcements and opportunities that I never post publicly, get on my private email list, here:
</p>

<section id="contact">
<h2>
	Contact me
</h2>
<p>
	Reach me at <a href="mailto:derykmakgill@gmail.com">derykmakgill@gmail.com.</a></p>
	<p>You can follow me on Twitter at <a href="https://twitter.com/derykmakgill">@DerykMakgill,</a> but here's <a href="/nofollow">why you shouldn't follow me</a> (or anyone).</p>

</section>

<section id="search" style="
    margin-bottom: 0px;
">
<h2>Search</h2>
<form action="https://duckduckgo.com/" method="get">
	<label for="q">Search derykmakgill.com for anything:</label>
	<input type="text" name="q" value="">
	<input type="hidden" name="sites" value="“derykmakgill.com”">
	<input type="hidden" name="ia" value="web">
	<input type="submit" value="search">
</form>
</section>
