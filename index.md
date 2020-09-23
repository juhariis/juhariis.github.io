Just another site with some random and infrequently published 
blog entries.
Mostly related to data science and programming 
in R and Python - and whatever that brings up.

The WordPress site 
[What's hiding in data](https://hidingindata.wordpress.com/)
won't get any updates anymore and migt eventually be transferred
over here.

Posts so far

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

* * *

[About]({% link about.md %})
