Title: The Inconvenient Nature of Software Development

Software development is often viewed from two completely different mindsets. 

Let's consider first what we might call the Predictive Planning Model. 

### The Predictive Planning Model

1. Software development is best managed as a set of projects, with each project starting and ending at specific points in time.  

2. There exists a finite set of requirements for any software development project.

3. That finite set of requirements is discoverable within some reasonable period of time.

4. That set of requirements can be accurately documented and validated before any working software is produced or executed. 

5. Requirements are most usefully considered in a pure state, untainted by any traces of design. 

6. The clearest way to communicate requirements is through written documents containing some combination of text and diagrams.

7. Requirements can be reliably validated through careful review of this documentation.

8. Customers can be relied upon to accurately identify the relative priorities of their requirements.

9. It is possible to define a repeatable process for requirements discovery, based on the principles above.

10. The goal of design is to satisfy all the requirements.

11. It is very expensive and risky to change software once it is coded and working, so it is critical to get the requirements and the design right before coding is allowed to begin. 

12. At some point in the project early enough to be useful for purposes of planning and governance, the amounts of time and effort that will be required to complete the project can be accurately estimated. 

13. As with other engineering disciplines, software engineering is based on a stable foundation of immutable laws. 

14. It is possible to accurately gauge the overall progress of a project by collating and summarizing progress data from project team members. 

15. Projects based on these principles will tend to produce satisfied customers.

These principles sound reasonable, don't they? What's more, they cohere nicely, coming together to form a picture of software development that seems pleasingly rational and predictable. 

Wouldn't it be nice if they were actually true? 

However, many view software development from a completely different mindset. 

Let's call this one the Adaptive Model. 

### The Adaptive Model

1. Useful software products evolve rapidly and more or less continuously, so defining a "project" as a series of development activities with definite start and end dates is typically somewhat arbitrary, and often misleading. 

2. Software requirements are a matter of opinion, and are therefore subjective, largely unbounded, always incomplete, and open to perpetual redefinition and reinterpretation. 

3. Requirements documents for software development efforts of any significant size are generally difficult to understand and interpret consistently, and so offer an entirely misleading sense of control over the software coding activities to follow.

4. The supposed boundaries between requirements, design and coding are entirely porous, with all three "phases" of development interacting with and influencing the others.

5. Prioritizing requirements is generally difficult, since every requirement is important to someone, and no one wants to call another's child ugly. 

6. The cost of making software changes has consistently declined, due to the increasing power and sophistication of the languages and tools available to modern developers. And so writing software and then changing it based on reactions from stakeholders is often more efficient than going through elaborate and unreliable paper-based rituals prior to coding. 

7. Any software development effort is either a journey of discovery, or a waste of resources. Either you are creating something new, or you are recreating something that's already been done. If you are creating something new, then you had best be honest that you aren't entirely sure what you're doing, or how long it will take, until you've done it. If you're entirely sure of what you're going to do and when you're going to do it, then you're not developing something, you're just putting a fresh coat of paint on something that already existed. 

8. All software applications are built on top of hardware and software platforms that are themselves highly complex and still rapidly evolving. There are no limitations. There are no hard and fast rules. Everything is malleable, and everything is possible. In this sort of environment, it is folly to try to define some sort of repeatable and stable engineering discipline. 

9. The demonstration of working software is the only reliable indicator of progress in any sort of software development activity. All other avowals of project progress are illusory. 

10. Customers are happiest when the software is adaptive and evolving quickly in response to their explicit and implicit wants and needs. 

Quite a different perspective, isn't it?

### Reality

The Predictive Planning Model is the one usually favored by leadership, because it portrays the actual act of writing software as a more or less trivial activity that can be easily and effectively managed from on high. 

The Adaptive Model, on the other hand, is the one usually favored by developers, because it generally takes those annoying managers out of the picture and allows the developers to do what they do best without any pesky cost or schedule constraints. 

So which of these is true? 

Well, the inconvenient truth is that they both are, to varying degrees. 

As I'll argue shortly, [Software Development is a Balancing Act][balance].  

Although it would be nice to believe that the Predictive Planning Model can be made to work, and although it has worked, for some, to some degree, under very special conditions, it cannot be really said to be true in general. Like Newtonian physics, it can sometimes give us a useful approximation of reality, but we will get ourselves in trouble if we rely on it to be absolutely valid under all conditions. 

The Adaptive Model is generally much more realistic, until we run up against the problems of limited time, money and resources, because no organization that I've ever seen can really live with a development team that is constantly adapting to emergent conditions without being willing to give some reasonably reliable predictions of when it will be done meeting some important goal, and at what cost. 

So where does that leave us? 

If we are now left with the uncomfortable feeling that we have two different models, both of which can be helpful at times, but neither of which can be absolutely relied upon, then we are probably in the right place to begin thoughtful and appreciative consideration of Software Development's other Big Ideas. 

----

<blockquote>
<p>
...you said you think you know some things. What you mean is, you&#8217;ve constructed simplified representations of how those things work. But don&#8217;t confuse yourself by thinking your simplified mental constructions are realistic, or worse yet, true ... Nothing useful is real. If it&#8217;s complicated enough to be realistic, it&#8217;s too complicated to be useful. That&#8217;s why we build models. Representations. When we say we know things, we just mean we have mental models of those things that we like. Often we like them because they&#8217;ve been useful. But let&#8217;s not confuse having a useful model with actual knowing. </p>

<p>
Managers have a problem ... when they fall in love with a particular model of how something works. When they become convinced that a mental model they have of how something works is the right one. When they decide that they know something. ... when we become too wedded to a model, we lose our ability to deal with new situations.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Robert_D._Austin"  target="ref">Robert D. Austin</a>, <a href="http://en.wikipedia.org/wiki/Richard_L._Nolan"  target="ref">Richard L. Nolan</a> and <a href="http://en.wikipedia.org/wiki/Shannon_O'Donnell"  target="ref">Shannon O'Donnell</a> from the book <cite><a href="bibliography.html#austin-et-al-2009">Adventures of an IT Leader</a></cite> Copyright &copy; 2009
</footer>
</blockquote>



[balance]: software-development-is-a-balancing-act.html
