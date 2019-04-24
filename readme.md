# Self-Directed Computer Science curriculum

## Purpose

This document is meant to give structure to a self-study in computer science based on personal career and life goals. It will draw heavily
from [Forrest Knight's Open Source CS curriculum](https://github.com/jake-bladt/open-source-cs) and 
[the OSSU computer science course](https://github.com/jake-bladt/computer-science).

Because this is entirely self-directed and not certification seeking, it's focused primarily on three areas of study:

* Subject matter underlying what I already know - theory and math
* Material that has a high probability of being professionally valuable in the next twenty years of my career
* Matieral that will allow me to build systems outside of my professional track, but which can serve the greater good
* Material that can make me more of a "well-rounded developer."

Because I've been a professional software developer for 20+ years, these requirements are markedly different from what a traditional college freshman would find educationally valueable.

## Programming

While programming isn't the first subject in computer science, most CS subjects are explored through programming and a well-stocked programming toolbox is essential to understanding the concepts, theory, and applications of computer science. As such, I'd like to have at least one object-oriented language, one functional language, and one language for system programming. These will be used to create scripts, engines, libraries, web applications, and low-level tools.

My initial toolbox starting out is:

* Comfortable and familiar languages, ideal for hashing out complex ideas and prototyping: C#, JavaScript
* Languages I've used, faster to get up to speed with than starting at the ground floor: Python, Ruby, Java, Clojure, C/C++, Common LISP
* Languages I've never used, but would find valuable to know: Rust, Go, Haskell, F#, OCaml

Based on that toolset, I expect to benefit from the following courses:

* [Linux for Developers](https://www.coursera.org/learn/linux-for-developers) and possibly [Linux Tools for Developers](https://www.coursera.org/learn/linux-tools-for-developers)
* [Programming Languages, Part A](https://www.coursera.org/learn/programming-languages)
* [Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b)
* [Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c)
* [Functional Programming in Haskell](https://www.futurelearn.com/courses/functional-programming-haskell)
* [EPFL's Functional Programming in Scala](https://www.coursera.org/learn/progfun1) may be a prerequisite for the distributed systems specialization below
* [O'Reilly's Rust Programming Learning Path](https://learning.oreilly.com/learning-paths/learning-path-learn/9781789809398/)
* [UCI's "Programming with Google Go path](https://www.coursera.org/specializations/google-golang)

## Math and underlying theory

The OSSU recommendations are very math heavy and, at this point, it's not entirely clear to me whether or not they're needed for anyting I want to create. I'm sure I would benefit from a survey course at least as review of material I covered 30+ years ago. Because I want to at least survey machine learning as a field (and possibly make it my core focus,) I should have an underpinning in statistics and probability. Plenty of the problems I've addressed as a developer required an understanding of graphs, so graph theory is a must. Likewise matrix transformations and linear algebra.

On the other hand, I've encountered differential and integral calculus exactly twice in my career - once to calculate the value of conjoined cashflows (ie stocks that pay dividends) over time and once when my client was considering commissioning his own digital signal processing library, but ultimately decided to buy a third-party library. I'm holding off on adding calculus to this curriculum until I see a need for it.

(As with every part of this document, this section may be modified over time as new information comes in.)

Math requirements:

* Either UC San Diego's [Mathematical Thinking in Computer Science](https://www.coursera.org/learn/what-is-a-proof) and the other courses in Introduction to Discrete Mathematics for Computer Science Specialization or MIT's [Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/index.htm).
* Duke's [Introduction to Probabily and Data](https://www.coursera.org/learn/probability-intro)
* Udacity's [Introduction to Statistics](https://www.udacity.com/course/intro-to-statistics--st101)
* UT's [Linear Algebra - Foundations to Frontiers](https://www.edx.org/course/linear-algebra-foundations-to-frontiers), backed by [this video series](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
* UCSD's [Intro to Graph Theory](https://www.coursera.org/learn/graphs)

A lot of courses are a mixture of some theory and some systems/applications. Of the purer theory courses, I would benefit from reviewing the following:

* Algorithms - Princeton's three-course track on algorithms - [intro](https://www.classcentral.com/course/coursera-computer-science-algorithms-theory-and-machines-10671), [Part I](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/about), and [Part 2](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/about)
* Data Structures - University of Michigan's [Python Data Structures](https://www.coursera.org/learn/python-data) - prework for setting up Python may be in previous course
* Computational Geometry Tsinghua University's [Computational Geometry](https://www.edx.org/course/ji-suan-ji-he--computational-geometry)
* Debugging - Udacity's [Debugging](https://www.udacity.com/course/software-debugging--cs259)
* Testing - Udacity's [Software Testing](https://www.udacity.com/course/software-testing--cs258) and University of Texas's [LAFF](https://www.edx.org/course/laff-on-programming-for-correctness)
* Logic - Standford's [Introduction to Logic](https://www.coursera.org/learn/logic-introduction) - may require pre-work in Set Theory
* Automata Theory - Stanford's [Automata Theory](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+SelfPaced/about)
* Formal Concept Analysis - National Research University Higher School of Economics' [Introduction to Formal Concept Analysis](https://www.coursera.org/learn/formal-concept-analysis)
* Parallelism - EPFL's [Parallel Programming](https://www.coursera.org/learn/parprog1)
* Architecture & Design - Georgia Tech's [Software Architecutre & Design](https://www.udacity.com/course/software-architecture-design--ud821)
* Distributed Systems - Reliable Distributed Algorithms - [I](https://www.edx.org/course/reliable-distributed-algorithms-part-1-kthx-id2203-1x-0), [II](https://www.edx.org/course/reliable-distributed-algorithms-part-2-kthx-id2203-2x)

## Systems & Applications

With some of these subjects, the free MOOC model may break down - in which case I'll either rely on commercial resources I have available (O'Reilly Learning and Pluralsight, primarily) or seek to accumulate enough free material in one place to simulate a directed course.

* First Principles - Build a Modern Computer from First Principles: From Nand to Tetris Part [I](https://www.coursera.org/learn/build-a-computer) and [II](https://www.coursera.org/learn/nand2tetris2)
* Operating Systems - [Udacity's Introduction to Operating Systems](https://www.udacity.com/course/introduction-to-operating-systems--ud923) or possibly start with [Hack the Kernel](https://www.ops-class.org/) and [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
* Compilers Stanford's [Compilers](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/about) course
* Computer Graphics - UC San Diego's [Computer Graphics](https://www.edx.org/course/computer-graphics)
* Computer Networking - Stanford's [Introduction to Computer Networking](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about)
* Databases - Stanford's [Introduction to Database Systems](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about)
* Machine Learning - Stanford's [Introduction to Machine Learning](https://www.coursera.org/learn/machine-learning)
* Cryptography - Standford's [Cryptography I](https://www.coursera.org/learn/crypto)
* Cloud Computing and Virtualization
* DevOps
* Cybersecurity - [Enterprise System Management and Security](https://www.coursera.org/learn/enterprise-system-management-security) and possibly the courses that follow on that track

## Capstone Project

As I go through the course material, I will be looking for an opportunity to contribute to FOSS projects and to create my own unique and useful capstone FOSS project. It may turn out to be Uduu Project: Nimrod.
