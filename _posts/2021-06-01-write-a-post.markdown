---
layout: post
title: "Write a Post"
date: 2021-05-31
categories: jekyll blogging
---

The goal of this article is to add some extra info about blog writing with _Jekyll_.

## Structure your posts

Use level 2 (`##`) and if necessary level 3 (`###`) titles to structure your posts.

## Display code snippets

You can display a block of code like the following using the 3 backticks before and after. You can specify the language after the 3 first backticks.

````python
```python
def hello(name):
    return f'hello {name}'
```
````

## Add images

Create an `assets` folder where you can put all your images, then link them like this `![my inspiring image](/assets/sample-image.jpg)`.

![my inspiring image]({{ "/assets/sample-image.jpg" | relative_url }})
_Photo by [Ian Schneider](https://unsplash.com/@goian)_
