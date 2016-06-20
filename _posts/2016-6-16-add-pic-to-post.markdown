---
layout: post
title:  "Hot to add a picture to a post in Jekyll"
date:   2016-06-16 18:50:21 +0300
categories: jekyll
---
Jekyll is fun, can't wait to see what else I'll be able to implement here. Also I'm trying out some code snippets:

{% highlight Java %}
public static void main(){
System.out.println("Hello everyone xoxo");
}
{% endhighlight %}
here's how you add a pic to this post:
{% highlight HTML %}
![alt text][id]

[id]: /url/to/img.jpg "Title"
{% endhighlight %}

<h1> GOLYANOVO NE BRUKLYN </h1>
![text in case of missing img][img1]

[img1]: /img/bg11.jpg "It's my low res bg pic"
