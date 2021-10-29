# 编译器特别兴趣小组-论文研讨班
## Motivation
> 吾尝终日而思矣，不如须臾之所学也；吾尝跂而望矣，不如登高之博见也...... 君子生非异也，善假于物也。
> 
> ——荀子，《劝学》

- 发现做理论的同学，他们组里基本上都会有开研讨班这样的传统，大概就是大家一起来刷某本书，轮流领导讲课，然后共同解决课后习题。在国外许多PhD的研讨课上也是采用研讨的方法来研读论文。后来也在知乎上看到某位大佬自己组织数据库相关的研讨班。和小伙伴交流之后，发现好多人都有同样的兴趣和苦恼，所以大家决定一起组织起来这个研讨班，共同进步、共同提高。
- 学术上的进步需要多和人讨论
  - 大家一起讨论，能体会看待同一个问题的不同视角。同样一篇论文，学习一下别人会用什么样的方式来完成一个汇报
  - 通过回答别人的提问，能提高自己对问题理解的深度，发现自己阅读论文时没有注意到的问题
  - 做学术，需要频繁的跟别人展示自己的工作，也当作对自己论文阅读能力、表达能力的一次长期训练
- 贵在坚持
  - 这么多经典论文，通过自己精读、作报告或听别人作报告的方式学习完，也是一件很了不起的事情

## Paper List
主要来源于[UIUC Compilers Track PhD Qualifying Exam](http://rsim.cs.uiuc.edu/arch/compiler_qual.html)和崔老师给的论文阅读列表

### Compiler Core
- [ ] D. Padua and M. Wolfe. "Advanced Compiler Optimizations for Supercomputers," Communications of the ACM, Vol. 29, No. 12, pp. 1184-1201, December 1986.
- [ ] Rakesh Ghiya, Daniel Lavery, and David Sehr. "On the Importance of Points-to Analysis and Other Memory Disambiguation Methods for C Programs," Proceedings of the ACM SIGPLAN 2001 Conference on Programming Language Design and Implementation (PLDI'01), Snowbird, UT, June 2001.
3. Michael E. Wolf and Monica S. Lam. "A Data Locality Optimizing Algorithm," ACM SIGPLAN Conference on Programming Languages Design and Implementation, June 1991, pp. 30-44.
- [ ] R. Cytron, J. Ferrante, B. Rosen, M. Wegman, and K. Zadeck. "Efficiently Computing Static Single Assignment Form and The Control Dependence Graph," ACM Transactions on Porgramming Languages and Systems, 13(4), pp. 451-490, October 1991.
- [ ] Joseph A, Fisher and B. Ramakrishna Rau. "Instruction-Level Parallel Processing," Science, New Series, Vol. 253, No. 5025, September 13, 1991, pp. 1233-1241.
- [ ] Larsen, S., & Amarasinghe, S. (2000). Exploiting superword level parallelism with multimedia instruction sets. Acm Sigplan Notices, 35(5), 145-156
- [ ] Luk, C. K., Cohn, R., Muth, R., Patil, H., Klauser, A., Lowney, G., ... & Hazelwood, K. (2005). Pin: building customized program analysis tools with dynamic instrumentation. Acm sigplan notices, 40(6), 190-200.
-----
### Compiler Specialization
### Overview
- [ ] Marc Auslander and Martin Hopkins. "An Overview of the PL.8 Compiler," Proceedings of the 1982 SIGPLAN Symposium on Compiler Construction, Boston, MA pp. 22-31, 1982.
- [ ] Kevin O'Brien, Kathryn M. O'Brien, Martin Hopkins, Arvin Shepherd, and Ron Unrau, "XIL and YIL: The Intermediate Languages of TOBEY," ACM SIGPLAN Notices, 30(3), pp. 71-82, March 1993.
- [ ] L. Almagor, K.D. Cooper, A. Grosul, T.J. Harvey, S.W. Reeves, D. Subramanian, L. Torczon, and T. Waterman. "Finding Effective Compilation Sequences," Proceedings of the 2004 Conference on Languages, Compilers, and Tools for Embedded Systems (LCTES), June 2004, pp. 231-230.
- [ ] Chris Lattner and Vikram Adve. " LLVM: A Compilation Framework for Lifelong Program Analysis & Transformation",In Proceedings of the international Symposium on Code Generation and Optimization  (CGO '04), 2004.

### Data Flow Analysis and Optimizations
- [ ] J. B. Kam and J. D. Ullman. "Global Data Flow Analysis and Iterative Algorithms,"Journal of the ACM, 23(1), pp. 158-171, Jan. 1976.
- [ ] Barbara G. Ryder and Marvin C. Pauli. "Elimination algorithms for data flow analysis," ACM Computing Surveys, 18 (3), pp. 277-316. September 1986.
- [ ] J. Knoop, O. Ruthing, and B. Steffen. "Lazy Code Motion," Proceedings of the ACM Symposium on Programming Language Design and Implementation (PLDI'92), 1992.

### Static Single Assignment Form and SSA Optimizations
- [ ] B. Alpern, M.N. Wegman, and F.K. Zadeck. "Detecting Equality of Variables in Programs," Proceedings of the 15th Annual ACM Symposium on Principles of Programming Languages, pp. 1-11, 1988.
- [ ] Mark N. Wegman and Kenneth Zadeck. "Constatnt Propagation with Conditional Branches," ACM Transactions on Programming Languages and Systems, 13(2), pp. 181-210, April 1991.

### Dependence Analysis
- [ ] M.E. Wolfe and M. Lam. "A Loop Transformation Theory and an Algorithm to Maximize Parallelism, IEEE Transactions on Parallel and Distributed Systems, 2(4): 452-471, October 1991.
- [ ] R. Allen and K.W. Kennedy. "Automatic Translation of FORTRAN Programs to Vector Form," ACM Transactions on Programming Languages and Systems (TOPLAS), 9(4), October 1987, pp. 491-542.

### Pointer Analysis
- [ ] B. Steensgaard. "Points-to Analysis in Almost Linear Time," Proceedings of the 23rd Annual ACM Symposium on Principles of Programming Languages (POPL'96), pp. 32-41, January 1996.

- [ ] Manuel Fahndrich, Jeffrey S. Foster, Zhendong Su, and Alexander Aiken. "Partial Online Cycle Elimination in Inclusion Constraint Graphs," Proceedings of the ACM SIGPLAN'98 Conference on Programming Language Design and Implementation, pp. 85-96, June, 1998.
- [ ] Hardekopf, B., & Lin, C. (2007, June). The ant and the grasshopper: fast and accurate pointer analysis for millions of lines of code. In Proceedings of the 28th ACM SIGPLAN Conference on Programming Language Design and Implementation (pp. 290-299).

### Interprocedural Optimization

- [ ] Michael Burke, Linda Torczon. "Interprocedural Optimization: Eliminating Unnecessary Recompilation," ACM Transactions on Programming Languages and Systems, 15(3), July 1993.
- [ ] Reps, T., Horwitz, S., & Sagiv, M. (1995, January). Precise interprocedural dataflow analysis via graph reachability. In Proceedings of the 22nd ACM SIGPLAN-SIGACT symposium on Principles of programming languages (pp. 49-61).

### Code Generation and Register Allocation
- [ ] C. Fraser, R. Henry, and T. Proebsting. "BURG: Fast Optimal Instruction Selection and Tree Parsing," ACM SIGPLAN Notices, 27(4), pp. 68-76, April 1992.
- [ ] Preston Briggs, Keith Cooper, and Linda Torczon. "Improvements to Graph Coloring Register Allocation," ACM Transactions on Programming Languages and Systems, 16(3), pp. 428-455, May 1994.
- [ ] B.Ramakrishna Rau, Michael S. Schlansker, P. P. Tirumalai. "Code Generation Schema for Modulo Scheduled Loops", In Proceedings of the 25th Annual International Symposium on Microarchitecture(MICRO 25), 1992.

### Scheduling
- [ ] P.B. Gibbons and S.S. Muchnick. "Efficient Instruction Scheduling for a Pipelined Architecture," ACM SIGPLAN Symposium on Compiler Construction, pp. 11-16, June 1986.
- [ ] W.W. Hwu, et.al. "The Superblock: An Effective Technique for VLIW and Superscalar Compilation," Instruction-Level Parallelism, B.R. Rau and J.A. Fisher (editors), Kluwer Academic Publishers, ISBN 0-7923-9367-8, 1993, pp. 229-248.

### MISC
- [ ] Frigo, M. (1999, May). A fast Fourier transform compiler. In Proceedings of the ACM SIGPLAN 1999 conference on Programming language design and implementation (pp. 169-180).
- [ ] Yotov, K., Li, X., Ren, G., Cibulskis, M., DeJong, G., Garzaran, M., ... & Wu, P. (2003, May). A comparison of empirical and model-driven optimization. In Proceedings of the ACM SIGPLAN 2003 conference on Programming language design and implementation (pp. 63-76).
- [ ] Gal, A., Eich, B., Shaver, M., Anderson, D., Mandelin, D., Haghighat, M. R., ... & Ruderman, J. (2009). Trace- based just-in-time type specialization for dynamic languages. ACM Sigplan Notices, 44(6), 465-478.
- [ ] Bansal, S., & Aiken, A. (2006). Automatic generation of peephole superoptimizers. ACM SIGARCH Computer Architecture News, 34(5), 394-403.

----
### Programming Languages
- [ ] Hoare, C. A. R. (1969). An axiomatic basis for computer programming. Communications of the ACM, 12(10), 576-580.
- [ ] Milner, R. (1978). A theory of type polymorphism in programming. Journal of computer and system sciences, 17(3), 348-375.
- [ ] Wegner, P. (1987). Dimensions of object-based language design. ACM Sigplan Notices, 22(12), 168-182.
- [ ] Agha, G. (1990). Concurrent object-oriented programming. Communications of the ACM, 33(9), 125-141.
- [ ] Plotkin, G. D. (1975). Call-by-name, call-by-value and the λ-calculus. Theoretical computer science, 1(2), 125-159.
- [ ] Wadler, P. (1992, February). The essence of functional programming. In Proceedings of the 19th ACM SIGPLAN-SIGACT symposium on Principles of programming languages (pp. 1-14).
