# cvpr2018-SSAH
the tensorflow code for Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval

hi,everyone.The original code comes from the work https://github.com/lelan-li/SSAH.

I modify the method of reading the data and some small bug I think. The version of tensorflow is 1.4.1. I do not try others, but I think it is ok with little modification. I use python2.

The use of this code:

1.download the Flickr-25k data by google pan:
Then, unzip the data.zip and replace the original directory data/. Last, unzip the all .zip file in the data. 

2.python Main.py

Lastly, I get the result:

================================================
...test map: map(i->t): 0.794, map(t->i): 0.797
...test map: map(t->t): 0.766, map(i->i): 0.828
================================================

Welcome everyone to give suggestions and supplements. Thanks
