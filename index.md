---
title: Joel Brendle Blog
feature_text: ''
feature_image: https://raw.githubusercontent.com/joelbrendle/JoelWebsite/master/images/titlepicture.jpg
excerpt: Joel Brendle Blog

---
Blog von [Joel Brendle](https://joelbrendle.ch).  
Veröffentliche hier über alles mögliche was mich so interessiert. :D

## Neuste Posts:

{% for post in site.posts %}

<li><h2><a href="{{ post.url }}">{{ post.title }}</a></h2>{{ post.excerpt }}</li>

{% endfor %}

{% include button.html text="English Version 🇬🇧" link="#" color="#242e2b" %} {% include button.html text="PayPal 🤑" link="https://paypal.me/notjoel/" color="#0366d6" %}