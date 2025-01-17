---
layout: landing
---

# Data Science Seminar

## Grading

Please enroll in DATA 472 for 1 unit, on a CR/NC grading basis.

To earn a CR grade, you are expected to:

- attend all seminars
- do the reading
- complete the assignment associated with each reading

## Readings

## Spring 2023

### Week 10: June 7th

Wrap-up and celebration!

Don't forget to send in you artwork (Week 7 homework) by June 6th.

### Week 9: May 31

Topic: Recommender Systems

One of the things missing from our Data Science discussions in DATA NNN coursework and beyond are recommender systems and recommendation engines. This is in part because quite a bit of methodology that goes into recommendation engines comes from classification, regression and clustering. But this is also somewhat unfortunate, because there are issues that are specific to recommender engines that get ignored. This week you are reading two surveys on recommender systems.

[Recommender Systems Survey (Bobadilla et. al, 2013)](https://www.sciencedirect.com/science/article/abs/pii/S0950705113001044)

This is a general survey of recommender systems. It is somewhat old for "future" being the general theme, but it is a good overview of the current state of non-deep-learning systems.

[Deep Learning based Recommender System: A Survey and New Perspectives (Zhang et. al, 2018)](https://arxiv.org/pdf/1707.07435.pdf). This is a newer and more in-depth technical survey documenting how deep learning techniques are used in the guts of the recommender engines.

How to read these? 
* The first survey is broad and not overly technical. Read fully. This will give you the background and the set up for reading the second paper. 
* The second paper has a lot of technical content. This may be useful for you in the future, should you be tasked with building a recommendation system. In the meantime, you can internalize the methodology that is being discussed, but do not have to get too deep into the math.

Please come to class prepared to discuss the first paper, and with at least one *already written down* short paragraph summarizing *one* takeaway or idea from the second paper that you kind of understood or were interested to learn more about.

### Week 8: May 24

Topic: Towards Fair, Transparent and Accountable AI

Many of our discussions this year have considered the ethical implications of AI and the many pitfalls inherent in the machine learning process.  This week we will consider strategies to ensure that future AI systems are fair, transparent, and accountable, and ask whether this is even a realistic possibility.

Readings
1. [Hutson, M. It’s Too Easy to Hide Bias in Deep-Learning Systems.  IEEE Spectrum, January 2021.](https://spectrum.ieee.org/computing/software/its-too-easy-to-hide-bias-in-deeplearning-systems)
2. [Mitchell et al., Model Cards for Model Reporting.  FAT* '19: Proceedings of the Conference on Fairness, Accountability, and Transparency, January 2019.](https://dl.acm.org/doi/abs/10.1145/3287560.3287596)

The first reading points out the many ways in which an organization might try to make their AI system appear fair and unbiased, while actually operating in a biased manner.  It also discusses some possible strategies to address this problem.  The second reading proposes a way to address this problem head on, by providing a performance "report card" along with the AI model when it is distributed.  

Your groups will present a [Hippocratic Oath of AI](https://en.wikipedia.org/wiki/Hippocratic_Oath).  Each of your statements in the Oath should be supported by examples or quotes from these or other readings from this year.


### Week 7: May 17

Topic: Generative Art

[In-Class Video: Generating Basic Tiling with turtle](https://www.youtube.com/watch?v=Cm_SzDlQ2cM)

In-Class Activity:  Make your first art piece.  Each person should produce their own unique piece, but your group's collection should have something in common, such as similar colors, similar movement principles, etc.

Homework: Watch the remaining videos in the series.  By Week 10, produce a more complex piece or series of pieces, including titles.  We will have a "gallery" at the Week 10 meeting/party.


### Week 6: May 10

Topic: Data Feminism

Guest speaker: Dr. Allison Theobold

### Week 5: May 3

Topic: Under the Covers of GPT-3

Guest speaker: Jim Bodwin


### Week 4: April 26

Topic:  Reproducibility

*Job security through code obscurity*

Have you ever inherited code so impossible to follow, you decided it was easier to rewrite it yourself?  

In this class, we'll learn by counterexample, by implementing the most difficult to read and inefficient code possible, then trying to figure out what's going on in each other's messy code.

Rules:
* Your code must successfully achieve the assigned goal, in either R or python.
* You may **not** add any comments that are not accurate.
* You may **not** add complexity by adding unnecessary lines that do unrelated calculations.
* You may **not** add complexity by splitting simple calculations into many steps, e.g. turning `b = a + 2` into `c = a + 1` and `b = c + 1`
* You **may** add confusion by giving things bad names, e.g. `sum_ab = a - b`
* You **may** take inefficient approaches to calculations that have more efficient shortcuts.



### Week 3: April 19

Topic: Examples of Explainable Boosting

Readings/Discussion

Teams will give a 10-15 minute lecture on their assigned topic.  You will NOT have access to a projector - please plan to use the blackboard and/or handouts to explain your topic.  You should include some mathematical/conceptual explanation of the topic, but also some discussion of its place in ML progress: Do you see this method as a solution to any problems that currently exist? 

Team 1: ADA Boost (https://www.youtube.com/watch?v=LsK-xG1cLYA)
Team 2: Gradient Boosting (https://www.youtube.com/watch?v=3CC4N4z3GJc)
Team 3: Explainable Boosting (https://towardsdatascience.com/the-explainable-boosting-machine-f24152509ebb)


### Week 2: April 12

Topic: Predicting the future of the field

> "I have traveled the length and breadth of this country and talked with the best people, and I can assure you that data processing is a fad that won't last out the year."
> - Editor of Prentice Hall business books, 1957

It's easy to look back and laugh at predictions of the future that turned out to be dead wrong.  As we move into speculative readings, that suggest hypothetical future directions for Data Science, how do we know which ones are plausible?  This week you'll read papers from the past, and compare them to a recent paper that looks ahead to the next decades of data.

Readings
1. [On the Future of Statistics (1942)](https://www.jstor.org/stable/2980609?casa_token=PP52fd7TNakAAAAA%3AqoJm6zjE9CUjLzRL3Xnoo2OScq0rqkS1QCeldkF0frjietpKs1PnFZcb0hWUKfAkhk1Qd6JAgtcdQVligKPBySNAf2fqKlhw36qTW733RANyevTa7us&seq=9#metadata_info_tab_contents)
2. [The Future of Statistics as a Discipline (1981)](https://apps.dtic.mil/dtic/tr/fulltext/u2/a116258.pdf)
3. [The Future of Statistics and Data Science (2018)](https://discovery.ucl.ac.uk/id/eprint/10045833/1/olhede-article-finalv4.pdf)

In your groups, one person should read each paper.

Each person find at least 2 quotes or ideas that are, in your opinion, accurate or true today; and at least 2 that do not seem to hold up.  As a group, choose a few of your favorites to present, along with references to support the accuracy/inaccuracy of the prediction.

### Week 1: April 5

In-Class activity: Cards Against Data Science


## Winter 2023

### Week 9: March 8

We'll finish off this quarter with another discussion about ChatGPT. Please complete the following reading and prepare for our discussion this Wednesday via the following assignments.

* Reading: [https://nymag.com/intelligencer/article/ai-artificial-intelligence-chatbots-emily-m-bender.html](https://nymag.com/intelligencer/article/ai-artificial-intelligence-chatbots-emily-m-bender.html)

All teams should prepare the following from two perspectives: 

1. Us as an ongoing data science fellowship

2. A lay audience. That is, summarize this reading for your friends, parents, or other contacts might know less about AI and data science than you.

* **Team 1 (Bella, Zachary, Leander)**: Summarize the reading. 

* **Team 2 (Erik, Anthony, Sarah, Sam V.)**: Compare/contrast ChatGPT to an entity like the octopus from the story. 

* **Team 3 (Sucheen, Sam w., Sophia, Anagha)**: Compare/contrast ChatGPT to a parrot. 

Finally, last week we talked about the idea of using and citing ChatGPT...and its limitations. Please come prepared to discuss when it would be appropriate to cite ChatGPT and how you would do so.

### Week 8: March 1

We're going to begin discussing ChatGPT, and other similar tools, over the next couple of weeks and likely next quarter too! If you're unfamiliar with ChatGPT, please read the following short synopsis:

[https://www.digitaltrends.com/computing/how-to-use-openai-chatgpt-text-generation-chatbot/](https://www.digitaltrends.com/computing/how-to-use-openai-chatgpt-text-generation-chatbot/)

It is extremely exciting and powerful. Your first assignment concerning ChatGPT involves the following:

* Research "AI hallucination". What does it mean? What does it involve?

* **Team 1 (Bella, Erik, Sucheen, Sam V.)**: Force ChatGPT to hallucinate and come prepared to share the experiences with the class. What topics did you choose and what did ChatGPT do? Bonus points for bringing examples that make the other two teams' jobs more challenging!

* **Team 2 (Anthony, Zachary, Anagha, Sam W.)**: Come to class prepared to discuss why AI hallucination is a bad and dangerous thing.

* **Team 3 (Sarah, Sophia, Leander)**: Come to class prepared to discuss why AI hallucination is not a serious issue and that we don't need to worry too much about it.

### Week 7: February 22

In this next exercise you'll be working with a team, again, to revisit the kidney disease dataset. Please read the instructions for the second assignment and access the data at the following link, and come prepared to next week's class:

[https://drive.google.com/drive/folders/1vXFloq65bmXzwWfB-K6VMJtnWbRy52I3](https://drive.google.com/drive/folders/1vXFloq65bmXzwWfB-K6VMJtnWbRy52I3)

### Week 6: February 15

One of the dangers of AI and Machine Learning technologies becoming ubiquitous is that they inevitably become the tools in product marketing, fundraising, and attention-grabbing campaigns.  As data scientists we do not always control how our work is presented to others and in what form.  As consumers we may want to recognize when claims of AI use exceed plausibility, or spurious.

AI/ML researchers and sociologists started using the term "AI snake oil" to discuss situations when AI technology is being sold for unsuitable purposes, or when the marketing claims of AI input into a company's product are dubious.

Looking at the problem from another angle, we as data scientists, machine learning experts and AI researchers must understand the limitations of the tools we use to analyze data, make predictions, and obtain insight from data.  We must be able to separate the real contributions and capabilities of AI/ML systems from the claims made in public space.

So, let's take a look at how AI snake oil works and how to recognize it.

For next week's assignment, watch  Arvind Narayanan's talk "How to Recognize AI Snake Oil" available here:  [https://www.cs.princeton.edu/news/how-recognize-ai-snake-oil](https://www.cs.princeton.edu/news/how-recognize-ai-snake-oil)
(1 hour 37 minutes)

The slides for the talk can be found here: [https://www.cs.princeton.edu/~arvindn/talks/MIT-STS-AI-snakeoil.pdf](https://www.cs.princeton.edu/~arvindn/talks/MIT-STS-AI-snakeoil.pdf)

For some additional insight and takes, you can also watch this University of Oxford virtual panel on Fake AI, snake oil, pseudoscience and hype by a group of authors of the book "Fake AI, pseudosicence, snake oil and hype":
[https://www.youtube.com/watch?v=w1f0Sj-st9g&ab_channel=OxfordInternetInstitute%2CUniversityofOxford](https://www.youtube.com/watch?v=w1f0Sj-st9g&ab_channel=OxfordInternetInstitute%2CUniversityofOxford)
(1 hour 4 minutes)

In preparation for the discussion, break into groups of 4 people each and discuss the following questions:

* What is AI snake oil? How would you define it for yourselves?
* What are the signs of AI snake oil? How can you spot them?
* How do you draw the line between legitimate claims of contributions of AI/ML/data science methods to a marketable product (e.g., a software system), and the AI snake oil-style claims?
* What do you feel are the obligations of data scientists/ML engineers w.r.t. to flawed AI claims made about their work by others?
* Where is the boundary between harmless and harmful when it comes down to flawed AI claims?

In class, we will discuss each question in turn, each group is expected to have a summary of thoughts on each question prepared for sharing with the rest of the Fellowship.

### Week 5: February 8

In this next exercise you'll be working with a team, again, to analyze some data in an attempt to do some classification. Please read the instructions and access the data at the following link, and come prepared to next week's class:

[https://drive.google.com/drive/folders/1vXFloq65bmXzwWfB-K6VMJtnWbRy52I3](https://drive.google.com/drive/folders/1vXFloq65bmXzwWfB-K6VMJtnWbRy52I3)

### Week 4: February 1

In the next week, we will discuss tooling.

You need to pick a partner to research one of two technologies for data science: R or Python. Before class make sure you know which tool you're researching and that the assignments are balanced across all pairs of students.

The R group will research the advantages of:

* R
* R Markdown

The Python group will research the advantages of:

* Python
* Jupyter notebooks

Come prepared to discuss and debate the advantages of your assigned technology.

### Week 3: January 25

By this class, in your same groups of three from the activity on January 18, you should pick two data science tools from the following list to compare and contrast with respect to **reproducibility**. What are the pros? What are the cons? Is one of them clearly better than the other? Why?

Come to class prepared to give a 5-minute presentation on what you come up with.

* RStudio

* PyCharm

* Jupyter

* Google Colab

* Amazon Web Services

* Google Docs

* Github

* GitLab

* Slack

* Dropbox

* Tableau

* LaTeX

* Microsoft Office

* RMarkdown

### Week 2: January 18

Our first unit is on **reproducibility**. Please read the following before this class and come prepared to discuss them both in terms of their content and how you feel they relate to your experiences and knowledge of data science:

- [https://www.nature.com/articles/533452a](https://www.nature.com/articles/533452a)

- [https://www.vox.com/future-perfect/21504366/science-replication-crisis-peer-review-statistics](https://www.vox.com/future-perfect/21504366/science-replication-crisis-peer-review-statistics)

- [https://arxiv.org/pdf/2011.10098.pdf](https://arxiv.org/pdf/2011.10098.pdf)

**Please don't look at the following docs until class today!**

Group 1: [https://docs.google.com/document/d/1zlgi44LB8L8-5-gCTknCy54pKT_BjaqAVf7CoNvBIIU/edit?usp=sharing](https://docs.google.com/document/d/1zlgi44LB8L8-5-gCTknCy54pKT_BjaqAVf7CoNvBIIU/edit?usp=sharing)

Group 2: [https://docs.google.com/document/d/1PsQwkE8OoAg9h7Q8LP_DZ135U5Z29hEd7lk7fUJCfd0/edit?usp=sharing](https://docs.google.com/document/d/1PsQwkE8OoAg9h7Q8LP_DZ135U5Z29hEd7lk7fUJCfd0/edit?usp=sharing)

### Week 1: January 11

## Fall 2022

The theme of the readings for Fall 2022 is **the past**.

### Week 1: September 21

### Week 2: September 28

Hypothesis testing is a core part of many statistics classes. But where did the ideas such as the p-value, Type I error, and power come from? This reading reviews the turbulent history of hypothesis testing in the 20th century.

#### Required Reading:

- [Chapters 10 and 11](http://dlsun.github.io/ds-seminar/readings/LadyTastingTea-HypothesisTesting.pdf) from David Salsburg (2001). _The lady tasting tea: How statistics revolutionized science in the twentieth century_. Macmillan.

#### Additional Resources:

- Erich Lehmann (1993). [The Fisher, Neyman-Pearson Theories of Testing Hypotheses: One Theory or Two?](https://www.jstor.org/stable/2291263). (You should be able to download a PDF when you are on the Cal Poly network or VPN.)
- Erich Lehmann (2011). [Fisher, Neyman, and the Creation of Classical Statistics](https://link.springer.com/book/10.1007/978-1-4419-9500-1).
- [Oral History Interviews with David Blackwell](https://www.youtube.com/watch?v=Xo_YYxsFF6Y&list=PLCwE4GdJdVRIU1j2-nzpxOIi3XSNEZ3qv) (Youtube playlist).

#### Assignment:

In your assigned group of 6 students:
- Pair 1 should prepare slides discussing Fisher's contributions to hypothesis testing.
- Pair 2 should prepare slides discussing Neyman's (and Pearson's) contributions to hypothesis testing.
- Pair 3 should prepare slides comparing and contrasting the two approaches.

### Week 3: October 5

In the early to mid 1900s, the field of eugenics - the idea that some groups or people are inherently genetically inferior - was a mainstream and well-respected scientific pursuit.  Many of the foundational ideas of classic statistics were developed in conjunction with eugenics applications.  In the modern era, now that these ideas have been rejected as racist/classist/etc, how should we regard the influential people and ideas that came out of that movement?

#### Required Reading:

- [This twitter thread](https://threadreaderapp.com/thread/1268392721275744256.html) by famous statistician Daniela Witten, which initiated a change to a major statistics award.
- [Scientific Priestcraft](https://github.com/dlsun/ds-seminar/blob/master/readings/Superior_Ch3.pdf), Chapter 3 of "Superior: The Return of Race Science" by Angela Saini.

#### Assignment:

We ask you to think carefully about the practice of re-contextualizing scientific contributions in light of modern ethics.  Questions to consider:

- Does removing accolates like the Fisher Prize harm the target and/or his family?  Should the scientific contributions be considered in isolation, and honored, regardless of what else the individual did?
- Does this approach truly create a more welcoming/diverse scientific community?  Or does it discourage or hinder others from contributing to scientific progress, for fear of personal scrutiny?
- Does it remove objectivity from statistical methodology?
- Does it help us prevent similar mistakes in the future?

In your assigned group of 6 students:
- Pair 1 should track down more examples of events like the Fisher Prize renaming: Can you find historical figures related to data science whose ethics are currently in question?  Can you find examples of honors or accolades being removed from these people (or discussions suggesting such)? 
- Pair 2 should collect, summarize, and present arguments **against** re-contextualizing scientific contributions in light of modern ethics.     
- Pair 3 should collect, summarize, and present arguments **for** re-contextualizing scientific contributions in light of modern ethics.

### Week 4: October 12

We will look at the Frequentist vs. Bayes debate! Not only does this debate pertain to how you think and do your statistics and data science, but also to some of your ways of thinking every day! Please come prepared to defend both, although we want you will be asked to take a side in class.

#### Required Reading:

- New York Times Article: [The Odds, Continually Updated](readings/The%20Odds,%20Continually%20Updated%20-%20The%20New%20York%20Times.pdf)
- [Frequentist and Bayesian Approaches in Statistics](https://www.probabilisticworld.com/frequentist-bayesian-approaches-inferential-statistics)
- Efron, B. (2005). [Bayesians, frequentists, and scientists](https://dlsun.github.io/ds-seminar/readings/Bayesians,%20Frequentists,%20and%20Scientists.pdf). _Journal of the American Statistical Association_, 100(469), 1-5.
- [The Boxer, the Wrestler, and the Coin Flip: A Paradox of Robust Bayesian Inference and Belief Functions](http://www.stat.columbia.edu/~gelman/research/published/augie4.pdf) Andrew Gelman, The American Statistician, May 2006, Vol. 60, No. 2
- xkcd comic on [Frequentists vs. Bayesians](https://xkcd.com/1132/)

Here are some additional readings that might be of interest.

- MIT Lecture Notes: [Comparison of frequentist and Bayesian inference](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/readings/MIT18_05S14_Reading20.pdf).
- Efron, B. (1986). [Why isn't everyone a Bayesian?](https://dlsun.github.io/ds-seminar/readings/Why%20Isn't%20Everyone%20a%20Bayesian.pdf) _The American Statistician_, 40(1), 1-5.
- Andrew Gelman's blog post: [Why I Don't Like Bayesian Statistics](https://statmodeling.stat.columbia.edu/2008/04/01/problems_with_b/). (This is an April Fools' Joke written by a famous Bayesian statistician. However, it contains some good ideas.)

#### Assignment:

We ask you to think carefully about these two sides: Frequentist and Bayes.  Questions to consider:

- What are the strengths and weaknesses of each?
- Is it possible be a little bit of both? Why or why not?
- Think about your own beliefs about how probability and the likelihood of events work. In your day-to-day life (when not doing statistics or data science), do you tend to be more frequentist or bayesian? 

In your assigned group of 6 students:
- Pair 1 should organize and present the strengths of the Frequentist side and the weaknesses of the Bayesian side, as they pertain to statistics and data science work.
- Pair 2 should organize and present the strengths of the Bayesian side and the weaknesses of the Frequentist side, as they pertain to statistics and data science work.     
- Pair 3 should comment on how these two sides pertain to day-to-day life, and whether your position on them in this context should be related to your position on them in the context of your work. Be sure to think carefully and thoroughly here. Your comments might also include similarities between the two sides in certain situations. 

### Week 5: October 19

We will read a classic paper by Leo Breiman entitled "Statistical Modeling: The Two Cultures."   The PDF linked below also contains comments by leading statisticians and data scientists which will give you more ideas as you prepare your presentations.

#### Required Reading:

- Leo Breiman: [Statistical Modeling: The Two Cultures (with comments and a rejoinder by the author)](readings/breiman.pdf)

This paper by Efron can be seen as an update to Breiman's paper 20 years later -- it is not required reading but might be interesting for you to read over:

- Efron, B. (2020). [Prediction, Estimation, and Attribution](https://www.tandfonline.com/doi/full/10.1080/01621459.2020.1762613) _Journal of the American Statistical Association_.

#### Assignment:

In your assigned group of 6 students:
- Pair 1 should organize and present the strengths of the "data modeling" culture.
- Pair 2 should organize and present the strengths of the "algorithmic modeling" culture.
- Pair 3 should compare and constrast the two cultures.

### Week 6: October 26

We will discuss the past and future of Artificial Intelligence (AI). 

#### Required Reading:

- [Deep Learning's Diminish Returns](https://spectrum.ieee.org/deep-learning-computational-cost)
- [Probability of an Approaching AI Winter](https://towardsdatascience.com/probability-of-an-approaching-ai-winter-c2d818fb338a)


#### Assignment:

In your assigned group of 6 students: 
- Pair 1 should review the two papers.
- Pair 2 should make the argument why AI is the best thing since peanut butter and jelly and why investment in AI will keep growing.
- Pair 3 should make the argument that history will repeat itself, reality will crush expectations, and we will head for another AI winter.


### Week 7: November 2

We are starting a three-week stretch devoted to the ideas and technologies behind working with big data. Our first discussion is about relational databases, their history and their role in bringing forth our ability to work with large quantities of data.  To that end, you will read two sets of articles.

The first set of articles gives you some historic perspective on the development of the **relational data model** and **relational databases**. The articles in this set are:

- [E.F. Codd. A Relational Model of Data For Large Shared Data Banks, Communications of the ACM, June 1970] ( https://www.seas.upenn.edu/~zives/03f/cis550/codd.pdf)
- [E.F. Codd. The 12 Rules, (excert from "Is your database fully relational?", Computerworld, Oct 1985, reprinted](https://reldb.org/c/index.php/twelve-rules/)
- [Important Papers: Codd and the Relational Model. Two Bit History blog, Dec 2017](https://twobithistory.org/2017/12/29/codd-relational-model.html)

The Codd papers provide historic descriptions of the ideas behind the modern relational databases. The blog post puts some of the information contained in these papers in the overall context.

The second set of papers comes from a sequence of meetings conducted by the database research and industry community over the course of the late 20th and early 21st century. The meetings served as the community reflection points on the progress of the field of relational databases (and the field of databases in general) over the years. They also attempted to identify future challenges that the database technology and the database community needed to meet. The papers are co-authored by who's who in the area of database management systems.  The papers in this series are:

- [Erich Neuhold and Michael Stonebreaker Future Directions in DBMS Research, 1988](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/Stonebraker88.pdf)
- [A. Silberschatz, M. Stonebraker, J. Ullman (Eds.), Database Research: Achievements and Opportunities into the 21st Century, 1995](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/DB-research1995.pdf)
- [A. Silberschatz, S. Zdonik et al, Strategic Directions in Database Systems - Breaking out of the Box, 1996](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/StrategicDirections.pdf)
- [P. Bernstein et al., The Asilomar Report on Database Research, 1998](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/Asilomar_DB_98.pdf)
- [S. Abiteboul et al., The Lowell Database Research Self Assessment, 2003](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/lowell-report2005.pdf)
- [R. Agrawal et al., The Claremont Report on Database Research, Communications of the ACM 2009](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/claremont-report2009.pdf)
- [D. Agrawal, Challenges and Opportunities with Big Data, 2012](http://users.csc.calpoly.edu/~dekhtyar/560-Fall2012/papers/bigdatawhitepaper.pdf)

**This is a lot of reading. Please, read the instructions below carefully.**

The roles for this week's assignment are:

- **Role 1: Archeologists.** Students in this role will present information about the development the ideas behind modern (relational) database management systems and will discuss the importance of these ideas to today's data science.
- **Role 2: Supporters.** Students in this role will discuss what the database community _got right_ about its challenges and the problems that it needs to tackle in a modern world.
- **Role 3: Detractors.** Students in this role will discuss where the database community _missed_. What errors of omission and commission did the DB community commit? (Errors of omisison - something important about today's world of working with data, that the community missed. Errors of commission - something the DB community thought would be a big challenge, that was not).

### Week 8: November 9

We will discuss the rise and "fall" of Hadoop... and future of Hadoop. 

#### Required Reading:
Everyone should read in detail the following:

- [Background on CAP Theorem](https://en.wikipedia.org/wiki/CAP_theorem)
- [Google's MapReduce Paper](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
- [Hadoop: The Chronicle of an Expected Decline](https://www.singlestore.com/blog/hadoop-the-chronicle-of-an-expected-decline/)

#### Assignment:
The "decline" of Hadoop is documented, and so it is not my intention to have you discuss why this happened. It is an interesting topic but not our focus. I'll share a bit of my own experiences with Hadoop at the beginning of seminar since it came about during my graduate school days, and I've been along for the ride ever since. 

In your assigned group of 6 students: 
- Pair 1 should provide summaries of the CAP Theorem, MapReduce Paper, and the blog style article.
- Pair 2 should discuss how Hadoop can be thrive as expectations and the technology mature (i.e., in a plateau of productivity phase). Specifically, they should focus on explaining and expanding on the third article's optimism for Hadoop. For example, the authors mention technologies maturing around Hadoop: optimized data formats (ORC, Parquet) and query engines (Impala, Presto, Dremel). This pair should also discuss and expand upon the emerging best practices, and should make a general case for the long-term viability of Hadoop ecosystem.
- Pair 3 should discuss and expand upon why the third article's optimism for Hadoop is incorrect. They likewise should go through the article and prepare specific counterpoints to the author's claims of a "plateau of productivity" future for Hadoop.


### Week 9: November 16
Everyone needs to read the following:
- [A brief History of the Internet](https://dl.acm.org/doi/pdf/10.1145/1629607.1629613)
- [What is Web 2.0?](https://www.oreilly.com/pub/a/web2/archive/what-is-web-20.html) (make sure to read all the pages)
- [Semantic web](https://en.wikipedia.org/wiki/Semantic_Web)
- [Chicken Farms on the Semantic Web](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4445616&casa_token=rQj24Wp1StkAAAAA:Z6z7-0ehk4PFab16P8LDUh2yoN53kPykBl7s9o7or4kQ7Nrw2f02kubxHFxHnmjjTKdDYvOkYw&tag=1)

In your assigned group of 6:
- Pair 1 presents fundamental forces (social, economical, political) that were crucial to development of the World Wide Web
- Pair 2 explain the differences between Web 1.0 and Web 2.0. Use examples and products from your own life and interaction. Name the ways in which current technologies exptend from Web 2.0 enabling concepts. 
- Pair 3 explain the semantic Web. How are things likely to change based on this in the near future? Use examples.

Everyone: be sure to look up terms and products that you're reading about which you may not be familiar with (too old or discontinued). Teams need to be explain the terms in the papers that have to do with their subject, if asked during their presentations.
