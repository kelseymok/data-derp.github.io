---
sidebar_position: 4
minutesToComplete: 5
---

# Reflect
Congratulations on finishing the exercises! You've learned how to take some data, a question, and transform that using the Spark API into something that represents an answer to that question.

You might have thought: **is that all that Data Engineering is?**. The answer is **no, that was just a demonstration of data handling** (and we learned a little bit of Spark while we were at it!). In reality, Data Engineering work involves handling large amounts of data that need to be transformed at specified intervals (e.g. every hour, every day, every month) ("batch" transformations) or in [near] real time ("streaming"), both of which require different technologies and handling techniques. 

In the next sections, we'll talk about how we might handle this OCPP data in the EV Charging domain as a platform, first covering "batch" transformation use cases and also "streaming" use cases later on.

## Q&A
> We didn't handle any large data in the last exercises. Why did we need to use Spark?

You're right, we didn't need to use Spark and it was probably a bit heavy for what we needed to do. A single-node Pandas would have served just fine. But for the purposes of this training, the curators wanted to be consistent with the tech that we used and we often can't get enough Spark practice.

> Do I need to memorize the entire Spark API? There's a lot of functions.

You don't, but it's more important to get an overview of what it can do, how it optimises (later!), and to have a solid understanding of the SQL underlying it.