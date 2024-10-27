java c
MATH 524, Fall 2018 
Nonparametric Statistics 
First assignment, due Monday, September 30, 2024, noon 
1. Let X be a random variable with cumulative distribution function F. It was shown in class that if F is continuous, then F(X) is uniformly distributed on the interval  (0, 1).   Show  with  an  example  that  this conclusion may not hold if F is discontinuous.
2.  Show analytically that if X1 , X2 , X3   form. a random  sample from a continuous distribution F, then Pr(X1   < X2 < X3 ) = 1/6. Deduce from this the fact that the joint distribution of the associated rank vector (R1 , R2 , R3 ) is uniform.
3.  The effectiveness of vitamin C in orange juice and in synthetic ascorbic acid was compared in 18 guinea pigs (divided at random into two groups of 9) in terms of the length of the odontoblasts after six weeks, with the following results:
Orange juice:     9.4     9.6    9.7    10.0     14.5    15.2     16.1    17.6    21.5
Ascorbic acid:    5.2    5.8    6.4       7.0      7.3    10.1     11.2    11.3     11.5
a) Use Wilcoxon’s rank-sum test statistic to test the hypothesis of no difference against the alternative that the orange juice tends to give rise to larger values.
b) Would the conclusion be different if you used the Kolmogorov– Smirnov statistic?
4.  Suppose that you have 50 subjects at your disposal. What sample size n should be used for the treatment group in order to maximize
a) the variance of Wilcoxon’s rank sum statistic Ws  under H0 ?
b) the total number of possible values for Ws?5. To test the effectiveness of vitamin B1  in stimulating growth in mush- rooms, this vitamin was applied to 13 mushrooms selected at random from a group of 24, while the remaining 11 did not receive this treat- ment. The weights (in mg) of the mushrooms at the end of the period of observation were as follows (Ber. Sc代 写MATH 524, Fall 2018 Nonparametric StatisticsC/C++
代做程序编程语言hweiz. Botan. Ges., 53, 409–456):
Controls: 
18 
14.5 
13.5 
12.5 
23 
24 

Treated: 
27 
34 
20.5 
29.5 
20 
28 

Controls: 
21 
17 
18.5 
9.5 
14 


Treated: 
20 
26.5 
22 
24.5 
34 
35.5 
19 
How significant are these results?  Justify your answer with detailed calculations.
6. As we saw in class, asymmetric alternative to the Siegel–Tukey statistic is obtained by assigning score 1 to both the smallest and largest obser- vation, score 2 to both the second smallest and second largest, etc.  Let T be the sum of scores of the treatment observations.  Find the exact null distribution of this Ansari–Bradley statistic if m = n = 4.
7.  Let X1 , . . . ,Xm  and Y1 , . . . , Yn  be two independent samples from con- tinuous distributions F and G, respectively.  Assign score 1 to both the smallest and largest observations in the combined sample, assign score
2 to the second smallest and the second largest, etc.  Let An  be the sum of the ranks of the observations from the Y-sample.  Show that if H0  : F = G holds and n + m is even, then
E(An) = 4/n(n + m + 2),  var(An) = 48(n + m − 1)/nm{(n + m)2 − 4} .
Hint:   Exploit the  fact that  a  linear transform. of An   is  related  to Wilcoxon’s rank-sum statistic with ties.
8.  In a study involving 2m subjects, m are assigned to treatment and m to control.  Let the control observations be denoted by X  and the treatment observations by Y.   Suppose  that  the  set of observations turns out to have the pattern XY XY ···XY , so that the treatment ranks are 2, 4, . . . , 2m. If large values of Wilcoxon’s rank-sum statistic are significant, use the Gaussian approximation to find the approximate significance probability when m is large.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
