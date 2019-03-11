### T-test from scratch

Just a numpy t-test implementation with SPSS-like result table.


Great for understanding underlying math. For other purposes, give yourself a break and use the scipy:

```
from scipy import stats
group1 = stats.norm.rvs(loc=5,scale=10,size=500)
group2 = stats.norm.rvs(loc=5,scale=10,size=500)
stats.ttest_ind(group1,group2, equal_var=True)
```
