[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

>> import scipy.stats

>> mu = 178

>> sigma = 7.7

>> dist = scipy.stats.norm(loc=mu, scale=sigma)

>> low = dist.cdf(177.8)

>> high = dist.cdf(185.4)

>> high - low
