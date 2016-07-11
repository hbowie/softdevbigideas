Title:  Cohesion

Tags:   1) Fundamental

Body:

When performing decomposition, elements that are closely related to each other should be grouped together.

The relationships may be based on functional similarities, communication paths between elements, and/or interdependencies.

One test of cohesion is whether the function of a group can be easily described and understood, and whether the elements in that group can be seen to readily fit within that stated function.

Be careful, though, not to group elements together based on a shared or similar role, if each element is tasked to perform that role for different groups.

In other words, and in the case of development teams, you would not normally maximize cohesion by assigning each database analyst to a group of other database analysts, since the primary communication for each would be with the developers they are supporting, and not with other DBAs.

Instead, groups of individuals performing similar roles on different teams can best communicate with each other as members of a Community of Practice. Such a group may also be referred to as a guild.

Note that the value of cohesion starts with the product design itself.

[Fred Brooks][fred] stated it this way in his book <cite>[The Mythical Man-Month][brooks-1975]</cite>, first published in 1975:

> I will contend that conceptual integrity is *the* most important consideration in system design. It is better to have a system omit certain anomalous features and improvements, but to reflect one set of design ideas, than to have one that contains many good but independent and uncoordinated ideas.

[Steve Jobs][steve] used very different words to make much the same point in 2000, in an [interview with <cite>Fortune</cite> magazine][jobs-2000]:

> Design is not just what it looks like and feels like. Design is how it works. Design is the fundamental soul of a human-made creation that ends up expressing itself in successive outer layers of the product or service.

[steve]: http://en.wikipedia.org/wiki/Steve_Jobs

[fred]: http://en.wikipedia.org/wiki/Fred_Brooks
[brooks-1975]: bibliography.html#brooks-1975
[jobs-2000]: bibliography.html#jobs-2000
