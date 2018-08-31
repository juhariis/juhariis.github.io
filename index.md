Starting to move from [What's Hiding in Data](https://hidingindata.wordpress.com/) on WordPress 
to over here, but it will take some time..

The posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

The site is very much in its infancy and will be evolving over the days and weeks to come.