Title: Plan-Do-Check-Act

Index: design thinking
Index: experiment
Index: PDCA
Index: plan-do-check-act
Index: scientific method (https://en.wikipedia.org/wiki/Scientific_method)
Index: Von Braun, Wernher
Index: waterfall

Body:

How do we learn what works?

One way is to [use things already proven to work][reuse].

But most significant development efforts will also involve some innovation. And when we try new things, they may not always work as well as we first thought they might.

One proven approach to learn what works is known as the <a href="https://en.wikipedia.org/wiki/PDCA" target="ref">Plan-Do-Check-Act</a> cycle, often abbreviated as PDCA.

It goes like this:

1. **Plan** to do something (develop features, reduce defects, etc.) The plan should involve a goal, as well as a means of achieving that goal.
2. **Do** the thing you planned.
3. **Check** the results. Did you meet your goal? Did your plan work as expected?
4. Take **Act**ion, as needed, to accept your results into a new baseline, or to propose modifications to be input into the next Plan-Do-Check-Act (aka PDCA) cycle.

Note that the PDCA cycle can be used on elements of a product design, but also on attempts to improve development processes. The same basic cycle applies equally well to both.

The PDCA cycle can also be thought of as a compressed version of the <a href="https://en.wikipedia.org/wiki/Scientific_method" target="ref">Scientific Method</a>, as indicated in the following table.

<table class="table table-bordered table-condensed table-dense">
	<thead>
	<tr>
		<th>PDCA Step</th>
		<th>Equivalent Scientific Method Step(s)</th>
		<th>Other Terms</th>
		<th>Example</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<th rowspan="4">Plan</td>
		<td>Ask a Question</td>
		<td>&nbsp;</td>
		<td>How can our users best navigate through our new web app?
	</tr>
	<tr>
		<td>Conduct Background Research</td>
		<td>See what others have done in similar circumstances</td>
		<td>Review other successful web apps to see what they have done</td>
	</tr>
	<tr>
		<td>Formulate a Hypothesis</td>
		<td>Propose a Design</td>
		<td>A Main Menu with one level of drop-downs</td>
	</tr>
	<tr>
		<td>Design an Experiment</td>
		<td>Construct a Test to validate or disprove the hypothesis</td>
		<td>Let's perform a usability test and ask the users to perform these five key tasks</td>
	</tr>
	<tr>
		<th>Do</td>
		<td>Perform an Experiment</td>
		<td>Test</td>
		<td>Create a working prototype and conduct the usability test</td>
	</tr>
	<tr>
		<th>Check</td>
		<td>Analysis</td>
		<td>Analyze results and draw conclusions</td>
		<td>Overall approach worked but users struggled to find one particular function</td>
	</tr>
	<tr>
		<th>Act</th>
		<td>Determine Next Steps</td>
		<td>Ask further related questions, or modify the hypothesis and perform further experiments</td>
		<td>Either modify the prototype and re-test, or incorporate modified design into final product and proceed</td>
	</tr>
	</tbody>
</table>

Note that the typical waterfall cycle of requirements-design-code-test is not a healthy adaptation of the PDCA cycle, because all testing is generally left to the end, without any provision to Act on the learnings gained from the tests. This is one reason why projects organized like this tend to finish late or fail altogether.

Note also that simply trying the first thing that pops into your head, and then proceeding with it if it's not an immediate disaster, is not an example of plan-do-check-act.

Let's review some important success factors for each step of this cycle.

## Plan

You must decide where you are using tried and true elements, and where you want to innovate.

For each significant innovation, you will want to use some form of this PDCA process.

For each area of innovation, you must allow enough time to conduct one or more experiments, and learn from each, and this must happen early enough to allow the learnings to be incorporated into the rest of the project.

Note that this step requires the project leaders to admit that they don't already know everything, and further note that many organizational environments view such an admission as a sign of weakness or inadequacy, and thus discourage this process from ever getting started.

As part of the plan step, it is important to formulate a testable hypothesis that can be proven or disproven.

Note that the plan-do-check-act cycle can be used to evaluate [alternatives][].

## Do

You must test in such a way that you can clearly see how well your plan is working.

As <a href="http://en.wikipedia.org/wiki/Wernher_Von_Braun" target="ref">Wernher Von Braun</a>, famed rocket scientist, once said:

> One test result is worth one thousand expert opinions.

## Check

Did you achieve the results you were hoping for? Be honest about what worked and what didn't.

## Act

If a test was successful, then you can incorporate the planned approach into your effort and proceed forward.

If a test was unsuccessful, then you will need to go back to the drawing board, and try again. Or you may decide to abandon this particular line of planned innovation, and fall back on something already known to work.

If you've conducted multiple tests in parallel (as in a Design Thinking exercise), then you may wish to combine the elements from multiple prototypes into a new hybrid design that tries to incorporate the best elements of multiple alternatives.

[alternatives]: consider-alternatives.html

[reuse]: use-things-already-known-to-work.html





