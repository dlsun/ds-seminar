# Data Science Seminar
## Winter 2021
## Overview

This is a seminar for the Cal Poly Data Science Fellows. We will meet weekly over Zoom on MWF. 

Mondays:
* Reading discussions
* Discussions will be held in three breakout rooms, 6 students per room. 
* Each student receives a designated role for each reading: "presenter", "supporter", "opponent".  Each breakout room will have two presenters, two supporters and two opponents.  
* Discussions start with presenters giving a succinct and fact-based summary of the reading material. then supporters will discuss what they liked in the reading material. After that, opponents will critique the work. Following this scripted discussion, there will be additional time for back and forth between all students, and for faculty reflections on the reading material.

## Grading

Please enroll in DATA 472 for 1 unit, on a CR/NC grading basis.

To earn a CR grade, you are expected to:

- attend all seminars
- complete readings and post a question or comment about the reading to the Slack channel

## Readings

The theme of the readings for Winter 2021 is **the present**.

### Week 9
Topic: Computational Psychiatry 

We've come a long way since ELIZA! ELIZA was an AI psychiatrist that took great advantage of natural language generation and Rogerian psychological methods. While it revolutionized computational assistants, it was very limited and had no knowledge base. Today there is a resurgance of fully data driven / AI driven methods and computationally mediated methods in pscyhotherapy. Two persistent problems exist, each at a different level of abstraction: First, how do we use data-driven natural language generation but with high quality output and coherence? (unlike GPT-3!); Second: Do we have evidence that we can adapt psychotherapy method in a deepr, more fundamental way than ELIZA did?

The pro side should argue that computers can solve these problems now. They can adopt the theory and solve the means of communication. The con side should be saying "hold on a minute!" We may not want to do this, and there are major reasons we don't have good enough technology anyway.

Readings 
1. [Self-Learning Architecture for Natural Language Generation](https://www.aclweb.org/anthology/W18-6520.pdf)
2. [Towards a Neural Model of Bonding in Self-Attachment](https://ieeexplore.ieee.org/iel7/7256526/7280295/07280548.pdf)

### Week 8

Topic: Learning Bayesian Networks/Learning with Bayesian Networks

Bayesian Networks (Bayes Nets) are compact representations of joint probability distributions over a set of discrete random variables (each with finite number of values). In a variety of settings Bayesian Netowrks can be used to describe relationships between the random variables in a succinct, and easy-to-manipulate way. Bayesian Networks can be learned from data.  In turn, a Bayesian Network can be used to simulate/synthesize a dataset.  

Your assignment for Week 8 is to read one of the most influential papers on the topic of learning Bayesian Networks, and to gain some insight about the potential uses of Bayesian Networks in Machine Learning/Data Science.  The paper is more technical than the conversation that we want to have, but it is a foundational paper on the subject.

The "pro" side should discuss the uses of Bayesian Networks for data science applications - situations when building Bayesian Netoworks from data is a good way to proceed.

The "con" side should discuss the limitations of the use of Bayesian Networks, and the difficulties that are associated with their use.

Note: one one paper is assigned. The paper was written in 1996, but was updates in 2020. Unfortunately, the 2020 version I found has no bibliogrpahy. So, two links are provided below. I recommend that you read the 2020 version, but use 1996 version for bibliographic references.

* [David Heckerman: A Tutorial on Learning With Bayesian Networks- 2020 Version](https://arxiv.org/pdf/2002.00269.pdf)
* [David Heckerman: A Tutorial on Learning With Bayesian Networks- 1996 Version](http://www.cs.cmu.edu/afs/cs.cmu.edu/Web/People/dgovinda/pdf/tr-95-06.pdf)

### Week 7

Topic:  Unsupervised Clustering

In Machine Learning, we talk a lot about prediction methods, where the relative "success" of any given algorithm is easily measurable.  What happens when we start applying unsupervised methods, such as clustering, where there is no clear "right" answer?  

The "pro" side should argue in favor of the central thesis of the paper; namely, that there is no way to evaluate a clustering method except in the context of how the results will be used.  The "con" side should argue against this thesis, in support of some of the evaluation metrics that are critiqued in the paper.

Reading:
* [Clustering: Science or Art?](http://proceedings.mlr.press/v27/luxburg12a/luxburg12a.pdf)

### Week 6

Topic: The Reproducibility Crisis

Results in science and social science are published, then turn out to be false. How serious is this problem? The "pro" side will argue that this is a crisis that undermines public trust in science, while the "opposition" will argue that the reproducibility crisis is overblown.

Reading:

* [Baker. Is there a reproducibility crisis?](https://github.com/dlsun/ds-seminar/blob/master/readings/Nature_ReproducibilityofResults.pdf)
* [Simmons et al. False-Positive Psychology: Undisclosed Flexibility in Data Collection and Analysis Allows Presenting Anything as Significant](https://github.com/dlsun/ds-seminar/blob/master/readings/Simmons%20PsySci%202011.pdf)

### Week 5

Topic: Dealing With Small Data

On the heels of some of our previous conversations about data science hype often going hand-in-hand with big data hype, it seemed appropriate to spend a little more explicit time on non-big data situations. This is a popular blog and probably worth an exploration beyond this article. There could actually be quite a bit to unpack with this reading. I (Glanz) challenge the "supporters" and "opposers" to really go at it with this one...Here are some starting questions, but don't feel restricted to just these.

* What, if any, explicit and/or implicit assumptions is the author making when proposing each tip?
* What are the pros and cons of each tip?
* If your dataset is small and there's not much to do about the size, can you really call your work with it "data science"?

Reading:

* [7 Tips for Dealing With Small Data](https://towardsdatascience.com/7-tips-for-dealing-with-small-data-7ffbd3d399a3) or here on [github](https://github.com/dlsun/ds-seminar/blob/master/readings/7%20Tips%20for%20Dealing%20With%20Small%20Data%20_%20by%20Daniel%20Rothmann%20_%20Towards%20Data%20Science.pdf)

### Week 4
Topic: Underspecification of Neural Network Models

A machine learning pipeline is underspecified when it can return many predictors with equivalently strong held-out performance in the training
domain. The paper discusses how this results in diminished accuracy on different real-world verification sets and possible solutions to address the problem. 

Reading:
* D'Amour, A. et al. (2020).  [Underspecification Presents Challenges for Credibility in Modern Machine Learning](https://github.com/dlsun/ds-seminar/blob/master/readings/2011.03395.pdf).  



### Week 3
Topic: Data vs. Theory

Intro to reading: In 2008, Chris Anderson, then editor-in-chief of Wired Magazine, published a provocative editorial entitled "The End of Theory: The Data Deluge Makes the Scientific Method Obsolete."  He essentially argues that traditional methods of scientific discovery and business strategy are inferior in comparison to what can be achieved with data mining on large-scale datasets.  This is a fundamentally attractive idea -- that through big data, we can leave behind human-constructed models and theories about the way the world works, and instead discover directly from the data all the answers we need.  There are clearly many examples of where data-driven methods have prevailed over traditional hand-crafted alternatives, and all of you must "believe in data" somewhat based on your choice of academic field to study!  But, what is missing in Anderson's discussion of the promise and successes of big data?  Is data really all we need?  And when might data lead us astray?  

Note that this article has almost 2,500 citations on Google Scholar and is widely discussed in followup blog posts and magazine articles -- you might want to search a bit to find some different perspectives on this bold idea.

Reading:
* Anderson, C. (2008).  [The End of Theory: The Data Deluge Makes the Scientific Method Obsolete](https://www.wired.com/2008/06/pb-theory/).  Wired Magazine.

### Week 2
Topic: Bias and Fairness of Rankings and Recommendations

Introduction to Readings: Rankings and recommendation systems are everywhere. We take them for granted. We base a lot of big and small decisions on the results presented to us. The readings below share several themes. At their heart they are examples of models and systems that have unintended and possibly detrimental impacts on society. When you are reading them, please think about things the original designers could/should have done differently. Put yourselves in their position, and think about whether you would have forseen or anticipated any of the results or problems. Think about how you can design and study the many different models of that recommend a
nd rank items for you. Did the paper (third link) present a reasonable approach to studying a black box? What faults do you find if any? What could be done with their
 findings? What did the designers of both the studies and the original systems do well (i.e., think about the positive as well as the negative). 

Readings:
* <a href="http://dlsun.github.io/ds-seminar/readings/college_chapter.pdf">Weapons of Math Destruction (Chapter)</a>
* <a href="https://www.cmu.edu/news/stories/archives/2015/july/online-ads-research.html">Questioning the Fairness of Targeting Ads Online (Brief Summary)</a>
* <a href="http://dlsun.github.io/ds-seminar/readings/AutomatedExperimentsonAdPrivacySettings.pdf">Original article from the above brief summary</a>

### Week 1
No reading

## Fall 2020

## Overview

This is a seminar for the Cal Poly Data Science Fellows. We will meet weekly over Zoom on Thursdays. There are two 
sessons: at 10 AM and at 3 PM. You only need to attend one of these sessions. Each week there will be some readings 
relevant to data science, which we will discuss for 30 minutes. Afterwards, individual fellows will give updates on 
their research projects.

## Grading

Please enroll in STAT 400 for 1 unit, on a CR/NC grading basis.

To earn a CR grade, you are expected to:

- attend all seminars
- complete readings and post a question or comment about the reading to the Slack channel

## Readings

The theme of the readings for Fall 2020 is **the past**.

### Week 1: September 17

No reading


### Week 2: September 24

Hypothesis testing is a core part of many statistics classes. But where did the ideas such as the p-value, Type I error, and power come from? This reading reviews the chaotic history of hypothesis testing in the 20th century.

- [Chapters 10 and 11](http://dlsun.github.io/ds-seminar/readings/LadyTastingTea-HypothesisTesting.pdf) from Salsburg, D. (2001). _The lady tasting tea: How statistics revolutionized science in the twentieth century_. Macmillan.
- 


### Week 3: October 1
We will look at how hypothesis testing has influenced other disciplines and the controversy this has caused.

- Cohen, J. (1994). [The earth is round (p < .05)](http://www.iro.umontreal.ca/~dift3913/cours/papers/cohen1994_The_earth_is_round.pdf). American psychologist, 49(12), 997. 
- Gill, J. (1999). [The insignificance of null hypothesis significance testing](https://american.theopenscholar.com/files/jeffgill/files/hypo.pdf). _Political research quarterly_, 52(3), 647-674.


### Week 4: October 8

We will look at the Frequentist vs. Bayes debate. Next week, you will be randomly assigned to defend either frequentism or Bayesianism. Please come prepared to 
defend both, although we want you to take a side in your Slack post this week.

- New York Times Article: [The Odds, Continually Updated](readings/The%20Odds,%20Continually%20Updated%20-%20The%20New%20York%20Times.pdf)
- [Frequentist and Bayesian Approaches in Statistics](https://www.probabilisticworld.com/frequentist-bayesian-approaches-inferential-statistics)
- Efron, B. (2005). [Bayesians, frequentists, and scientists](https://dlsun.github.io/ds-seminar/readings/Bayesians,%20Frequentists,%20and%20Scientists.pdf). _Journal of the American Statistical Association_, 100(469), 1-5.
- xkcd comic on [Frequentists vs. Bayesians](https://xkcd.com/1132/)

Here are some additional readings that might be of interest.

- MIT Lecture Notes: [Comparison of frequentist and Bayesian inference](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/readings/MIT18_05S14_Reading20.pdf).
- Efron, B. (1986). [Why isn't everyone a Bayesian?](https://dlsun.github.io/ds-seminar/readings/Why%20Isn't%20Everyone%20a%20Bayesian.pdf) _The American Statistician_, 40(1), 1-5.
- Andrew Gelman's blog post: [Why I Don't Like Bayesian Statistics](https://statmodeling.stat.columbia.edu/2008/04/01/problems_with_b/). (This is an April Fools' Joke written by a famous Bayesian statistician. However, it contains some good ideas.)

### Week 5: October 15

A survey of the history of the connection between early statistics and the eugenics movement.

- [Scientific Priestcraft](https://github.com/dlsun/ds-seminar/blob/master/readings/Superior_Ch3.pdf) From "Superior: The Return of Race Science" chapter 3

Bonus reading from last week:  A metaphor for the difference between randomness and unknown-ness, and the consequences in Bayesian analysis.

- [The Boxer, the Wrestler, and the Coin Flip: A Paradox of Robust Bayesian Inference and Belief Functions](http://www.stat.columbia.edu/~gelman/research/published/augie4.pdf) Andrew Gelman, The American Statistician, May 2006, Vol. 60, No. 2

### Week 6: October 22

We will examine the history of AI winters.

- [Analyzing the Prospect of an Approaching AI Winter](https://github.com/dlsun/ds-seminar/blob/master/readings/Forschungsarbeit-Sebastian-Schuchmann-030519%20(1)%20(1).pdf) Sebastian Schuchman, May 3, 2019

### Week 7: October 29

We will discuss the Turing Test and whether machines can be intelligent.

- [Computing Machinery and Intelligence](https://github.com/dlsun/ds-seminar/blob/master/readings/computing_machinery_and_intelligence.pdf) Alan Turing, Mind, October 1950, Vol. 59, No. 236
- [Is the Brain a Good Model for Machine Intelligence?](https://github.com/dlsun/ds-seminar/blob/master/readings/is_the_brain_a_good_model_for_machine_intelligence.pdf) Rodney Brooks, Demis Hassabis, Dennis Bray, and Amnon Shashua,  Nature, Feburary 2012, Vol 482

Questions to consider:
* Is the Turing Test a good test of whether a machine is intelligent?
* Are today’s systems (like IBM Watson, Google’s image recognition systems, etc.) intelligent?  Could a convolutional neural network be intelligent?
* In trying to achieve machine intelligence, should we try to mimic the brain or should we apply a pure engineering approach?
* Is the brain just a computer – could its functionality be replicated by a machine?

### Week 8

No reading. Focus group with Lubi.

### Week 9

Main reading: Challenges and Opportunities with Big Data, a community white paper developed by leading researchers across the United States, 2012. <http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/bigdatawhitepaper.pdf>

and The Claremont Report on Database Research, Communications of the ACM, Vol. 52, No. 8, 2009 <http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/claremont-report2009.pdf>

Supplemental reading:
- 2005: Lowell self-assessment. http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/lowell-report2005.pdf
- 1998: Asilomar report. [PDF](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/Asilomar_DB_98.pdf).
- 1996: Strategic directions in database systems. [PDF](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/StrategicDirections.pdf).
- 1995: Achievements and Opportunities. [PDF](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/DB-research1995.pdf).
- 1988: Future Directions in DBMS Research. [PDF](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2014/papers/Stonebraker88.pdf)

Given the timeframe there is no expectation that any supplemental materials will be read, but I want them available in a single place.

### Week 10
reading: D. I. HOLMES and R. S. FORSYTH, "The Federalist Revisited: New Directions in Authorship Attribution" [PDF](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.890.8767&rep=rep1&type=pdf)

In 1964 Mosteller and Wallace showed how statistics (and Bayesian analysis) can be applied to the problem of authorship attribution, and by implication stylometry (understanding, measuring and detecting "style"). Holmes and Forsyth built on that work in the 1990s, laying the foundations for more computationally intensive methods of behavioral analysis that has major implications in our lives in 2020s. Here are some motivating questions for the discussion this week:

- What are the parameters for the authorship attribution problem?
- Do you think there's a definitive style of writing associated with each person? Can that style be faked? 
- How has computational stylistics changed in the recent decades?
- How does the 1964 work on Federalist Papers relate to your personal life today?
- 
