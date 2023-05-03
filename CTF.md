---
---

## Capture The Flag

The conference is around the corner, it is time to sharpen your minds and prepare for the CTF!

This year, The CTF team (professionals from various places), led by Maor Tal (Sikreta) and Tomer Zait (F5) have worked hard to create a new, interesting, unique challenges, in the fields of application security, cloud security, mobile security, code review, devSecOps and more.

<!---The CTF Team Members: Maor Tal (th3location), Avi Wolicki, Noy Pearl, Meitar Reihan, Shay Nehmad, Amit Avrahamov, Ben Salem, Nimrod Levy, Artur Isakhanyan, Michael Maltsev, Itai Ben-Natan, Gal Goldshtein.

Make sure to sign up (with a valid email address) at the following link:  

[https://appsecil2020.ctf.today/](https://appsecil2020.ctf.today/)
--->


The challenge is free to attend and will be opened on Wednesday, May 17th at 10 am.

Please note that registration is required and will open soon! 

Good Luck  :)

{% if site.data.sponsors.alacarte %}
<div class="sponsor-tier">
	Sponsored by:<br/>
  {% for sponsor in site.data.sponsors.alacarte %}
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


