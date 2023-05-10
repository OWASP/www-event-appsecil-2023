---
---

## Capture The Flag

The conference is around the corner, it is time to sharpen your minds and prepare for the CTF!

This year, The CTF team (professionals from various places), led by Maor Tal (Sikreta) and Tomer Zait (F5) have worked hard to create a new, interesting, unique challenges, in the fields of application security, cloud security, mobile security, code review, DevSecOps and more.

The CTF Team Members: Maor Tal,Tomer Zait, Idan Bachar, Aviv Avraham Levy, Or Sahar, Osher Bello, and Artur Avetisian. 

Make sure to sign up (with a valid email address) at the following link:  

[https://appsecil2023.ctf.today/](https://appsecil2023.ctf.today/)



The challenge is free to attend and will be opened on Wednesday, May 17th at 10 am.

**Please note that registration is required**, please register  [here](https://www.eventbrite.com/e/appsec-israel-2023-tickets-594694937567) by choosing CTF area ticket type (Yo dawg, I heard you like CTFs, so I....). 

Good Luck  :)

{% if site.data.sponsors.alacarte %}
<div class="sponsor-tier">
	Sponsored and built by:<br/>
  {% for sponsor in site.data.sponsors.alacarte %}
	{% if sponsor.type == "CTF" %}
		<span class="sponsor silver-sponsor">
	 	 <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
			{% if sponsor.image == %}
			  <span>{{ sponsor.name }}</span>
			{% else %}
			  <img src="assets/img/Sponsors/{{ sponsor.image }}" style="padding: 4px;">
			{% endif %}
		  </a>
		</span>
	{% endif %}
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.ctfBuilders %}
<div class="sponsor-tier">
	Also built and managed by:<br/>
  {% for sponsor in site.data.sponsors.ctfBuilders %}
	<span class="sponsor silver-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %}
		  <img src="assets/img/Sponsors/{{ sponsor.image }}" style="padding: 4px;">
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}
