---
layout: post
title:  "Gor 3.10.1 released"
date:   2021-05-08 08:21:20 +0000
categories: gor release
---
Gor has been updated to version 3.10.1, featuring updates to the file driver framework.

For instance, now you can write to remote paths such as s3

{% highlight bash %}
gor #genes# | write s3://ref_genome/genes.gorz
{% endhighlight %}

[https://github.com/gorpipe/gor/releases/tag/v3.10.1](https://github.com/gorpipe/gor/releases/tag/v3.10.1)
