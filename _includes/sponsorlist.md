{% if site.data.sponsors.diamond %}
### Diamond Sponsor 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.diamond %}
	<span class="sponsor diamond-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == blank %}
		  <p>{{ sponsor.name }}</p>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.platinum %}
### Platinum Sponsors
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.platinum %}
	<span class="sponsor platinum-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == blank %}
		  <p>{{ sponsor.name }}</p>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.gold %}
#### Gold Sponsors 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.gold %}
	  <span class="sponsor gold-sponsor">
		<a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		  {% if sponsor.image == %}
			<span>{{ sponsor.name }}</span>
		  {% else %} 
			<img src="assets/img/Sponsors/{{ sponsor.image }}">
		  {% endif %}
		</a>
	  </span>
  {% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.silver %}
##### Silver Sponsors
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.silver %}
	<span class="sponsor silver-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.bronze %}
###### Bronze Sponsors
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.bronze %}
	<span class="sponsor bronze-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.community %}
####### Community Supporters
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.community %}
	<span class="sponsor community-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.alacarte %}
####### A La Carte Sponsorships
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.alacarte %}
	<span class="sponsor alacarte-sponsor">
	  <span>{{ sponsor.type }}</span>  <hr />
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}
