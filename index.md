Hi there. I live in Brooklyn and work in product at [Wave](https://www.wave.com/en/about/). 

Reach out anytime: hi@carrietian.com

This site is perpetually a work in progress. As am I, as am I.

To make staying in touch easier, I send friends old and new a letter once a season.
They’re nice! You can [get it here.](https://www.carrietian.com/letters/)


### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> // {{post.date | date: "%B %Y"}}
    </li>
  {% endfor %}
</ul>
