# Ho ho ho

{% include main.html %}

{% for post in site.posts %}
{% if post.sold != true %}
![{{ post.title }}]({{ site.baseurl }}/assets/{{ post.permalink }}.png)
{% endif %}
{% endfor %}

