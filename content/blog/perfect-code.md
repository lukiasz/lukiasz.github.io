+++
date = 2023-08-03
published = true
title = "Does your code has to be perfect?"

[taxonomies]
tags = ["programming"]
+++

One of thoughts that came to my mind some time ago was the conflict between spending more time on *perfect* code vs iterating quickly while having *good enough* code.

So... What is perfect code at all? Can we express it in objective terms meaning that some fragment is perfect or closer to perfection than the other fragment?

<!-- more -->

Consider two snippets:
```
for (int i = 0; i < n; ++i)
{
    ...
}
```
vs
```
var range = Enumerable.Range(0, n).Select(x => ...);
```

There are multiple people with different mindsets, experiences, personal tastes, and so on. But... If there would be an omniscient programming god who could judge - which snippet would he choose?

## You can't judge code without knowing context

And the answer is... **the first one**!

Just kidding 😊. No one can answer to that question without knowing the context. The first fragment is doing *something*, and the second one is doing *something else*. One can explain what the computer will do when executing these of two fragments - how it'll be interpreted, what would be the result, maybe some performance characteristics and other details and... that's it. Can't objectively tell which one is better.

We're writing the code to solve some problems, and without knowing the problem, we can't judge the code. For the sake of the argument, imagine these fragments being sent to [The International Obfuscated C Code Contest](https://www.ioccc.org/). Both of them would be totally bad because they aren't obfuscated at all, and they're not even written in C. But even without going to such extremes, the answer is still not obvious. Maybe we could start asking whether such code was part of some performance-critical library? Or maybe that doesn't matter even in that case? Maybe the **n** is small and the code is not on the hot path at all?

The example is just a loop written in two flavors. In the everyday life, we're choosing from an infinite number of possible solutions that require more analysis. How on earth could anyone say which fragment of code is better without knowing the context?

## You need to judge the solution

These isn't just *perfect* code without the problem that it solves, but I guess there could be a *perfect* solution to a given problem, available for those who know the entire state of the universe 😊 Exploring problem domain – sometimes interesting, sometimes laborious work – must suffice for the rest of us 😊. Quite a big part of working as a programmer is uncovering the problem. The more variables you take into consideration, the better solution you can create.

And that better solution might be non-obvious and beyond those of us who don't bother. Sometimes it does not include writing any code at all – or quite contrary – requires some additional code that might look as unnecessary at first glance.

Not every customer requirement has to be satisfied by writing more and more lines of code (which require more hours to maintain). That's the power of knowing well the domain in which you implement the software – quite often you can solve the problem in a different way than originally planned.

Every now and then implementing more generic mechanisms and functionalities pays off. But in many scenarios it doesn't. Sometimes it *would* pay off but you can't generalize it because you don't have enough skills and you don't even know how to do it. If *knowing the context is the king*, *knowing your craftmanship is the queen*.

## Summary

You *write the code to solve the problem*, not *just* write the code for the sake of writing the code. You judge others code from the perspective how well is solves the problem you have.

Have a nice day! 😊
