---
layout: page
---


<div id="gunroom">
<h1>Dead Ground</h1>

---

{% for item in site.glossary %}
{% if item.category == 'afghanistan' %}
<div class="character">
<h2>Glossary</h2>
<a class="more_link" href="{{ item.url }}" target="_blank">Read more</a>
</div>
<div class="photo"><img src="{{ item.photo }}"></div>
{% endif %}
{% endfor %}

<h2>Characters</h2>
{% for item in site.character %}
{% if item.category == 'afghanistan' %}
<div class="character">
<div class="photo"><img src="{{ item.photo }}"></div>
<h1>{{ item.title }}</h1>
{% if item.quote %}
<div class="quote">"{{ item.quote | truncatewords: 16 }}"</div>
<div class="quote_author text-right">̶ {{ item.quote_author }}</div>
{% endif %}
<a class="more_link" href="{{ item.url }}" target="_blank">Read more</a>
</div>
{% endif %}
{% endfor %}

<h2>Places</h2>
{% for item in site.place %}
{% if item.category == 'afghanistan' %}
<div class="character">
<div class="photo"><img src="{{ item.photo }}"></div>
<h1>{{ item.title }}</h1>
{% if item.quote %}
<div class="quote">"{{ item.quote | truncatewords: 16 }}"</div>
<div class="quote_author text-right">̶ {{ item.quote_author }}</div>
{% endif %}
<a class="more_link" href="{{ item.url }}" target="_blank">Read more</a>
</div>
{% endif %}
{% endfor %}

<h2>Weapons & Tools</h2>
{% for item in site.tool %}
{% if item.category == 'afghanistan' %}
<div class="character">
<div class="photo"><img src="{{ item.photo }}"></div>
<h1>{{ item.title }}</h1>
{% if item.quote %}
<div class="quote">"{{ item.quote | truncatewords: 16 }}"</div>
<div class="quote_author text-right">̶ {{ item.quote_author }}</div>
{% endif %}
<a class="more_link" href="{{ item.url }}" target="_blank">Read more</a>
</div>
{% endif %}
{% endfor %}


<h1>Go Fast</h1>
---

<h2>Characters</h2>
{% for item in site.character %}
{% if item.category == 'morocco' %}
<div class="character">
<div class="photo"><img src="{{ item.photo }}"></div>
<h1>{{ item.title }}</h1>
{% if item.quote %}
<div class="quote">"{{ item.quote | truncatewords: 16 }}"</div>
<div class="quote_author text-right">̶ {{ item.quote_author }}</div>
{% endif %}
<a class="more_link" href="{{ item.url }}" target="_blank">Read more</a>
</div>
{% endif %}
{% endfor %}

</div>