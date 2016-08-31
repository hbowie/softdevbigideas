Title: Decomposition

Index: Davis, Alan M.
Index: decomposition
Index: epic (http://www.scaledagileframework.com/epic/)
Index: feature (https://www.symphonious.net/2006/05/18/features-vs-stories/)
Index: MVC (https://en.wikipedia.org/wiki/Model–view–controller)
Index: planning
Index: user story (https://www.mountaingoatsoftware.com/agile/user-stories)
Index: WBS (https://en.wikipedia.org/wiki/Work_breakdown_structure)
Index: work breakdown structure (https://en.wikipedia.org/wiki/Work_breakdown_structure)
Index: Wright Brothers

Body:

Large and complex things should be broken down into smaller, more manageable things. This can be done progressively, and recursively, at multiple levels.

It's best if the number of things in each group is somewhere in the range of 3 - 15, with 7 being a sweet spot. The human brain seems fairly good at dealing with sets of this size.

This idea can be applied to system functionality, to software architectures, to work statements (where it results in a <a href="https://en.wikipedia.org/wiki/Work_breakdown_structure" class="reflink" target="ref">work breakdown structure</a>), and to project staffing.

Decomposition is particularly powerful when done in conjunction with [Cohesion][] and [Loose Coupling][loose].

One famous example of decomposition was performed by the <a href="http://www.nytimes.com/2003/12/09/news/earliest-days-takeoff-how-the-wright-brothers-did-what-no-one-else-could.html?pagewanted=all" class="reflink" target="ref">Wright Brothers</a> when they broke down the problem of human flight into three separate domains: lift, control and propulsion.

Another common example of decomposition in modern web applications is evident in the popular <a href="https://en.wikipedia.org/wiki/Model–view–controller" class="reflink" target="ref">MVC</a> pattern, in which application logic is subdivided into three separate areas: model, view and controller.

In Agile, it is common to have three levels of requirements decomposition, starting with <a href="http://www.scaledagileframework.com/epic/" class="reflink" target="ref">epics</a>, proceeding to <a href="https://www.symphonious.net/2006/05/18/features-vs-stories/" class="reflink" target="ref">features</a>, and then to <a href="https://www.mountaingoatsoftware.com/agile/user-stories" class="reflink" target="ref">user stories</a>.

Note, however, that detailed decomposition of requirements need not be done initially, and can often be profitably deferred until a feature is a high enough priority to be approaching scheduled implementation into code.

----

<blockquote>
<p>
The bulleted list of requirements is by far the most cost-effective and beneficial approach. It is simple to create; it is simple to read, regardless of background; and, when stored in a spreadsheet, database, or requirements management tool and augmented with annotations, it has incredible benefits to project management.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Alan_M._Davis" class="reflink" target="ref">Alan M. Davis</a> from the book <cite><a href="bibliography.html#davis-2005">Just Enough Requirements Management: Where Software Development Meets Marketing</a></cite> Copyright &copy; 2005 by Alan M. Davis
</footer>
</blockquote>

[cohesion]: cohesion.html
[loose]: loose-coupling.html

