<header>
    <div class="top">
        <a href="{{ '/' | relative_url }}" class="logo" style="background-image: url({{ site.data.year-2025.config.logoUrl }})"></a>
    </div>
	
    <nav>
        <ul class="nav navbar-nav">
            {% for menu in site.data.year-2025.menus %}
            <li>
                <a href="/{{ menu.url }}">{{menu.title}}</a>
            </li>
            {% endfor %}
        </ul>
    </nav>
</header>
