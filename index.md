---
layout: default
title: "Welcome to Ortwind.com"
---

# I remember printer woes

This is a normal paragraph following a header. I can change this to describe my intentions for this site, or life in general. What I do with this area has been left entirely up to my imagination.

## See how the backend of this website is setup
[Basic overview of the configuration](http://jmcglone.com/guides/github-pages/){:target="_blank"}

## Additional Resources
[Great Tutorial of how to do this yourself](https://hackernoon.com/how-to-setup-your-jekyll-website-with-free-web-hosting-ssl-and-a-custom-domain-4056ff862ca1){:target="_blank"}

## Markdown Cheatsheet
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet"){:target="_blank"}


## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
