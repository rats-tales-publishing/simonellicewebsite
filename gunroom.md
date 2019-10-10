---
layout: page
name: gunroom
title: "Gun Room"
subtitle: "Explore the world of Simon Ellice"
---


{% for item in site.character %}

<div class="character">
<h1>{{ item.title }}</h1>
<div class="photo"><img src="{{ item.photo }}"></div>
<div class="info">
	name: <i>{{ item.name }}</i><br/>
	age: <i>{{ item.age }}</i><br/>
	eyes: <i>{{ item.eyes }}</i><br/>
	hair: <i>{{ item.hair }}</i><br/>
	height: <i>{{ item.height }}</i><br/>
	interests: <i>{{ item.interests }}</i><br/>
	<p>&nbsp;</p>
	<p>&nbsp;</p>
</div>
<div class="quote">"{{ item.quote }}"</div>
<div class="quote_author text-right"> {{ item.quote_author }}</div>
<div>
	<p>&nbsp;</p>
	<p>{{ item.content }}</p>
	<p>&nbsp;</p>
	<p>&nbsp;</p>
	<p>&nbsp;</p>
</div>
</div>

{% endfor %}

