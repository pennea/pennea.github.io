---
layout: default
title: Events
nav: main
permalink: /events/
---

<div class="main-list">

  <h1 class="page-heading">Events</h1>

<iframe src="https://www.google.com/calendar/embed?src=mpe3r96ghp3b8u7mk0jppijjqs%40group.calendar.google.com&ctz=America/New_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

  <ul class="post-list">
    {% for event in site.categories.event %}
      <li>
        <span class="post-meta">{{ event.date | date: "%B %-d, %Y" }} &mdash; {{ event.guest }} </span>

        <h2>
          <a class="post-link" href="{{ event.url | prepend: site.baseurl }}">{{ event.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

</div>
