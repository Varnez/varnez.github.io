---
layout: post
title: 10th of October, 2022
subtitle: New Journey
readtime: true
comments: true
---


<div class="warning" style='padding:0.1em; background-color:#E9D8FD; color:#69337A'>
<span>
<p style='margin-top:1em; text-align:center'>
<b>With this post, I begin a new journey.</b></p>
<p style='margin-left:1em;'>
 General Artificial Intelligence is something that has always been able to spark a flame of the best kind of curiosity there is within me, but, in a sense,
 as weird as it is, I've never actually pursued to develop into actual founded knowledge.<br/><br/>

 With the start of my master's degree and the open question of a thesis project, I think the time is nigh to get my hands on this matter once and for all.<br/><br/>

 This is my first post of what will be a compilation of material, publications and personal notes on the current state of the art in the ambit of General
 Artificial Intelligence.<br/><br/>

 Also, in this header notes I might ramble a little. Sorry for that.<br/><br/>

 I think it might be within the blood: as much as I wanted this to be as straight to the point as possible, one cannot avoid providing their ego a voice.
 Or maybe it's just me?<br/><br/>

 Let us begin.<br/>
</p>
<p style='margin-bottom:1em; margin-right:1em; text-align:right; font-family:Georgia'>
 <b><i>Varnez<br/>10th of October, 2022</i></b>
</p>
</span>
</div>


With this very first post I aim to get a general view of the current state of General Artificial Intelligence, as well as the current open approach paths.

After visiting a couple of post with very straightforward searches, it is easy to realice that, nowadays, the conversation is very shifted towards separating
the necessity of shaping AGI entirely after the human mind. It seems obvious to base our idea of General Intelligence in the most successful case
that we can find, but as it is wonderfully exposed in the following
article, [The flawed quest for Artificial General Intelligence - do you need to know how the mind works for AGI?](https://diginomica.com/flawed-quest-artificial-general-intelligence-do-you-need-know-how-mind-works-agi):

> The problem is that developing a human-level AI without understanding how the mind works will be an entity that does not possess the same reality as humans.

As it develops, this consideration seem rooted in that the current environment of AGI is focused on reproducing said General Intelligence explicitly from the perspective of
the mind as a phenomena that takes place uniquely on the brain, while [current cognitive theories (Embodied Cognition)](https://en.wikipedia.org/wiki/Embodied_cognition) find our cognitive system deeply rooted within the complete extent of
our nervous system.

Nevertheless, in that same previously mentioned article, there is a very interesting quote from Ray Kurzweil, Google’s Director of Engineering:

> We have to use different techniques — different **self-organizing methods** — that are biologically inspired.

I wanted to make a heavy emphasis to those **self-organizing methods**, because as I currently understand it know, that is the base the current main paths being nowadays
taken in AGI: a self-organizing hierarchical system of multiple levels of intelligence, being the current narrow approaches the smallest 'lego brick' within this
structure.

In those lines, the own François Chollet already mentioned in the previous article, as well in probably most any other article on the topic out there. In 2019, he published
his work [On Measure of Intelligence](https://arxiv.org/abs/1911.01547).

In this white paper, François Chollet points out the current differences in scope when we speak on Intelligence, depending on it being Biological or Artificial. This
was a few years ago - AGI hadn't earned yet a place in a mediatic spotlight, and the expectancies on narrow AI were as prevalent as they might ever be, thus such a
take on Artificial Intelligence take.

The problem has in roots in conceiving Intelligence itself: it will only grow as much as we are able to conceive it might grow, and thus if we want it to break a
certain given limit, it is imperative for us to be able instruct the machine a set of objectives that translate into the breakthrough of said task.

Thus, one of the main point in Chollet's paper is a measurement of this ambit of Generallity for an Intelligent system. At least, this is as much as I know, since I
have to admit, I still haven't properly read his paper in its full extent. That is my next main objective, since I want all the insight it
contains to be a part of my mental landscape on the topic before I consider next steps.

In the meant time, I've made me a few spoilers by reading a couple of brief articles summarizing its
contents, just to have a lead on what to expect within the paper's pages.

- [François Chollet's general intelligence test, by Pablo Padila](https://pgpbpadilla.github.io/chollet-general-intelligence-test)
- [On “On the Measure of Intelligence” by F. Chollet (2019), by Robert Tjarko Lange](https://roberttlange.github.io/posts/2020/02/on-the-measure-of-intelligence/)

In them it is highlighted its inspiration on [Psychometrics](https://en.wikipedia.org/wiki/Psychometrics). As Robert Tjarko Lange writes in the second article:

> Chollet proposes to develop human-centered tests of intelligence which incorporate human cognitive priors & the developmental psychology notion of core knowledge.<br/> (...) <br/>Additionally, Chollet provides a formal algorithmic information theory-based measure of the intelligence of an artificial system.

Thus, it seems to tackle those two previous points: the proper contextualization of Intelligence given an artificial system in contrast to a biological, holistic
system and trying to adapt the teaching from the field of Psychometrics into a mean to evaluate the generalization (addressed straightforward as Intelligence itself)
capabilities of an artificial system.

Also, again in the second article, Robert Tjarko Lange points to a very interesting point when summarizing the different key insights on prior efforts on solving [the challenge](https://github.com/fchollet/ARC) that Chollet proposed along with his paper:

> Core knowledge is hard to encode. Relational deep learning and geometric deep learning provide promising perspectives but are still in their infant stages. We are far from being able to emulate evolution with meta-learning.

These comment alone open up the road for two potentially promising paths: **Relational** and **Geometric** deep learning, both fairly unknown to me. Any of those could be very promising ambits in which to base a thesis. I will keep an eye on them.

To begin with, I will start over the reference provided in the article, [An Explicitly Relational Neural Network Architecture](https://arxiv.org/abs/1905.10307), a paper published on May from 2019 by Murray Shanahan et al on the ambit of Relational Deep Learning. Its abstract states as follows:

> With a view to bridging the gap between deep learning and symbolic AI, we present a novel end-to-end neural network architecture that learns to form propositional representations with an explicitly relational structure from raw pixel data. In order to evaluate and analyze the architecture, we introduce a family of simple visual relational reasoning tasks of varying complexity. We show that the proposed architecture, when pre-trained on a curriculum of such tasks, learns to generate reusable representations that better facilitate subsequent learning on previously unseen tasks when compared to a number of baseline architectures. The workings of a successfully trained model are visualised to shed some light on how the architecture functions.
