Arrow's paper [The Economic Implications of Learning by Doing](https://doi.org/10.2307/2295952) begins with a contrast to invention.

One example of invention is LED lighting.
Ravers with LEDs of course look futuristic, but now that LED lighting is widespread, the whole world looks a little different, and old indoor photos look old just because of the quality of the light.

LED lighting required a new material: gallium nitride for the blue LED.
My postdoc work was in materials discovery, and blue LEDs and lithium-ion batteries were aspirational examples.
Solar power, though, was an uncomfortable reminder of how much technological progress had nothing to do with academics like us working on exciting new materials in the lab.
After all these years, and all these exciting new solar cell materials demonstrated in academic labs, the solar boom was happening with silicon.
(Except for America's only major solar manufacturer, First Solar; they use cadmium telluride.)

I first saw a graph like this at a conference:

On the y axis is log price, and on the x axis is log cumulative production, that is, how many solar panels have ever been made, measured in watts.
This is called an instance of "Wright's Law".
I saw my first Wright's Law plot of solar power at a conference, but soon enough saw them everywhere online; [this one is from OWID](https://ourworldindata.org/learning-curve).
People call this a "learning curve" or an "experience curve", although on a log-log plot the point is it doesn't curve, it's a straight line.

Why plot against cumulative production, rather than against time?
Moore's Law is the observation that transistor density doubles every two years.
[You plot it](https://ourworldindata.org/moores-law) with time on the x axis, and on the y axis, transistor density on a logarithmic scale.
Speaking roughly, both graphs are plotting some measure of efficiency on the y axis, but Moore's law uses time as the x axis, whereas Wright's Law uses cumulative production.

Wright's law originates in a 1936 paper called [Factors Affecting the Cost of Airplanes](https://pdodds.w3.uvm.edu/research/papers/others/1936/wright1936a.pdf), by a Wright of no relation to the Wright brothers.
He made the log-log plot of price vs cumulative production, and drew a line, the first instance of Wright's law:

Critically, Wright talking about improvements within a single factory, and saw decreases specifically in labor cost.
Speculating as to the reasons, he discusses the workers getting better at what they do, and mentions time-and-motion studies.
He also mentions better tools, both because make work more efficient and because you can decrease labor costs by hiring less skilled workers.

The solar Wright's law graph, spanning multiple decades, is presumably reflecting something different.
The old factories are gone, the new ones have different people and equipment.
Arrow's Learning by Doing paper presented a model where all improvements to manufacturing efficiency are due to new equipment.
He evocatively describes the efficiency of a machine as a function of its serial number.
This makes it hard to distinguish between "learning by doing" and invention, since improved equipment embodies inventions.
For example, even though we're still using silicon, there has been a succession of technologies for slicing the crystal into wafers.

In Arrow's model, progress doesn't come from time passing, or from routine production, but from investments in new capital.
We could formulate an "Arrow's law": an increase in efficiency as a function of capital investment.

When does Wright's Law differ from a Moore's Law extrapolation in time?
When demand is unreliable, so there's years of low production, or at least stagnant growth in production.
If Wright's Law truly holds, then this will look like falling behind Moore's Law.

When does Arrow's Law differ from a Wright's Law extrapolation in cumulative production?
When investment is unreliable.
Years where people are still buying, but it is not possible to finance new equipment.

There's [a paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0052669) that says Wright's Law-style extrapolations are somewhat better than Moore's Law extrapolations, but not by much.
I couldn't tell you whether a hypothetical Arrow's Law extrapolation is better.
I don't know who collects data measuring total cumulative investment in production of a specific product.

The real trick to all of these extrapolations, I think, is that huge errors look small on a log scale.
Even if you're totally mislead by the predictions year by year, they'll still look great looking back over the decades when the deviations have all averaged out.
