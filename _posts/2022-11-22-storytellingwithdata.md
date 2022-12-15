---
layout: post
title: "Tips From a Scientist and Storyteller"
date: 2022-11-22
---
<div class="row">
<div class="left" markdown="1">
<b>Writing Sample for Brilliant, Data Science Producer</b>

<b>Submission Type</b>: Blog Post

Scientists are great with data. They love it. They'll happily spend their evenings in their labs, collecting their precious data, meticulously notetaking or just watching a tool tick towards completion. Years or months later, when they finally emerge with the data they were hoping for, they rejoice in excitement and can't wait to show you. <i>There's so much data, and it's good! The trends go the right way and the statistics are sound!</i>

The problem is, they aren't always great at explaining that to others.

They're disappointed when you aren't excited too. But you haven't sat in the lab with this data for months. You haven't thought about it until today.

When I was a PhD student, and even now working in industry, this was the world that surrounded me. Even with an advisor who loved a good, crisp data story as much as I did, we could not escape the hour-long presentations of endless slides, one plot after another, no cohesion and no clarity for the audience. 

<i>Here is a plot. Here is another plot.</i>

<i>We collected the data we sought to collect.</i>

<i>Success. </i>

<i>Applause.</i>

As someone who spends her weekends writing fiction or painting urban landscapes, I spent most of my career feeling like no one else saw data as a story. That wasn't true, of course, but it sparked in me the need to show others the beautiful ways in which art, storytelling and data are all connected. 

I'm lucky enough to teach a class on this topic at RIT, and have led presentations on effective data communication for my team at Intel, but that's not helpful if you aren't a college student in Rochester, NY, or an engineer at Intel. Here, I'll share a few tips that you can take with you to help your audiences be as excited about your data as you are.

<h2>Effective Visualizations </h2>
You can transform your visualizations by following five guidelines:
<ol>
	<li> Don't be afraid to use text: titles, axis labels, legends. These help clarify meaning and create context for the viewer. </li>
	<li> Use whitespace to help a visualization look cleaner. </li>
	<li> Use color sparingly and for a reason (<b>Focus Attention</b>)</li>
	<li> Avoid unneccessary clutter (i.e. background images, gridlines). As much as possible, every drop of ink on the chart should relate to your data. </li>
	<li> <b>Tell a story.</b></li>
</ol>

Here, I will go into detail on two of these guidelines that will help you quickly improve the effectiveness of your visualizations and how you present them: <b>focusing attention and telling a story</b>.

For an example of effective transformation from an overly saturated and colored bar chart to a more effective and visually appealing visualization, I point you to <a href="http://www.storytellingwithdata.com/blog/how-does-this-graph-make-you-feel">this chart makeover</a> from the Storytelling with Data website.

The transformed chart:

<img src="../../../assets/chart_transform1.PNG" width="90%" >

Think for a moment. How does the chart on the left make you feel? How about the one on the right? Hopefully, the chart on the right puts you at ease, and it does all of the hard work for you. You don't have to guess at the intended message, you don't have to hunt for comparisons between the bars, and the colors don't stress you out like the huge chunk of oversaturated red on the left.

<h2>1. Focus Attention </h2>
Data visualization is closely connected to neuroscience. This may suprise you, but the key to a good visualization is understanding how the brain works. At a very basic level, when you take in visual information, your brain kicks in to <i>see</i> (perception) and simultaneously to <i>think</i> (cognition). While thinking is certainly not a bad thing, cognition is much, <i>much</i> slower than perception. Visual perception is essentially automatic and happens in your sub-conscious, so it takes
very little energy. Often, especially in the Data Viz community, it is called "pre-attentive processing." On the other hand, cognition is slow and requires conscious, deliberate, focused thought as well as much more energy. Cognition is also called "attentive processing." 

<br>

Why does this matter to us? It matters because we can use these distinctions to our advantage to improve the effectiveness of our visualizations. To do this, all we need to do is make a visualization that envokes <b>more pre-attentive processing than deliberate thoughts</b>. If successful, when someone looks at our visualization, they will be able to understand it very quickly and easily just by "seeing", without having to expend additional time and energy to think about what they are seeing.

A lot of research has been done on the visual properties that best use pre-attentive processing. I especially recommend Colin Ware's book "Information Visualization: Perception for Design." According to him, the four best pre-attentive visual properties are: color, form, movement, and spatial positioning. This makes sense: you don't need to spend a lot of time and effort to recognize if there are two separate columns of text on a screen, for example, provided they are spaced far enough apart
and not too cluttered with extraneous distractions. 

To drive this point home, consider the power of using color to draw attention using pre-attentive processing. This technique is often called <b>popout</b>.

In the abstract scatterplot below, the large difference in color between the muted grey and saturated red dots makes it very easy to use pre-attentive processing to instantly recognize the difference and draw your eyes to the red dot.

<img src="../../../assets/popout1.PNG" width="50%" >

It's the same concept that's used in photography or visual art to draw the viewers' eyes to a specific point of interest. Contrast. 

Where are your eyes drawn in the photograph on the left, below? How about the one on the right?

<img src="../../../assets/focus2.PNG" width="90%" >


Most likely, your attention instantly goes to the big, red stop sign. But for the image of the umbrellas, there is very little focus. Likely, everyone's eyes will be drawn to a different place. There is no focus point, and pre-attentive processing is minimized. Think about some ways that this image could be improved to enhance its focus and optimize the viewers' pre-attentive processing.

Finally, consider how we might take advantage of this concept in a real visualization by comparing the left and right charts below. 

<img src="../../../assets/focus.PNG" width="90%" >

Which one do you find easier to understand?

<h2>2. Tell a Story </h2>

The final trick to a compelling visualization is understanding the importance of <b>story</b>.

Just like a novel, data has a narrative. If you ignore that narrative, no matter how pretty your visualization is, no one will remember it.

Like a novel, data has a beginning, a middle, and an end. Or, perhaps more interestingly, <b>a plot, a twist, and an ending</b>. For more details, take a look at <a href="http://www.storytellingwithdata.com/blog/2020/5/21/the-structures-of-story">The Structures of Story</a> from the same Storytelling with Data site. As Cole Nussbaumer Knaflic describes in <a href="https://www.youtube.com/watch?v=8EMW7io4rSI">her incredible Talk at Google</a>, the story of data can be broken down into the
following:

<ol>
	<li> <b>Plot</b>: What context is essential?</li>
	<li> <b>Twists</b>: What is interesting about the data and what it shows?</li>
	<li> <b>Ending</b>: What do you want your audience to do?</li>
</ol>

You can also think of "twists" as a story's climax, and the ending as a resolution. A call to action.

And, like any novel or piece of art, you have to think about your audience. The Plot, Twist, and Ending will vary greatly depending on who you are talking to.

It's very easy to share about your data in the chronological order that it affected you. I began to explore the data, I found some initial results. I refined those results. I made some conclusions. Here they are. 

I've seen this hundreds of times in hundreds of presentations over the years.

That may be your story, but that is not the story of the data itself.

For now, I leave you with <a href="http://nytimes.com/interactive/2021/06/30/opinion/environmental-inequity-trees-critical-infrastructure.html">this excellent example of Data Storytelling from the New York Times</a>, as inspiration to go out and tell your own data story.











</div>
</div>
