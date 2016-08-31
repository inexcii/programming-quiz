# description

for example, there are arrays like the following:

* a[0] = 1, a[1] = 4, a[2] = 6, a[3] = 10, a[4] = 6, a[5] = 16

* In this array,
  1. a[1] and a[2], a[1] and a[4] is the adjacent value
  1. the index of a[1] and a[4], thus 1 and 4 (instead of a[1] and a[2]) is called 'distance'

So, write a program, for any possible arrays, to caculate the 'distance' if there is adjacent values in there, if not, return -1.