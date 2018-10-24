# cvpr2018-SSAH
the tensorflow code for Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval

hi,everyone.The original code comes from the work https://github.com/lelan-li/SSAH.

I modify the method of reading the data and some small bug I think. The version of tensorflow is 1.4.1. I do not try others, but I think it is ok with little modification. I use python2.

The use of this code:

1.download the Flickr-25k data by google pan:https://drive.google.com/file/d/1DISD-7KSVkcJ8R6AyXvxj2jYSvIIP8G1/view?usp=sharing
Then, put it in the big directory and unzip the data.zip. Last, unzip the all .zip file in the data. 

2.python Main.py

Lastly, I do more experiments. I get the next results with only one epoch:

16bits:
test map: map(i->t): 0.788, map(t->i): 0.785

32bits:
test map: map(i->t): 0.807, map(t->i): 0.802

64bits:
test map: map(i->t): 0.811, map(t->i): 0.795

Welcome everyone to give suggestions and supplements. Thanks
