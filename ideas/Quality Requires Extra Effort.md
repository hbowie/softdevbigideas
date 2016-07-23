Title:  Quality Requires Extra Effort

Most software developers enjoy programming. And most software developers enjoy pleasing their customers. This means that, left to their own devices, developers will tend to focus on quickly delivering new features to their customers.

The problem here is that some attributes of high-quality software are not immediately visible to customers. And so, left to their own devices, many developers will tend to give short shrift to these quality factors.

Many of these quality attributes are often collectively referred to as the "-ilities". Following is a list of some of these attributes:

* Maintainability
* Recoverability
* Scalability
* Security
* Survivability
* Usability
* Graceful Failures

Since developers often have little natural motivation to focus on these attributes, a project must generally exert some extra effort to ensure adequate levels of quality.

Such extra effort could include any or all of the following:

* definition and implementation of [non-functional requirements][nfr] (NFRs)
* peer reviews
* pair programming
* coding standards
* architecture reviews
* code analysis tools
* automated tests
* performance and scalability testing
* dedicated testers
* defect metrics

Establishing the right sort of quality program for a project is a matter of judgment, though. There is no single set of quality practices that will be right for every project. What's right for one effort might be overkill for another.

Be careful as well to make sure that the practices you choose are actually effective. None of these practices should simply be implemented on faith, or because someone outside of the project says you should do them.

You will probably need to assign someone the responsibility of [ensuring that these quality practices are not neglected][wrong].

----

<blockquote>
<p>
Fact 37: Rigorous inspections can remove up to 90% of errors from a software product before the first test case is run.</p>

<footer>
<a href="http://en.wikipedia.org/wiki/Robert_L._Glass">Robert L. Glass</a> from the book <cite><a href="bibliography.html#glass-2003">Facts and Fallacies of Software Engineering</a></cite> Copyright &copy; 2003 by Pearson Education, Inc
</footer>
</blockquote>

----

<blockquote>
<p>
&#8220;You get what you design for. Chester, your peer in Development, is spending all his cycles on features, instead of stability, security, scalability, manageability, operability, continuity, and all those other beautiful &#8216;itties.&#8221; </p>

<footer>
<a href="http://en.wikipedia.org/wiki/Gene_Kim">Gene Kim</a>, <a href="http://en.wikipedia.org/wiki/Kevin_Behr">Kevin Behr</a> and <a href="http://en.wikipedia.org/wiki/George_Spafford">George Spafford</a> from the book <cite><a href="bibliography.html#kim-et-al-2013">The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win</a></cite> (2013)
</footer>
</blockquote>

[nfr]: https://en.wikipedia.org/wiki/Non-functional_requirement
[wrong]: consider-what-might-go-wrong.html



