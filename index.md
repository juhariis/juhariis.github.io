A companion to  [What's Hiding in Data](https://hidingindata.wordpress.com/) with all the tl;dr details.

And at the moment very much under construction and experimentation..

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>