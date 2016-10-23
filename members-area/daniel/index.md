---
layout: page
permalink: /members-area/daniel/
---
<h1> Daniel </h1>
Any important information will appear here:
<h3 class="page-heading">Posts</h3>



  <ul class="post-list">

    {% for post in site.daniels_posts %}

      <li>

        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>



        <h2>

          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>

        </h2>

      </li>

    {% endfor %}

  </ul>
