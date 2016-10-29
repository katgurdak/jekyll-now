---
layout: post
title: Big O(h my god, what is this) Notation
---

Hey! So I'm going to take my best shot at Big O notation. Feel free to give any feedback as I'm always looking to learn! Now, there's quite a bit to go over but I'll break it down into manageable bites. Hope you enjoy the first part!

Let's start off with - what exactly is Big O notation?? Looking at our handy dandy [Wikipedia](https://en.wikipedia.org/wiki/Big_O_notation), it says that it's "used to classify algorithms by how they respond to changes in input size, such as how the processing time of an algorithm changes as the problem size becomes extremely large."

From within that description, we can pick out two major components - time and input size. Big O notation's whole thing is based on the relationship between those two elements. It looks at your algorithm and asks "How does it scale?" - it being the number of operations it takes to solve the problem.

Put simply, as we increase the input size, how does that affect the time of your algorithm? Will it stay the same? Will it increase exponentially?

If you've ever come across something like O(log n), you've come across Big O notation and if it looks crazy, don't worry. That's simply a way to describe the rate of growth. I'll be going over a few different types later and my goal is that by the end of it, it'll look not only crazy - but crazy easy.

Keep hacking, everybody!