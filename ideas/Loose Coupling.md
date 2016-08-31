Title:  Loose Coupling

Index: coupling
Index: encapsulation (https://en.wikipedia.org/wiki/Encapsulation_(computer_programming))
Index: Object-Oriented Programming (https://en.wikipedia.org/wiki/Object-oriented_programming)
Index: OOP (https://en.wikipedia.org/wiki/Object-oriented_programming)
Index: Postel's Law
Index: teams

Body:

When performing [decomposition][], it is best to group elements so as to minimize coupling between groups.

Coupling can be thought of as communication between groups, or knowledge of what's going on within other groups, or dependencies of one group on another.

Note that loose coupling is desirable, whether the groups under consideration are teams of developers, or packages of data and methods.

Loose coupling tends to maximize the freedom of each group to handle its own work without consideration for what's going on in other groups.

<a href="https://en.wikipedia.org/wiki/Encapsulation_(computer_programming)" class="reflink" target="ref">Encapsulation</a> of data and internal components within objects is a notable feature of <a href="https://en.wikipedia.org/wiki/Object-oriented_programming" class="reflink" target="ref">Object-Oriented Programming</a> (OOP), and is one means by which tight coupling between objects may be avoided.

Loose coupling frequently offers a way to make internal improvements to one object or group without necessitating concomitant changes to other objects/groups that communicate with the first, thus minimizing the "ripple effects" of changes.

When decomposing the staff of developers needed on large projects, the idea of loose coupling results in the formation of relatively small, self-managed [teams][] that contain all the resources they need to work relatively independently.

<a href="https://en.wikipedia.org/wiki/Robustness_principle" class="reflink" target="ref">Postel’s Law</a> can be thought of as another means of supporting loose coupling:

> Be conservative in what you do; be liberal in what you accept from others.

This admonition, for both software interfaces and human ones, encourages us to stick to the straight and narrow in our own behavior, but be tolerant of minor quirks in others. For more on this topic, see the Pagan Tuna post, &ldquo;<a href="http://www.pagantuna.com/posts/reflections-on-postels-law.html" class="reflink" target="ref">Reflections on Postel’s Law</a>.&rdquo;


[decomposition]: decomposition.html
[teams]: build-great-teams.html
