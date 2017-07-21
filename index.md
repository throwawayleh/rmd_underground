## Welcome to RMD underground

RMD Underground is a blog for RMD staff to share views that support – or challenge – prevailing orthodoxies. The views expressed here are strictly those of the authors.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
