Economists studying technological progress contrast invention to learning by doing.
Invention is doing something new, whereas learning by doing is doing the same thing over and over.

One example of invention is LED lighting.
Ravers with LEDs of course look futuristic, but now that LED lighting is widespread, the whole world looks a little different, and old indoor photos look old just because of the quality of the light.
It was not an incremental improvement but a total trend break when we replaced our incandescent bulbs with LED bulbs that draw a tenth of the power.

LED lighting required a new material: gallium nitride, to emit blue light, which can be converted to the white light needed for lighting.
My postdoc work was in materials discovery, and blue LEDs and lithium-ion batteries were aspirational examples.
Solar power, though, was an uncomfortable reminder of how much technological progress had nothing to do with us.
The solar boom was not because of academics working on exciting alternatives to silicon in the lab, but decades of accumulated progress in manufacturing with silicon.
(The exception is America's only major solar cell manufacturer, First Solar; they use cadmium telluride.)

I first saw a graph like this at a conference:

![](https://res.cloudinary.com/lesswrong-2-0/image/upload/v1794897603/lexical_client_uploads/pu8ncrl9doxgyco0iahy.png)

On the y axis is log price, and on the x axis is log cumulative production: that is, how many solar panels have ever been made, measured in watts.
When we see a line on a graph like this, we call it an instance of "Wright's Law".
Soon enough I saw these graphs everywhere online; [this one is from OWID](https://ourworldindata.org/learning-curve).
People call this a "learning curve" or an "experience curve", although on a log-log plot the point is it doesn't curve, it's a straight line.

Why plot against cumulative production, rather than against time?
Moore's Law is the observation that transistor density doubles every two years.
[You plot it](https://ourworldindata.org/moores-law) with time on the x axis, and on the y axis, transistor density on a logarithmic scale.
Both graphs are plotting some measure of efficiency on the y axis, but Moore's Law uses time as the x axis, whereas Wright's Law uses cumulative production.

Wright's Law originates in a 1936 paper called [Factors Affecting the Cost of Airplanes](https://pdodds.w3.uvm.edu/research/papers/others/1936/wright1936a.pdf), by a Wright of no relation to the Wright brothers.
Here's his line on a log-log plot of cost vs cumulative production, the first instance of Wright's Law:

![](https://res.cloudinary.com/lesswrong-2-0/image/upload/v1794897621/lexical_client_uploads/ykdissbnulyqp28bzi9m.png)

Wright was talking about improvements within a single factory, and the steep decrease he saw was in labor cost.
Speculating as to the reasons, he discusses the workers getting better at what they do, and mentions [time-and-motion studies](https://en.wikipedia.org/wiki/Time_and_motion_study).
He also mentions better tools, both because they make work more efficient and because you can decrease labor costs by hiring less skilled workers.

The solar "Wright's Law" graph, spanning multiple decades, seems to measure something else entirely.
It isn't about decades-old factories with the world's most experienced workers.
It depicts decades of new factories being built in an expanding industry.

Arrow's paper [The Economic Implications of Learning by Doing](https://doi.org/10.2307/2295952)  presented a model where all improvements to manufacturing efficiency are due to new equipment.
He evocatively describes the efficiency of a machine as a function of its serial number.
This makes it hard to distinguish between "learning by doing" and invention, since improved equipment embodies inventions.
For example, even though we're still using silicon, there has been a succession of technologies for slicing the crystal into wafers.

In Arrow's model, progress doesn't come from time passing, or from routine production, but from investments in new capital.
We could formulate an "Arrow's Law": an increase in efficiency as a function of cumulative capital investment.

When does Wright's Law differ from a Moore's Law extrapolation in time?
When demand is unreliable, so there are years of low production, or at least stagnant growth in production.
If Wright's Law truly holds, then this will look like falling behind Moore's Law.

When does Arrow's Law differ from a Wright's Law extrapolation in cumulative production?
When investment is unreliable.
Years where people are still buying, but it is not possible to finance new equipment.

There's [a paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0052669) that says Wright's Law-style extrapolations are somewhat better than Moore's Law extrapolations, but not by much.
I couldn't tell you whether a hypothetical Arrow's Law extrapolation is better.
I don't know who collects data measuring total cumulative investment in production of a specific product.

I think it doesn't matter so much because these fits are not so precise anyway.
The real trick to all of these graphs, I think, is that huge errors look small on a log scale, and we adjust the line fit as more points come in.
Even if you're totally misled by the extrapolations year by year, the plot will still look great retrospectively decades later.
