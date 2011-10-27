---
layout: site
title: Home
---

This is Parrot. This is a test.

<h2>Recent Announcements</h2>
<table id="posts-table">
{% for post in site.posts limit:20 %}
    <tr>
        <td class="post-info">
            <span class="post-date">Posted: {{ post.date | date_to_string }}</span>
            <h3 class="post-title"><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></h3>
            <span class="post-tags">
                {% for category in post.categories %}
                    <b>{{ category }}</b> &nbsp;
                {% endfor %}
            </span>
        </td>
    </tr>
{% endfor %}
</table>
