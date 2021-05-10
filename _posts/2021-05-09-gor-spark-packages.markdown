---
layout: post
title:  "Gor Spark using --packages flag"
date:   2021-05-09 08:31:20 +0000
categories: spark gor
---
GOR Spark 3.10.2 has been released to the spark-packages repository
Use the --packages flag with pyspark or spark-shell to load gor-spark dependencies to your spark job

{% highlight bash %}
pyspark --packages org.gorpipe:gor-spark:3.10.2
spark-shell --packages org.gorpipe:gor-spark:3.10.2
{% endhighlight %}

To skip unwanted packages use --exclude-packages, such as

{% highlight bash %}
 pyspark --packages org.gorpipe:gor-spark:3.10.2 --exclude-packages "org.apache.logging.log4j:log4j-core,org.apache.logging.log4j:log4j-api,net.sourceforge.f2j:arpack_combined_all"
{% endhighlight %}

[https://github.com/gorpipe/gor/releases/tag/v3.10.1](https://github.com/gorpipe/gor/releases/tag/v3.10.1)