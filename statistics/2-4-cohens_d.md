[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> print(firsts.totalwgt_lb.mean(), others.totalwgt_lb.mean())
 
>> #function definition

def CohenEffectBabySize(first_babies, other_babies):

    diff = first_babies.mean() - other_babies.mean()
    
    var1 = first_babies.var()
    var2 = second_babies.var()
    n1 = len(first_babies)
    n2 = len(other_babies)
    
    pooled_variace = (n1 * var1 + n2 * var2)/(n1 + n2)
    d = diff / np.sqrt(pooled_variance)
    
    return d

>> print(CohenEffectBabySize(firsts.totalwgt_lb, others.totalwgt_lb))
