---
title: Recursion Patterns, Polymorphism, and the Prelude (CIS194 Wk 3)
author: Matthew Brecknell
event: 166867022
vimeoid: 92976563
---

While completing HW 2, you probably spent a lot of time writing explicitly
recursive functions. At this point, you might think that’s what Haskell
programmers spend most of their time doing. In fact, experienced Haskell
programmers hardly ever write recursive functions!

How is this possible? The key is to notice that although recursive functions
can theoretically do pretty much anything, in practice there are certain common
patterns that come up over and over again. By abstracting out these patterns
into library functions, programmers can leave the low-level details of actually
doing recursion to these functions, and think about problems at a higher
level—that’s the goal of wholemeal programming.

This lecture will cover these recursive patterns, the haskell abstractions that
make them possible and where to find these library functions in the prelude.
We'll also take a tangent into the different between total and partial
functions and why you should care about the difference. 
