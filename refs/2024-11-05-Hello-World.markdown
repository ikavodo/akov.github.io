---
title: "Hello World!"
layout: post
date: 2024-11-05 16:38
image: /assets/HelloWorld.svg
headerImage: True
tag:
- Hello
- World
star: true
category: blog
author: Ido Akov
description: Hello World!
---

## Hello World

This is me saying [Hello World][1] in lots of ways to learn Markdown.

![Hello World SVG](/assets/HelloWorld.svg)

---

## SVGs

Inline SVG:

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 100">
  <text x="10" y="40" font-family="Verdana" font-size="24" fill="black">Hello, World!</text>
</svg>

---

##Raw text

{% highlight raw %}
# This is a simple comment
def hello_world():
    print("Hello, World!")
{% endhighlight %}

---

## Linking

![Hello World SVG](https://upload.wikimedia.org/wikipedia/commons/2/28/HelloWorld.svg)
---

## Lists

### Ordered list

1. Hello
2. World
3. Hello

### Unordered list

* World
* Hello
* World

---

## Quote

> <strong>"Hello World"</strong>  
> — Someone
---


## Code

A Python example:
```python
    print("Hello, World!")
```

And another

{% highlight python %}
def hello_world():
    print("Hello, World!")
{% endhighlight %}


And a third
<script src="https://gist.github.com/HeyJunho/ad334605be8915a5f3676768a85edb37.js"></script>


[1]: https://en.wikipedia.org/wiki/%22Hello,_World!%22_program
