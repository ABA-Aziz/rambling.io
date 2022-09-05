---
toc: true
layout: post
description: A minimal example of using markdown with fastpages.
categories: [markdown], [post]
title: Development
---
# Development Timeline

## Intro

This is the timeline of progress on this site. Will be semi-regularly updated, so come back when you can!
## Basic formatting (for other cs students)

You can use *italics*, **bold**, `code font text`, and create [links](https://en.wikipedia.org/wiki/Alan_Turing). Here's a footnote [^1]. Here's a horizontal rule:

---

## Changelog

Most recent additions:

- Added quiz over knowledge of the site and random math question
- Changed the icon on browser

Removed Features:

1. Original icon on browser *replaced with* **kickhopper.png**
1. Original picture on home page. *replaced with* **rider jump.png**

## Quote

> This is a philosophy I live my life by

{% include alert.html text="Give me an answer in fifteen nanoseconds" %}

...Ms. Lanzi (teacher of my friend Leonard Wright, 2004-)

{% include info.html text="You can include info boxes" %}

## Images

![]({{ site.baseurl }}/images/kickhopper.png "my logo")

## Code

An Idea of the Code I do 

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '23.36664289109'
print(546^0.5)
```

    :D

Formatting text as shell commands:

```shell
echo "hello world"
./some_script.sh --option "value"
wget https://example.com/cat_photo1.png
```

Formatting text as YAML:

```yaml
key: value
- another_key: "another value"
```


## Timeline Table

| Date | Action |
|-|-|
| August 19, 2022 | Site was started |
| August 22, 2022 | Updated 'About Me' page |
| August 24, 2022 | Replaced icon on browser, Updated index |
| August 30, 2022 | Added quiz on main page |
| September 2, 2022 | Added changelog |
