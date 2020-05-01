## for
```
{% for link in linklists[section.settings.main_linklist].links %}
	{% if link.links == blank %}
		<li class="nav-item active">
			<a class="nav-link" href="{{ link.url }}">{{ link.title }}</a>
		</li>
	{% endif%}
{% endfor%}
```

## if
```
{% if link.links == blank %}
	<li class="nav-item active">
		<a class="nav-link" href="{{ link.url }}">{{ link.title }}</a>
	</li>
{% endif%}
```

## assign value
```
{% assign child_list_handle = link.title | handleize %}
```

## 