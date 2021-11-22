
### Compiler Core
- [ ] D. Padua and M. Wolfe. "Advanced Compiler Optimizations for Supercomputers," Communications of the ACM, Vol. 29, No. 12, pp. 1184-1201, December 1986.
  - will be presented by `Quanxi Li`
- [ ] Rakesh Ghiya, Daniel Lavery, and David Sehr. "On the Importance of Points-to Analysis and Other Memory Disambiguation Methods for C Programs," Proceedings of the ACM SIGPLAN 2001 Conference on Programming Language Design and Implementation (PLDI'01), Snowbird, UT, June 2001.
- [ ] Michael E. Wolf and Monica S. Lam. "A Data Locality Optimizing Algorithm," ACM SIGPLAN Conference on Programming Languages Design and Implementation, June 1991, pp. 30-44.
- [ ] A. Milanova, A. Rountev, and B. Ryder. "Parameterized Object Sensitivity for Points-To Analysis for Java", ACM Transactions on Software Engineering Methodology, 14(1), pp. 1--41, 2005.
- [ ] Joseph A, Fisher and B. Ramakrishna Rau. "Instruction-Level Parallel Processing," Science, New Series, Vol. 253, No. 5025, September 13, 1991, pp. 1233-1241.
-----
### Compiler Specialization
### Overview
- [ ] Marc Auslander and Martin Hopkins. "An Overview of the PL.8 Compiler," Proceedings of the 1982 SIGPLAN Symposium on Compiler Construction, Boston, MA pp. 22-31, 1982.
- [ ] Kevin O'Brien, Kathryn M. O'Brien, Martin Hopkins, Arvin Shepherd, and Ron Unrau, "XIL and YIL: The Intermediate Languages of TOBEY," ACM SIGPLAN Notices, 30(3), pp. 71-82, March 1993.
- [ ] L. Almagor, K.D. Cooper, A. Grosul, T.J. Harvey, S.W. Reeves, D. Subramanian, L. Torczon, and T. Waterman. "Finding Effective Compilation Sequences," Proceedings of the 2004 Conference on Languages, Compilers, and Tools for Embedded Systems (LCTES), June 2004, pp. 231-230.
- [ ] Chris Lattner and Vikram Adve. " LLVM: A Compilation Framework for Lifelong Program Analysis & Transformation",In Proceedings of the international Symposium on Code Generation and Optimization  (CGO '04), 2004.

### Data Flow Analysis and Optimizations
- [ ] J. B. Kam and J. D. Ullman. "Global Data Flow Analysis and Iterative Algorithms,"Journal of the ACM, 23(1), pp. 158-171, Jan. 1976.
  - This paper covers fundamental material in the area. For additional explanation of this material, refer to the Dragon book: Aho, Lam, Sethi and Ullmann – Chapter 9
  - will be presented by `Yongheng Huang`
- [ ] Barbara G. Ryder and Marvin C. Pauli. "Elimination algorithms for data flow analysis," ACM Computing Surveys, 18 (3), pp. 277-316. September 1986.
- [ ] J. Knoop, O. Ruthing, and B. Steffen. "Lazy Code Motion," Proceedings of the ACM Symposium on Programming Language Design and Implementation (PLDI'92), 1992.
  - For additional explanation of this material, refer to the Dragon book , Section 9.5, or Keith Cooper and Linda Torczon. "Engineering a Compiler", Section 10.3.2, Published by Morgan Kaufman, Second Edition, 2011
  - will be presented by `Zihao Li`

### Static Single Assignment Form and SSA Optimizations
- [ ] B. Alpern, M.N. Wegman, and F.K. Zadeck. "Detecting Equality of Variables in Programs," Proceedings of the 15th Annual ACM Symposium on Principles of Programming Languages, pp. 1-11, 1988.
  - will be presented by `Zihao Li`
- [ ] R. Cytron, J. Ferrante, B. Rosen, M. Wegman, and K. Zadeck. "Efficiently Computing Static Single Assignment Form and The Control Dependence Graph," ACM Transactions on Porgramming Languages and Systems, 13(4), pp. 451-490, October 1991.
  - will be presented by `Zihao Li`
- [ ] Mark N. Wegman and Kenneth Zadeck. "Constatnt Propagation with Conditional Branches," ACM Transactions on Programming Languages and Systems, 13(2), pp. 181-210, April 1991.
  - will be presented by `Zihao Li`

### Dependence Analysis
- [ ] M.E. Wolfe and M. Lam. "A Loop Transformation Theory and an Algorithm to Maximize Parallelism, IEEE Transactions on Parallel and Distributed Systems, 2(4): 452-471, October 1991.
- [ ] R. Allen and K.W. Kennedy. "Automatic Translation of FORTRAN Programs to Vector Form," ACM Transactions on Programming Languages and Systems (TOPLAS), 9(4), October 1987, pp. 491-542.
  - will be presented by `Zhongcheng Zhang` 

### Pointer Analysis
- [ ] B. Steensgaard. "Points-to Analysis in Almost Linear Time," Proceedings of the 23rd Annual ACM Symposium on Principles of Programming Languages (POPL'96), pp. 32-41, January 1996.
  - will be presented by `Yongheng Huang`
- [ ] Manuel Fahndrich, Jeffrey S. Foster, Zhendong Su, and Alexander Aiken. "Partial Online Cycle Elimination in Inclusion Constraint Graphs," Proceedings of the ACM SIGPLAN'98 Conference on Programming Language Design and Implementation, pp. 85-96, June, 1998.
- [ ] Hardekopf, B., & Lin, C. (2007, June). The ant and the grasshopper: fast and accurate pointer analysis for millions of lines of code. In Proceedings of the 28th ACM SIGPLAN Conference on Programming Language Design and Implementation (pp. 290-299).

### Interprocedural Optimization

- [ ] Michael Burke, Linda Torczon. "Interprocedural Optimization: Eliminating Unnecessary Recompilation," ACM Transactions on Programming Languages and Systems, 15(3), July 1993.
- [x] Reps, T., Horwitz, S., & Sagiv, M. (1995, January). Precise interprocedural dataflow analysis via graph reachability. In Proceedings of the 22nd ACM SIGPLAN-SIGACT symposium on Principles of programming languages (pp. 49-61).
  - will be presented by `Yongheng Huang`
  - We directly used the slices of the  [**Static Program Analysis** course](https://pascal-group.bitbucket.io/teaching.html) of Nanjing University 

### Code Generation and Register Allocation
- [ ] C. Fraser, R. Henry, and T. Proebsting. "BURG: Fast Optimal Instruction Selection and Tree Parsing," ACM SIGPLAN Notices, 27(4), pp. 68-76, April 1992.
- [ ] Preston Briggs, Keith Cooper, and Linda Torczon. "Improvements to Graph Coloring Register Allocation," ACM Transactions on Programming Languages and Systems, 16(3), pp. 428-455, May 1994.
- [ ] B.Ramakrishna Rau, Michael S. Schlansker, P. P. Tirumalai. "Code Generation Schema for Modulo Scheduled Loops", In Proceedings of the 25th Annual International Symposium on Microarchitecture(MICRO 25), 1992.
- [ ] Bansal, S., & Aiken, A. (2006). Automatic generation of peephole superoptimizers. ACM SIGARCH Computer Architecture News, 34(5), 394-403.
### Scheduling
- [ ] P.B. Gibbons and S.S. Muchnick. "Efficient Instruction Scheduling for a Pipelined Architecture," ACM SIGPLAN Symposium on Compiler Construction, pp. 11-16, June 1986.
- [ ] W.W. Hwu, et.al. "The Superblock: An Effective Technique for VLIW and Superscalar Compilation," Instruction-Level Parallelism, B.R. Rau and J.A. Fisher (editors), Kluwer Academic Publishers, ISBN 0-7923-9367-8, 1993, pp. 229-248.

### Vectorization
- [x] Larsen, S., & Amarasinghe, S. (2000). Exploiting superword level parallelism with multimedia instruction sets. Acm Sigplan Notices, 35(5), 145-156
  - presented by `Zhongcheng Zhang`, 2021.11.14, 19:00-20:00
  - [PPT Directory Link](https://github.com/zihaoli-cn/compiler-paper-reading/tree/main/material/Compiler%20Specialization/Vectorization)

### Program Synthesis
- [ ] Frigo, M. (1999, May). A fast Fourier transform compiler. In Proceedings of the ACM SIGPLAN 1999 conference on Programming language design and implementation (pp. 169-180).
- [ ] Yotov, K., Li, X., Ren, G., Cibulskis, M., DeJong, G., Garzaran, M., ... & Wu, P. (2003, May). A comparison of empirical and model-driven optimization. In Proceedings of the ACM SIGPLAN 2003 conference on Programming language design and implementation (pp. 63-76).

### Dynamic Analysis
- [ ] Luk, C. K., Cohn, R., Muth, R., Patil, H., Klauser, A., Lowney, G., ... & Hazelwood, K. (2005). Pin: building customized program analysis tools with dynamic instrumentation. Acm sigplan notices, 40(6), 190-200.
- [ ] Gal, A., Eich, B., Shaver, M., Anderson, D., Mandelin, D., Haghighat, M. R., ... & Ruderman, J. (2009). Trace- based just-in-time type specialization for dynamic languages. ACM Sigplan Notices, 44(6), 465-478.

### Correctness
- [ ] Thomas Ball, Rupak Majumdar, Todd Millstein, and Sriram K. Rajamani. "Automatic Predicate Abstraction of C Programs", InProceedings of the ACM SIGPLAN 2001 Conference on Programming Language Design and Implementation (PLDI).  June 2001.
- [ ] Yichen Xie and Alex Aiken. "Saturn: A Scalable Framework for Error Detection Using Boolean Satisfiability",ACM Transactions on Programming Languages and Systems, 29 (3), May 2007.
- [ ] Rastislav Bodik, Rajiv Gupta and Vivek Sarkar. "ABCD: Eliminating Array Bounds Checks on Demand", InProceedings of the ACM SIGPLAN 2001 Conference on Programming Language Design and Implementation (PLDI), June 2000.

### Safe Parallelism
- [ ] Robert L. Bocchino, Vikram S. Adve, Danny Dig, Sarita V. Adve, Stephen Heumann, Rakesh Komuravelli, Jeffrey Overbey, Patrick Simmons, Hyojin Sung, and Mohsen Vakilian. A Type and Effect System for Deterministic Parallel Java. OOPSLA 2009.

### Superoptimizaion
- [ ] Alexia Massalin. Superoptimizer: A Look at the Smallest Program. ASPLOS 1987.

### Garbage Collection
- [ ] David F. Bacon, Perry Cheng, and V. T. Rajan. A Unified Theory of Garbage Collection. OOPSLA 2004.
- [ ] Rifat Shahriyar, Stephen M. Blackburn, and Kathryn S. McKinley. Fast Conservative Garbage Collection. OOPSLA 2014.

### Dynamic Language's Compiler
- [ ] C. Chambers, D. Ungar, and E. Lee. An Efficient Implementation of SELF, a Dynamically-Typed Object-Oriented Language Based on Prototypes, OOPSLA 1989.

### Synthesis-Aided Compilers
- [ ] Phitchaya Mangpo Phothilimthana, Tikhon Jelvis, Rohin Shah, Nishant Totla, Sarah Chasins, and Rastislav Bodik. Chlorophyll: Synthesis-Aided Compiler for Low-Power Spatial Architectures. PLDI 2014.

### Interactive Verification
- [ ] Xavier Leroy. Formal Verification of a Realistic Compiler CACM in 2009.

### Domain Specific Language
- [ ] PLDI '13. Halide: a language and compiler for optimizing parallelism, locality, and recomputation in image processing pipelines.
  - A language for image processing and computational photography.
----
### Programming Languages
- [x] Hoare, C. A. R. (1969). An axiomatic basis for computer programming. Communications of the ACM, 12(10), 576-580.
  - presented by `Zihao Li`, 2021.11.07, 19:00 ~ 20:00
  - [PPT Directory Link](https://github.com/zihaoli-cn/compiler-paper-reading/tree/main/material/ProgrammingLanguages/HoareLogic)
- [ ] Milner, R. (1978). A theory of type polymorphism in programming. Journal of computer and system sciences, 17(3), 348-375.
- [ ] Wegner, P. (1987). Dimensions of object-based language design. ACM Sigplan Notices, 22(12), 168-182.
- [ ] Agha, G. (1990). Concurrent object-oriented programming. Communications of the ACM, 33(9), 125-141.
- [ ] Plotkin, G. D. (1975). Call-by-name, call-by-value and the λ-calculus. Theoretical computer science, 1(2), 125-159.
- [ ] Wadler, P. (1992, February). The essence of functional programming. In Proceedings of the 19th ACM SIGPLAN-SIGACT symposium on Principles of programming languages (pp. 1-14).
