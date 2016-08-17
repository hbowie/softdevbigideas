Title: Understand the Arc of Your Project

Index: Ambler, Scott
Index: Hitchcock, Alfred
Index: Humphrey, Watts
Index: Leffingwell, Dean
Index: Psycho
Index: SDLC
Index: Spolsky, Joel
Index: Systems Development Life Cycle
Index: arc
Index: gates
Index: hero's journey
Index: iteration 0
Index: phases
Index: scaled agile
Index: three-act structure
Index: Discover
Index: Drive to Decisions
Index: Deliver
Index: narrative fiction; novel


Body:

Software development has traditionally been thought of as proceeding through a series of phases. This is sometimes described as a <a href="https://en.wikipedia.org/wiki/Systems_development_life_cycle" target="ref">Systems Development Life Cycle</a> (SDLC), and is often managed via a series of <a href="https://en.wikipedia.org/wiki/Phase%E2%80%93gate_model" target="ref">gates</a> that control progress from one phase to another, ensuring that the work of one phase has been completed successfully before allowing work on the next phase to start.

A fairly typical list of phases might be as follows:

1. Initiation
2. Requirements
3. Design
4. Construction
5. Testing
6. Implementation
7. Maintenance

<a href="https://en.wikipedia.org/wiki/Agile_software_development" target="ref">Agile</a> approaches, on the other hand, tend to break a project down into a series of time-boxed sprints or iterations, overlapping and compressing phases 2 - 6 (Requirements through Implementation) within each iteration. If there is any acknowledgment of a larger project lifecycle, it often consists merely of an initial iteration, referred to as iteration 0, dedicated briefly to startup tasks before beginning the actual work of coding in iteration 1.

In my experience, both of these approaches tend to have problems. The SDLC approach often tries to adhere too rigidly to firm gates, and often tends towards micromanagement in its review of deliverables needed to pass through each gate, losing sight of the forest in its minute review of the trees.

Watts Humphrey noted this first problem in trying to establish a firm conclusion to the requirements phase:

<blockquote>
<p>
A common misperception is that we must start with firm requirements. There is a widespread but fallacious view that requirements are the customers&#8217; job and that development should not start until they are explicitly defined. The fact is that the demand for firm and unchanging requirements is mostly wishful thinking....</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Watts_Humphrey" target="ref">Watts Humphrey</a> from the book <cite><a href="bibliography.html#humphrey-1998">Managing the Software Process</a></cite> Copyright &copy; 1998 by Addison-Wesley Publishing Company, Inc.
</footer>
</blockquote>

The Agile approach, on the other hand, often suffers because it assumes too blithely that all problems can be worked out during development iterations, with little up-front analysis and design work. As a result, I've heard frustrated executives declare that Agile is "just a way of producing crap faster."

Unfortunately, many software development shops tend to cycle back and forth between these two approaches, favoring one or the other based on whichever one most recently yielded disappointing results. And a series of project failures based on both approaches often leaves in its wake two teams of firmly entrenched methodology advocates, endlessly battling over which of their approaches represents the truth and the light.

Models that try to get the best of both worlds are now commonly referred to as "scaled agile." Two such examples are Dean Leffingwell's <a href="http://www.scaledagileframework.com/" target="ref">Scaled Agile Framework</a> (SAFe) and Scott Ambler's <a href="http://www.disciplinedagiledelivery.com/" target="ref">Disciplined Agile Delivery</a> (DAD) model. All of these scaled agile approaches have something to offer, and can help an organization move beyond the endless Agile vs. Traditional debates. For more on this topic, see the Pagan Tuna post, &ldquo;<a href="http://www.pagantuna.com/posts/benefits-of-the-scaled-agile-framework.html" target="ref">Benefits of the Scaled Agile Framework</a>.&rdquo;

However something important often gets lost in all of these attempts to reduce the reality of software development into the artificial confines of one model or another: the overall arc of your project.

What do I mean by this phrase?

Instead of a software development project, let's think for a minute about something else that has a beginning, a middle and an end.

Let's think about a book-length work of fiction: a novel.

We can think of each chapter of a novel as comparable to an iteration in an agile development project: each chapter delivers some additional dialogue, some additional characterization, and some additional elements of the plot, just as each iteration delivers some working software. And each chapter is roughly the same length as the others, just as each development iteration is often time-boxed into a prescribed length.

However, even though most of us wouldn't consciously mark the progress of a novel from one phase into another, we all have an instinctive understanding that a book is not an unending series of chapters, that as the story unfolds, we are proceeding along a narrative arc that should eventually bring us to a satisfying conclusion. And if that arc is interrupted, or perverted -- as it was very intentionally in Hitchcock's move *Psycho*, for example -- then we feel that something is wrong, we may even be shocked, without the need to resort to a particular model of narrative fiction in order to reach that conclusion.

Now even though we don't consciously think about these narrative stages as we're reading a novel -- and even though authors don't always consciously consider them as they're writing one -- we can construct various models of how a story typically proceeds. There are, for example, the twelve stages of a <a href="http://www.thewritersjourney.com/hero's_journey.htm" target="ref">hero's journey</a>, as identified by Joseph Campbell. Or we could look at the <a href="http://www.storyboardthat.com/articles/e/five-act-structure" target="ref">five act structure</a> used explicitly in many plays. For our purposes today, though, let's just consider the simplest of these, the <a href="https://en.wikipedia.org/wiki/Three-act_structure" target="ref">three act structure</a>.

* Act I -- Used for exposition, to establish the main characters, their relationships, the worlds they live in and, finally, the problem to be solved.

* Act II -- Our hero wrestles with the problem, encountering setbacks along the way, and gradually discovers new resources to help address the central problem.

* Act III -- The problem is resolved.

Let's return now to consideration of the nature of a software development project. If we think broadly about the structure of any such project, I will submit that we can typically discern three distinct "acts," even though they will typically overlap and not be clearly delineated.

1. **Discover**: In the first phase, a project team is discovering all they can about the problem space, and about potential elements of a solution. Questions are mostly open-ended, and you are working to get the general lay of the land.

2. **Drive to Decisions**: At this point the team has developed a good sense of what is expected of them, and their interests narrow to focus on some fairly specific concerns. Typically, these involve ambiguities in the problem space, competing perspectives held by different stakeholders, or difficult design trade-offs. Resolving these issues generally requires some tough decisions to be made.

3. **Deliver**: Finally, when they get those open issues nailed down, the team knows with some precision what they need to do, and they marshal the troops to go off and deliver on the promises made to their customers.

Note that working software can be developed and delivered in all three of these acts, although the purposes of this development will be somewhat different for each, in line with the varying characterizations given above. Note also that this three-act structure may be repeated within the larger arc of a sizable project, if delivery of overall project objectives has been decomposed into a series of somewhat smaller efforts (just as it is repeated in fiction within a trilogy).

How does this three-act structure for software development help us?

First, we should note that the key mindsets necessary to succeed are very different in these three acts. If I may be allowed to use some canine analogies:

* The **Discover** act primarily requires boundless curiosity -- much the same thing my Golden Retriever exhibits when he is let off his leash in a new space. You need to run around in all directions at once, discovering and testing boundaries, sniffing anything that might be interesting.

* In the **Drive to Decisions** act, though, you need to be more focused and persistent, doing whatever it takes to resolve your significant remaining issues. In this phase you are more like a bloodhound, relentlessly following the scent of its quarry.

* In the **Deliver** act, you need to be efficient and steady in making progress towards the finish line. You have lots of stuff to do, you know what it is, and you need to go about doing it. At this point, what you need is a sheepdog, rounding up the flock and bringing them home at day's end, making sure that no straggler gets lost.

Next, we can note that many project failures are traceable back to a problem of giving too much or too little attention to one or more of these acts.

Some projects get stuck in perpetual Discovery mode, wandering around for months and even years without ever figuring out what it is they're supposed to do.

Some projects skip the Drive to Decisions phase, sweeping all the difficult decisions under the rug in the vain hope that they will somehow sort themselves out later. As Joel Spolsky has noted:

<blockquote>
<p>
In too many programming organizations, every time there&#8217;s a design debate, nobody ever manages to make a <em>decision</em>, usually for political reasons. So the programmers only work on uncontroversial stuff. As time goes on, all the hard decisions are pushed to the end. <em>These projects are the most likely to fail.</em></p>

<footer>
<a href="http://en.wikipedia.org/wiki/Joel_Spolsky" target="ref">Joel Spolsky</a> from the book <cite><a href="bibliography.html#spolsky-2004">Joel on Software</a></cite> Copyright &copy; 2004 by Joel Spolsky
</footer>
</blockquote>

And then there are the projects that try to go straight to the Deliver act in a misguided effort to complete faster.

Once you begin to develop a sense of what these three acts look like, and how they work, then it becomes easier to detect and correct project narratives that are deviating from what is likely to be a successful arc. (Although it should perhaps be noted that it may be easier for an [English major][hb] to apply this wisdom than it is for someone trained in traditional project management disciplines.)

One document that can help a project navigate through these three acts successfully is a list of questions or open issues. I'm not talking about issues in a project management sense, since these are typically viewed as things that are threatening the normal progression of the project. I'm just talking about the normal list of questions that typically arise during any development project. This is typically a document that would be used by a development team or an analyst or an architect or a team lead, not by a project manager, and would not be managed with any degree of formality or management oversight.

And I'm not suggesting that this list need replace any of a project's other documents; often the answers to all these questions will ultimately get recorded in other documents that may be of a more permanent nature.

Here is how such a list would be used in each of these three acts.

* **Discover**: At the beginning of this act, you won't yet know enough to even formulate such a list, but should have the goal of being able to start such a list. By the end of this act, you should have a fairly comprehensive and specific list of open questions that need answers.

* **Drive to Decisions**: As you try to answer the questions you have listed, you will come up with some answers, as well as some further questions. Record the answers (which can also be characterized as decisions that have been made), as well as the additional questions, and move the answered questions down into a lower section of the list. In some cases, developing some quick software prototypes to show your customers may be the best way to get solid answers to some of your questions. You may also want to make note of the reasons for particular decisions. When you've got a long list of answered questions, and only minor issues left to be resolved, and the pace of adding additional questions has slowed or stopped, you're at the end of Act II.

* **Deliver**: Now start or continue the steady delivery of working software, based on the answers you've come up with. As additional questions arise, don't panic or try to sweep them under the rug, just continue to add them to the list and get answers to them. Similarly, if the answers to some questions change, just make sure everyone is in agreement with the new answer, record it, and proceed to deliver.

If we focus on the details of a project, then we will often see subplots, red herrings, surprises, suspense and mystery, just as we do in any good novel. After all, any software development project is fundamentally a journey of discovery: our intent is always to discover the big things early on, and have fewer and smaller surprises as we continue, but any omniscience we can claim is only in hindsight. If we're trying to track progress according to a traditional project plan, then the project may appear to be in a state of chaos.

If we step back and look at the overall arc of the project, though, proceeding through the three acts of *Discover*, *Drive to Decisions*, and *Deliver*, then we can often get a much better sense of whether a project is fundamentally on track or headed off the road and into the weeds. And a list of open questions, paired with a list of closed questions and their answers, can help key leaders navigate the roiling waters of any challenging project, ultimately leading their teams and stakeholders to a successful conclusion.

[hb]: about-the-author.html

