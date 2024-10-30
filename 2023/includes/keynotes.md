{% if site.data.year-2023.keynotes %} 
<br /> 

## Keynote Speakers

  {% for keynote in site.data.year-2023.keynotes %}
<img src="/assets/img/{{ keynote.image }}" style="width:320px"> 
### {{ keynote.name }}
#### <em style="font-style: italic;">{{ keynote.company }}</em>
{% if keynote.url %}
#### <a href="{{ keynote.url }}" target="_blank">{{ keynote.title }}</a>
{% else %}
#### <strong style="font-size:large; font-weight:300; text-decoration:underline;">{{ keynote.title }}</strong>
{% endif %}

<br />

  {% endfor %} 

{% endif %}
