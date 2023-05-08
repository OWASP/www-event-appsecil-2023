---
---

## Capture The Flag

The conference is around the corner, it is time to sharpen your minds and prepare for the CTF!

This year, The CTF team (professionals from various places), led by Maor Tal (Sikreta) and Tomer Zait (F5) have worked hard to create a new, interesting, unique challenges, in the fields of application security, cloud security, mobile security, code review, DevSecOps and more.

<!---The CTF Team Members: Maor Tal (th3location), Avi Wolicki, Noy Pearl, Meitar Reihan, Shay Nehmad, Amit Avrahamov, Ben Salem, Nimrod Levy, Artur Isakhanyan, Michael Maltsev, Itai Ben-Natan, Gal Goldshtein.

Make sure to sign up (with a valid email address) at the following link:  

[https://appsecil2020.ctf.today/](https://appsecil2020.ctf.today/)
--->


The challenge is free to attend and will be opened on Wednesday, May 17th at 10 am.

**Please note that registration is required**, please register  [here](https://www.eventbrite.com/e/appsec-israel-2023-tickets-594694937567) by choosing CTF area ticket type. 

Good Luck  :)

{% if site.data.sponsors.alacarte %}
<div class="sponsor-tier">
	Sponsored and built by:<br/>
  {% for sponsor in site.data.sponsors.alacarte %}
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

{% if site.data.sponsors.ctfBuilders %}
<div class="sponsor-tier">
	Also built by:<br/>
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
