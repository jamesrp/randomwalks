# randomwalks

This is some code and notes developed to investigate the Double Dixie Cup
Problem on other graphs.

The double dixie cup problem is a generalization of the classic coupon
collector's problem - how may samples of Uniform({1, ..., n}) does it take to
see each of 1, ..., n at least once? In the double dixie cup problem, we ask how
many samples it takes to see each number at least twice. It turns out that while
the first complete set costs ~ n log n samples, subsequent sets cost only n log
log n samples.

See:

The Double Dixie Cup Problem, Donald J. Newman, The American Mathematical
Monthly, Vol. 67, No. 1 (Jan., 1960), pp. 58-61

The coupon collector problem can be generalized in another way: we can rephrase
it as a random walk on the star graph with n leaves. How long does it take to
visit each node at least once? Given this formulation, it is natural to consider
this question (called the 'cover time') for other graphs, the simplest of which
are the line or cycle on n nodes. See: Lovász, László. "Random walks on graphs:
A survey." Combinatorics, Paul erdos is eighty 2.1 (1993): 1-46.

The aim of these notes is to investigate the 'doubled' problem for the line or
cycle graph (or more generally for random walks on arbitrary graphs): for a
random walk on a graph G, how long does it take until we have visited each node
twice?
