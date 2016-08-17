Title: Use Things Already Known to Work

Index: design patterns (https://en.wikipedia.org/wiki/Software_design_pattern)
Index: Don't Repeat Yourself (https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
Index: DRY (https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
Index: Kovitz, Benjamin
Index: reuse

Body:

In other words, don't reinvent the wheel.

This can also be thought of as reuse, or as part of the principle "Don't Repeat Yourself" (DRY). But there are a number of different ways to state this.

1. Don't spend good money creating something new when something sufficiently similar already exists.

2. Make use of patterns, algorithms, operating systems, APIs, services, database management systems, high-level languages, application frameworks, existing libraries and other building blocks that will help you focus on adding something new to the world, rather than simply recreating something that already exists.

3. If you find yourself or your team doing repetitive work, then try to encapsulate the repeated actions into a module, class, framework or subroutine that can be used when needed, rather than simply doing the same mindless coding again.

Use of things already known to work is a great way to increase both productivity and quality.

Note that this idea can be applied at any phase within a project.

At the governance stage, this idea can be applied by using existing software rather than developing something new, including the idea of buying software rather than building new software.

At the design stage, this idea can be applied by making use of existing application frameworks, component packages and <a href="https://en.wikipedia.org/wiki/Software_design_pattern" target="ref">design patterns</a>, rather than having development teams "roll their own" solutions.

And at the execution stage, this idea can be applied by ensuring that data or logic needed in more than one place is created once by one team and made available as a reusable class, module, function or configuration file to others.

It's worth noting that developers tend to underestimate the effort that can be saved by using something already available and proven, often preferring to write something themselves instead. But while it may take little time to write something new, testing and debugging that new thing can consume much greater amounts of time, cause nagging quality problems, and delay schedules when bugs suddenly pop up at the worst possible moment.

As with [quality][], it often requires some forethought and extra effort to induce developers to apply this idea, since the natural rewards for developing new user-requested features are often more immediate and more satisfying than the rewards for selecting or creating or incorporating reusable resources.

----

<blockquote>
<p>
Just as possessing a rich vocabulary of words enables you to write well, possessing a rich vocabulary of design patterns enables you to design well.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Benjamin_L._Kovitz"  target="ref">Benjamin L. Kovitz</a> from the book <cite><a href="bibliography.html#kovitz-1999">Practical Software Requirements: A Manual of Content and Style</a></cite> Copyright &copy; 1999 by Manning Publications Co.
</footer>
</blockquote>

----

<blockquote>
<p>
The following is an exhaustive list of <em>all</em> problem-solving techniques, arranged in order of decreasing effectiveness: </p>

<ol>
<li>Already knowing the solution; </li>

<li>Already knowing the solution to a similar problem; </li>

<li>All other techniques. </li>
</ol>

<p>
The third &#8212; enormous &#8212; category lumps functional decomposition together with whacks on the side of the head, thinking outside the box, and all the others because, compared to the first two techniques, they are nearly worthless.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Benjamin_L._Kovitz"  target="ref">Benjamin L. Kovitz</a> from the book <cite><a href="bibliography.html#kovitz-1999">Practical Software Requirements: A Manual of Content and Style</a></cite> Copyright &copy; 1999 by Manning Publications Co.
</footer>
</blockquote>

[quality]: quality-requires-extra-effort.html

