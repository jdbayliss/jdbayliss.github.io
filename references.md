## <center>Data-Oriented Design: References</center>

There are many available references for data-oriented design that have been primarily put into the following github repo:

[Github list of resources by dbartolini](https://github.com/dbartolini/data-oriented-design)

There are also a lot of related topics having to do with hardware, optimization, and lots of other topics that I find helpful knowledge for data-oriented design:

1. Free Talks not in the list above:
- [A Data Oriented Approach to Using Component Systems (2018)](https://www.youtube.com/watch?v=p65Yt20pw0g&t=3398s) 
- [SIMD at Insomniac Games (How We Do the Shuffle) : good description of SOA vs. AOS and how to think about SIMD](http://gdcvault.com/play/1022248/SIMD-at-Insomniac-Games-How)  
- [Massively Parallel AI for GPGPUs using OpenCL or C++ (2014) : gives a good overview of modern hardware and power usage](http://gdcvault.com/play/1020618/Massively-Parallel-AI-on-GPGPUs) 
- [Code Clinic: How to Write Code the Compiler can Actually Optimize  (2015) ](http://gdcvault.com/play/1021866/Code-Clinic-2015-How-to)  [2014] (http://gdcvault.com/play/1020472/Code-Clinic-How-to-Write )
- [Three Big Lies: Typical Design Failures in Game Programming (2010)](http://gdcvault.com/play/1012200/Three-Big-Lies-Typical-Design )
2. Data-Oriented Design and Thinking about Data
- [Typical C++ BS talk](https://macton.smugmug.com/Other/2008-07-15-by-Eye-Fi/n-xmKDH/i-BrHWXdJ)  [code](http://codepad.org/u3yqprPJ)
- [A Mathematical Theory of Communication - Claude Shannon](http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)
3. Hardware Topics
- [Basics of speculative execution](https://fgiesen.wordpress.com/2013/03/04/speculatively-speaking/ )
- [Gamasutra article that talks a bit about load-hit-store](http://www.gamasutra.com/view/feature/3687/sponsored_feature_common_.php )
- [Basics of pipelining](http://scalibq.wordpress.com/2012/02/19/cpus-and-pipelines-how-do-they-work/ )
- [Write and replacement policies](http://en.wikipedia.org/wiki/Cache_algorithm)
- [Coherency issue from xbox360 engineer](https://randomascii.wordpress.com/2018/01/07/finding-a-cpu-design-bug-in-the-xbox-360/)
4. Laying out Data Structures
- [Benchmark comparison of common STL data structures](https://baptiste-wicht.com/posts/2012/12/cpp-benchmark-vector-list-deque.html )
- [Alignment](http://www.ibm.com/developerworks/library/pa-dalign/)
- [Spatial hashing intro: Big Fast Crowds on the PS3 - Craig Reynolds (presented at SIGGRAPH Sandbox 2006)](https://www.researchgate.net/publication/220007853_Big_fast_crowds_on_PS3)
- [Allocator issues EA Document](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2007/n2271.html )
5. Parallelization
- [Several concurrency talks by Mike Acton](https://cellperformance.beyond3d.com/articles/2009/08/roundup-recent-sketches-on-concurrency-data-design-and-performance.html)
6. Overall philosophy about why things don't work the way you want them to
- [The Law of Leaky Abstractions by Joel Spolsky](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/)
7. Optimization
- [Branch removal & good for using bitwise ops](http://cellperformance.beyond3d.com/articles/2006/04/benefits-to-branch-elimination.html )
- [Example of branch avoidance for chess](https://chessprogramming.wikispaces.com/Avoiding+Branches )
- [Optimization basics for hardware](http://www.agner.org/optimize/ )
 
 