# Blog

Welcome to my blog! \:\) Here you can find my blog posts organized by their tags:

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>
{% endfor %}

***

Subscribe to my [atom feed](https://chester-tan.com/feed.xml) \:\)
