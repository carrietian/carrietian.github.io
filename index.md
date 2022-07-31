Hi there. I live in Brooklyn and work in product at Wave. 

Reach out anytime: hi@carrietian.com

This site is perpetually a work in progress. As am I, as am I.

To make staying in touch easier, I send friends old and new a letter once a season.
They’re nice! You can [get it here.](http://eepurl.com/giFVMv)

## Posts
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

