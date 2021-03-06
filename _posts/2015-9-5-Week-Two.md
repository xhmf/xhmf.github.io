---
layout: post
title: Week Two
---

Second week of Software Engineering is over. This week Professor Downing walked us through how we should approach completing the Collatz project, explained the .travis.yml, .gitignore, and makefile files, and discussed various techniques for optimizing our Collatz solution.

I particularly liked the iterative approach we took when covering optimization because it clearly demonstrated how we should go about thinking of solutions to problems on our own, quickly implementing a slow solution that actually works, and then worrying about optimizing it afterwards (I feel like there's an applicable Knuth quote for this). First Downing explained how lazy and eager caching can speed up our program by preventing the program from having to continually recompute subsolutions. He then explained how the solution could be even further optimized through using a meta-cache (create cache beforehand to save even more time) and addressed space limitation by suggesting a meta-cache that tiles the space (don't store every solution but store a subset of the solutions that can be used later to save some computation). Attendance and quizzes were conducted same as usual and were a pleasant reminder that I need to keep up with the assigned readings.

Tip-of-the-week is use a virtual environment when working with Python. This tip probably doesn't apply much to this assignment given that we only need coverage3, but when you're working on different projects that depend on different versions of Python packages it can make managing that a whole lot easier. Also I want to be able to type python instead of python3.
