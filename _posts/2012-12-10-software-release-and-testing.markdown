---
layout: post
title: Testing Should Not Stop a Release. Ever.
---

{{ page.title }}
================

<p class="meta">12 Dec 2012 - Leeds, UK</p>

I am, for all the bells and whistles, a tester but my role is not to find defects or to ensure quality in software. Those would be un-quantifiable goals whose relationship with real business value is intangible. What I do is analyse systems, software and processes to produce information that makes a case supporting or undermining the value of a release.

That does not mean I stop releases or slow down the rate of iteration or introduce hoops for development teams to jump through. Testing should never stop a release. Only the business can stop a release. The only sensible criteria to do that is how much money the release will make the business or save the business.

If there is a one week window to produce something that captures a fleeting market then two things are true of the best test process. First it can and should be tested. Second the tests should aim to make sure it hits the target market and that serious exploits are reported quickly and clearly. That is it.

On the other hand if you're producing a pacemaker even though the task is computationally simple the testing should be fine grained and have a significant assurance process. I would encourage comprehensive unit testing and long phases of functional investigation. 

Fundamentally some systems, especially back of house systems, are not high value enough to warrant imposing a test process on just like some software isn’t worth writing. One of the most important pieces of information to have is how much, as a ballpark, does this cost to test to the right level so that the business gets the information it needs about releasing the software. If you do not have that number how can you embark on testing and how can you know when you are ‘done’?
