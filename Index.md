#Hello, i am William !
## Let´s learn together!
# My Projects
Here is a list of projects that I am working on:
*GitHub Page,
*Refreshing my university knowledge of R,
*Learning PHP.
# My Interests
I'm interested in some networking and to help in GitHub projects
# My Blog
GravityOnline.github.io
I'm really excited to blog my journey on GitHub.com.
# Get in Touch
<ul>
<li><a href="https://twitter.com/{{ site.twitter_username
}}">Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username
}}">GitHub</a></li>
</ul>

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
