---
layout: post
title: "Dirty Data I: Introduction"
date: 2019-02-22
---

When working with an new dataset, the first task at hand is to get
familiar with it. Think of it like scoping out a house to buy; you want
to know the square footage, whether there's mold, if anyone died in
it, how many bedrooms it has, etc. With this information you can make 
better decisions re: whether/how to move forward with the sale.

Hopefully no one died in your dataset, but like houses on on the 
market datasets can contain unpleasant surprises. These surprises have the potential to confuse and cloud your analysis. I'll be writing a 
series of posts discussing how to deal with a number of these issues. 
As they come out I'll link to each new topic in this post, or you can 
check out the feed to find the topic relevant to your work.

For this week, something easy-peasy. After reading in the dataset
(let's call it df), I always run 
<code>df.head()</code> 
If you're working in Jupyter Notebook, this returns a nice 5 row slice 
of your dataframe in Markdown. The default argument is 5, for 5 rows, 
but if you want to see more or fewer rows, say, n rows, just enter that
integer as an argument. For example,
<code>df.head(20)</code>
will show you the first 20 rows of your dataset.

See you next week!

