---
layout: post
title: Don't mind me, just learning jekyll
categories: blog
date: 2017-02-06
published: true
---

this right here should be math:
\\[ \frac{1}{n^{x}} \\]



more math?!

$$softmax(x) =    \frac{e^{x}}  {\sum_{i} e^{x_i}}  $$


$$h_\theta =  \sigma(reLU(X.W_1+b_1).W_2 + b_2)  $$


this right here should be an image:
![what the fuck]({{ site.url }}/images/anneke2.jpg)


this right here should be some python code:

{% highlight python %}
def to_onehot(intarray):
    n = len(intarray)
    d = intarray.max()
    y=np.zeros((n,d))
    for i in range(n):
        y[i,intarray[i]] = 1
    return y
{% endhighlight %}



this right here should be a youtube video:

<iframe width="854" height="480" src="https://www.youtube.com/embed/FL5M1H-Rljk?ecver=1" frameborder="0" allowfullscreen></iframe>

this seems pretty easy
