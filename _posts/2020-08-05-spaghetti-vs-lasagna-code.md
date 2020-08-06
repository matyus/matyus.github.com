---
layout: default
tags: abstraction indirection lasagna spaghetti
---

> And I think an even more dangerous cost is the extra indirection an abstraction can create. So what I mean by that is that the promise was that I would just be able to focus on this specific layer in my code and not actually care about all the layers. Is that really what happens? I'm sure most of you probably had this bug where you started one layer, oh, it goes here. And it's like, well, actually, no. You need to understand this layer and this other layer because the bug, it goes across all of those layers. And we have a very limited stack in our heads.
>
> And so what happens is you just get a stack overflow, which is probably why the site was coded that way. And so what I see happen a lot is that we try so hard to avoid the spaghetti code that we create this lasagna code where there are so many layers that you don't know what's going on anymore at all. So that's extra indirection. And all of them wouldn't be that bad if they didn't entrench themselves.[^abramov]


[^abramov]: Abramov, 2019, p.?
