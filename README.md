##Approximate String Matching##

###KAUST AMCS 260 Final Project###

**Team Member :** 

>Gang Liao, liao.gang@kaust.edu.sa
>
>Fatima Zohra Smaili, fatimazohra.smaili@kaust.edu.sa
>
>Wentao Hu, wentao.hu@kaust.edu.sa
>
>Guangming Zang, guangming.zang@kaust.edu.sa

>King Abdullah University of Science and Technology (KAUST)
>
>Computer, Electrical and Mathematical Sciences and Engineering (CEMSE) Division

###1. Introduction###

String matching algorithms are an important class of algorithms in Computer Science used to solve some famous problems mainly `DNA strings matching, text processing, spell checking, spam filtering`. 

The idea behind them is to quickly find the first or all occurrences of a string in a text. In other words, given a text string T and a pattern P, we need to find a quick way to find whether there is any occurrence in P and where it appears in case it exists. 

A slightly different but more interesting problem is `approximate string matching problem`, which is the problem we chose to work on for our project. For the approximate string matching problem we look for a substring that is similar to pattern P in text T. The word similar here refers to a string that needs a minimum number of operations (`insertion, deletion and substitution`) to be converted to P. `This minimum number of operations is what we refer to as the edit distance.` 

[In our proposal](https://drive.google.com/file/d/0B2t5vXTh12G3TWl4NXRKQUFfT3M/view?usp=sharing), we will try to give a brief overview on the `two approximate string matching algorithms` we chose to work with, [2][6].

Approximate string matching is one of the main problems in classical algorithms, with applications to `text searching, computational biology, pattern recognition, etc.` Many algorithms have been presented that improve approximate string matching, for instance [1-6]. We decide to implement two of them and compare them via the time and space complexity.

###2. TimeLine###

####September####
- [x] ~~Review and research on the topic and its applications~~
- [x] ~~Review specific papers on the two algorithms chosen~~
- [x] ~~Task dispatching among team members~~

####October####
- [x] ~~Implementation of the algorithms~~
- [x] ~~Preparation of Midterm Presentation~~  `Gang and Fatima gave the midterm presentation.`
- [x] ~~Preparation of Midterm Report~~ 

####November####
- [x] ~~Evaluation of the implemented algorithms on different case studies~~
- [x] ~~Analysis of time and space complexity of the algorithms~~
- [x] ~~Synthesis and comparison of the algorithms~~
- [x] ~~Work on improving the existing algorithms as future work~~
- [x] ~~Preparation of Final Presentation and Report~~ `Wentao and Guangming gave the final presentation.`

`Thank all you guys for hardwork!`

###References###

```
[1] E. Ukkonen, Finding approximate patterns in strings, Journal of algorithms, vol. 6, no. 1,pp. 132{137, 1985.

[2] G. Navarro and R. Baeza Yates, Very fast and simple approximate string matching, Information Processing Letters, vol. 72, no. 1, pp. 65-70, 1999.

[3] G. M. Landau and U. Vishkin, Fast parallel and serial approximate string matching, Journal of algorithms, vol. 10, no. 2, pp. 157{169, 1989.

[4] R. A. Baeza Yates and C. H. Perleberg, Fast and practical approximate string matching, in Combinatorial Pattern Matching. Springer, 1992, pp. 185-192.

[5] R. Baeza-Yates and G. Navarro, Faster approximate string matching, Algorithmica, vol. 23,no. 2, pp. 127-158, 1999.

[6] H. Hyyro, Bit-parallel approximate string matching algorithms with transposition, in String Processing and Information Retrieval. Springer, 2003, pp. 95-107.

[7] S. Wu and U. Manber,Fast text searching with errors. University of Arizona, Department of Computer Science, 1991
```
