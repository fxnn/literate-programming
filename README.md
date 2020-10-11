# literate-programming

A new-style literate programming framework, designed in a time of test-driven development and self documenting code.

_**Note:** This repository contains only an_ idea _, so no code to expect here._


## Problem statement

For a software developer, taking about code is a simple necessity if he wants his skills to learn and grow.

Now, in talking, mankind has thousands of years of experience -- and in a special form of it, where one person talks and the others learn: narration.

[Literate programming](https://en.wikipedia.org/wiki/Literate_programming) brings together the concept of narration and the art of programming. First [introduced by Donald E. Knuth in 1984](http://www.literateprogramming.com/knuthweb.pdf), it has [caught some attention](https://wiki.c2.com/?LiterateProgrammingIdeas), although most modern computer science students or software development practitioners would consider it purely academic.

Too sad, because it's a concept that might be helpful for talking and discussion about code, and thus jointly finding better ways of writing code.


## Idea

One reason why Knuth's literate programming might seem academic (or even old fashioned) might be that Knuth used Pascal, C and TeX, which miss quite a lot of modern language's features, tooling and ecosystem.

Another reason might be that also the programming workflow, and the way of writing code (even in the same languages) changed (which, by the way, could very well have been influenced by literate programming).
Even though Knuth stated that, using literate programming, he started to use more speaking variable names, his code might still seem hard to read and maintain to some today's developers.
And by the way, where are his tests?

Actually, a modern literate programming tool would need to support the fast feedback cycles developers are used to nowadays, especially in terms of red/green bars for their TDD code.

And of course, the tests would be an integral part of every result document, as if you think of it: we improved our code documentation skill considerably in the last centuries.
Our tests document the requirements, the code self-documents the implementation.
What's missing is a documentation of the higher structure, of what's in between all the functions, methods, structs and classes, of their ordering, relationship and dependencies.
That's the gap literate programming could fill.

And it could be embedded in today's means of communication.
Why not blogging about a literate program while it's in progress?
Every week or so, the authors publish a new part of it, another chapter, and they immediately receive feedback through comments and pull requests.
Ultimately, as we know it from pair and [mob programming](https://en.wikipedia.org/wiki/Mob_programming), a discussion about practices and methods arises and everyone learns and grows in their skills.


## Approach

1. Research for modern literate programming tools, their tooling and integration, their general code readability and maintainability and finally their support for TDD.
2. Look out for a suitable prototype project and platform (e.g. blogging/publishing platform).
3. Look out for some time and do the thing!
