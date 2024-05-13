---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Will you join us in helping save food so all can eat? Every little bit counts and we are glad you are here!



{% for post in site.posts %}
<div class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
        {% if post.image %}
        <img src="{{ post.image | markdownify }}" alt="{{ post.image }}" style="width:100%; max-width:300px; height:auto;">
        {% endif %}
        <h2>{{ post.title }}</h2>
        {% if post.blurb %}
        <p>{{ post.blurb }}</p>
        {% endif %}
    </a>
    <p class="post-meta">Posted on {{ post.date | date: "%b %-d, %Y" }}</p>
</div>
{% endfor %}
