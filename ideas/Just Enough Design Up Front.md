Title: Just Enough Design Up Front

When considering the question of how much design should be completed before coding starts, there are several factors to consider.

1. Design changes are generally harder and more expensive to make after software code has been written.

2. Architects and designers are sometimes better qualified to perform design than other team members, and it is easier to confine design tasks to these few individuals before more developers get involved.

3. The wisdom of a design can only be fully validated once it is implemented in working software.

4. Work done later in the effort can draw upon the skills, experience and wisdom available from the larger team.

5. The team will learn more about the problem space as the work progresses, and so deferred design decisions can take advantage of these greater learnings.

6. Early design decisions often turn out to have been based on mistaken assumptions, or on evolving business conditions that then change before the software is ready for delivery and use.

7. When design is done early, there is a tendency to provision for features that later turn out to be unneeded. This is one reason why agile practitioners try to follow the "[YAGNI][]" dictum: until proven otherwise, assume that "You Ain't Gonna Need It".

8. Developers will be more fully engaged in the work if they are focused on the overall purpose of the effort, and are allowed sufficient autonomy to make some design decisions as they work.

If we consider only the first two factors, then we will do all of our design work using models and documents before writing a single line of code. This is sometimes referred to as Big Design Up Front (BDUF).

If we consider only the last six factors, then we may be tempted to only do design as we code, without any up-front design. This is often referred to as "cowboy development," since we are always shooting from the hip, without ever stopping to take careful aim at our target.

When we take all of these considerations into account, though, we generally find it best to do some early design work, but allow the full design to emerge as the work progresses.

This is why it is usually best to practice JEDUF: Just Enough Design Up Front.

The advantages of such an approach are not confined to software development.

Here is an example of how Frank Gehry and his team designed and built the Peter B. Lewis Building at Case Western Reserve University, as described in <cite>[A Perfect Mess: The Hidden Benefits of Disorder][abrahamson-freeman-2006]</cite>, by Abrahamson and Freeman:.

> The school approved the design and brought in a small army of contractors to build it. The contractors duly admired, in a shocked and fretful way, the model of the God-awfully complex structure they were about to undertake, and then asked for the blueprints, to which Gehry's team replied that there weren't any.
>
> To capture the building's emotional content, Gehry maintains, everyone working on the building should keep creating throughout the construction process.
>
> Freed from the constraints of a blueprint's rigid specifications… the contractors and architects were able to collaboratively rethink the design and construction techniques in any way necessary to achieve the project's goals. That led to an eruption of innovation.
>
> Not only was the finished building a stunning hit, completed on time and within budget, but most of the contractors were so pleased with the invention into which they had been pushed that they ended up changing the way they do business.

----

<blockquote>
<p>
We need to adopt the attitude that the internal structure of a system will require continuous improvement as the system evolves. Refactoring &#8212; improving the design as the system develops &#8212; is not just for commercial software. Without continuous improvement, any software system will suffer. Internal structures will become calcified and fragile. In a surprisingly short time, the system will cease to be useful.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Mary_Poppendieck">Mary Poppendieck</a> and <a href="http://en.wikipedia.org/wiki/Tom_Poppendieck">Tom Poppendieck</a> from the book <cite><a href="bibliography.html#poppendieck-2003">Lean Software Development: An Agile Toolkit</a></cite>
</footer>
</blockquote>

----

<blockquote>
<p>
Prototypes and prototyping are not substitutes for analysis and design, not excuses for sloppy thinking.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Larry_Constantine">Larry Constantine</a> and <a href="http://en.wikipedia.org/wiki/Lucy_Lockwood">Lucy Lockwood</a> from the book <cite><a href="http://www.amazon.com/exec/obidos/ASIN/0201924781/pagantuna-20">Software for Use: A Practical Guide to the Models and Methods of Usage-Centered Design</a></cite> Copyright &copy; 1999 by the ACM Press
</footer>
</blockquote>

----

<blockquote>
<p>
The final goal of any engineering activity is some type of documentation. When a design effort is complete, the design documentation is turned over to the manufacturing team. This is a completely different group with completely different skills from the design team. If the design documents truly represent a complete design, the manufacturing team can proceed to build the product. In fact, they can proceed to build lots of the product, all without any further intervention of the designers. After reviewing the software development life cycle as I understood it, I concluded that the only software documentation that actually seems to satisfy the criteria of an engineering design is the source code listings.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Jack_W._Reeves">Jack W. Reeves</a> from the essay <cite><a href="bibliography.html#reeves-1992">Code as Design</a></cite>, &#8221;What is Software Design?&#8221; Copyright &copy; Fall 1992 by Jack W. Reeves
</footer>
</blockquote>




[yagni]: https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it

[abrahamson-freeman-2006]: bibliography.html#abrahamson-freeman-2006
