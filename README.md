## Thanks for stopping by!
<img src="assets/headshot.jpg" alt="Chuck Quinn IV" style="width: 200px;"/>

I'm a current Computer Science student at DePaul University interested in backend development.

Feel free to reach out! You can email me at cquinniv@gmail.com and connect with me on
[LinkedIn](https://www.linkedin.com/in/cquinniv).

---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
---
