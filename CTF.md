---
---

## Capture The Flag

The conference is around the corner, it is time to sharpen your minds and prepare for the CTF!

This year, The CTF team (professionals from various places), led by Tomer Zait (realgam3) have worked hard to create a new, interesting, unique challenges, in the fields of application security, cloud security, mobile security, code review, devsecops and more.

The CTF Team Members: Maor Tal, Avi Wolicki, Noy Pearl, Meitar Reihan, Shay Nehmad, Amit Avrahamov, Ben Salem, Nimrod Levy, Artur Isakhanyan, Michael Maltsev, Nadav Tasher.

Make sure to sign up (with a valid email address) at the following link:  

[https://appsecil2020.ctf.today/](https://appsecil2020.ctf.today/)


The challenge will be opened on Saturday, October 24th at 7pm.

Good Luck  :)

{% if site.data.sponsors.ctf %}
<div class="sponsor-tier">
	Sponsored by:<br/>
  {% for sponsor in site.data.sponsors.ctf %}
	<span class="sponsor community-sponsor">
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
