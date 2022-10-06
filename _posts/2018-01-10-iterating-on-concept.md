---
date: 2018-01-10
published: true
tags: ["programming", "work"]
title: Iterating on Concept vs Iterating on Code
summary: Is delivering value early always the best way of developing software?
---

Is delivering value early always the best way of developing software? I'm pretty sure you've seen this picture:

{% include figure.html url="/assets/iterating-on-concept/iterating-on-concept.png" %}

It's usually mentioned in the context of discussing Agile vs Waterfall to make an argument that we should iteratively build a product that solves some business needs from some early days rather than create a software that won't render any value unless fully finished. But is it always the case?

Did you spot in your company people thinking:

> Let's do a skateboard to make customer somewhat happy, phase 1, and we'll think later.

without making an argument:

> Is spending time on designing and implementing skateboard... then scooter... then bicycle... then bike... really the fastest way to build a car?

?

## What's the problem?

I did. I've seen couple of times a temptation of focusing on intermediate, easy checkpoint while porposely avoiding thinking about the end goal.

Sometimes eagerness of delivering something working makes us forget that the overall process of making rollerskate -> scooter -> bicycle -> bike -> car will take more resources than doing just a car at the beginning. It's simply more work to build all of those things in-between. And business people may think like:

> "- ok, let's build rollerskate, it's simple"

> "- now, add handlebar, it's simple"

> ...

> "- now we have bike, it looks like we need to add two more wheels and that will be a car!"

In general, iterative approach is very tempting. It's because:

  - It's much easier for people who define the requirements.
  - Developers generally like jumping into code sooner than later.
  - It's motivating for everyone to see *some* tangible, working things early.

## Iterating on concept vs iterating on code

Iterating on code goes like this:
1. Design feature
2. Implement feature
3. Feedback loop
4. (go to point 1)

Iterating on concept goes like that:
1. Design feature
2. Prototype
3. Feedback loop
4. (go to point 1)
5. Implement final version of the feature

Obviously, latter approach is faster. You can iterate faster if you take coding out of the loop when prototyping a new feature/product.

Yes, there are cases that it's not possible. There are cases when you need to iterate on code. There are cases that you will build rollerskate, then scooter, bicycle, bike to end up building a car. Sometimes it's the only way to discover what to do next. But it's not always the case. In many, many situations you should hold your horses. Don't jump straight into development but stay longer in design and prototyping phases. Don't be lazy. Iterate on concept whenever possible. 



