# Sydney

A Bootstrap theme for Ghost.

See it in action: http://seanosaur.com.

![](http://i.imgur.com/66qF6K3.png)

## Theme Options

### Nav menu

**partials/header.hbs**: edit this file with your own information and social network usernames.

---

### Google Analytics

**default.hbs**: remove this line:

```
<!--  Add Google Analytics here. -->
```

then paste your code from Google Analytics in its place.

---

### Disqus comments

**page.hbs** and **post.hbs**: remove this line:

```
<!-- Add disqus comments here -->
```

then paste your code from Disqus in its place.

---

### Syntax Highlighting

Syntax highlighting is in place within each post, but if you want it on your index page, you'll have to go into **index.hbs** and change this:

```
    <section>
      <p>{{excerpt}}&hellip;</p>
      <h5><a href="{{url}}">Read more <i class="fa fa-caret-right"></i></a></h5>
    </section>
<!-- Uncomment this section (and comment out the section with {{excerpt}} ) if you want syntax highlighting on your index page.
    <section>
      {{content}}
    </section>
-->
```

to this:

```
<!--
    <section>
      <p>{{excerpt}}&hellip;</p>
      <h5><a href="{{url}}">Read more <i class="fa fa-caret-right"></i></a></h5>
    </section>
-->
    <section>
      {{content}}
    </section>
```

---

### Twitter Card

**default.hbs**: edit this line:

```
<meta name="twitter:creator" content="@YOUR_TWITTER_HANDLE">
```

by adding your username in place of "YOUR_TWITTER_HANDLE"

Base theme from [Black Tie](http://www.blacktie.co).
