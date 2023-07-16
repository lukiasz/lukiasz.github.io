<figure class="image">
{% if description %}
<img src="{{ url }}" alt="{{ description }}">
<figcaption>{{ description }}</figcaption>
{% else %}
<img src="{{ url }}">
{% endif %}
</figure>