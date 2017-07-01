[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> randoms = np.random.random(1000)

>> pmf = thinkstats2.Pmf(randoms)

>> thinkplot.Pmf(pmf, linewidth = 0.1)

>> thinkplot.Config(xlabel='Random variable', ylabel='PMF')

>>cdf = thinkstats2.Cdf(randoms)

>> thinkplot.Cdf(cdf)

>> thinkplot.Config(xlabel='Random variable', ylabel='CDF')
