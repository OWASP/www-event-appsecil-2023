<header>
    <div class="top">
        <a href="{{ '/' | relative_url }}" class="logo"></a>
    </div>
	
    <nav>
        <ul class="nav navbar-nav">
            {% for menu in site.data.menus %}
            <li>
                <a href="{{ menu.url | relative_url }}">{{menu.title}}</a>
            </li>
            {% endfor %}
        </ul>
    </nav>
</header>
