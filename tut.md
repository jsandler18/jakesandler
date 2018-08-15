---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---
# Building an Operating System for the Raspberry Pi
This is an in depth tutorial on how to write an operating system for the raspberry pi. It assumes prior knowledge of the C language, but does not assume any prior OS Dev
knowledge. The tutorial is broken up into pieces, where each piece is a differenet OS Concept. Each concept has explantions for how to do it, why it is done, and what
purpose it serves.

If you find something confusing, or you have questions or suggestions about this tutorial, submit an issue to [this repo's issue
page](https://github.com/jsandler18/jsandler18.github.io/issues).

If you see a problem with the kernel itself, submit an issue to [the kernel's issue page](https://github.com/jsandler18/raspi-kernel/issues)

If you want to have a discussion, [go to the gitter for this repo](https://gitter.im/raspi-kernel/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
## Tutorial
{% assign items = site.tutorial | sort: 'title' %}
{% for item in items %}
[{{item.title}}]({{item.url}})
{% endfor %}
## Extra Information
{% assign itemss = site.extra | sort: 'title' %}
{% for item in itemss %}
[{{item.title}}]({{item.url}})
{% endfor %}
