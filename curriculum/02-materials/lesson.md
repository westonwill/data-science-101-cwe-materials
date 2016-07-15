---
title: Data Science 101
duration: "2:50"
creator:
    name: J Rogel-Salazar
    city: LDN
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Data Science 101

### LEARNING OBJECTIVES
*After this lesson, you will be able to:*

- Explain the field of data science, defining common roles, benefits, and trends.
- Explore some popular tools and resources to visualize,  analyze, and model data.
- Recognize the different types of problems that can be solved by data scientists.
- Apply the data science workflow to provide real world recommendations.
- Create a custom learning plan to help you continue to build fundamental data science skills after this workshop.

### STUDENT PRE-WORK
*Before this lesson, you will need to:*
- Bring a laptop with [Anaconda](https://www.continuum.io/downloads) installed. Scroll to your operating system version and click on the install button for ***Anaconda with Python 2.7***. Note: we'll be using Python version 2.7 in this workshop.
- We will be using Jupyter Notebooks as the main IDE for the workshop. If you are using Anaconda (with Win, Mac or Linux) you are ready to go. 

### INSTRUCTOR PREP
*Before this lesson, instructors will need to:*

- Review & modify lesson plan & slide deck as needed
- Write learning objectives & relevant information on board
- Review student roster

### WORKSHOP AGENDA
| TIMING  | TYPE  | TOPIC  |
|:-:|---|---|
| 10 min  | [Opening](#opening)  | Greetings + The GA Experience  |
| 15 min  | [Introduction](#intro1)   | Why Data Science? What Can Data Science Do For Me? |
| 15 min  | [Demo](#demo1)  | Visualizing the Data Science Workflow  |
| 20 min  | [Guided Practice](#guided-practice1)  | Exploring the Data Science Toolkit |
| 20 min  | [Independent Practice](#ind-practice1)  | Analyze Some Data! |
| 5-10 min  | BREAK  |   |
| 15 min  | [Introduction](#intro2)   | What's an Algorithm, Anyway? |
| 15 min  | [Demo](#demo2)  | Algorithms in Action  |
| 20 min  | [Guided Practice](#guided-practice2)  | Thinking Logically  |
| 20 min  | [Independent Practice](#ind-practice2)  | Data Science Case Study |
| 10 min  | [Conclusion](#conclusion) | Review + Recap |
| 10 min  | [Takeaways](#takeaway) | Learning Plan + Q&A |

---

<a name="opening"></a>
## Opening (10 mins)

> Note: Let people know where restrooms and kitchen are located, as needed.

- Welcome the students and find out about their interests
- Review current lesson objectives

#### Instructor Bio

Welcome to Data Science 101! Here's a bit about me:
> Provide your name and brief bio, including: your background in data science, any experience you've had with GA, and one "fun fact" about yourself.

#### Introduce Yourselves

Before we dive in, a bit about you!

> Have students introduce themselves: name, what brings them to GA (ask for their current career & any specific goals), & one "fun fact".

> **Example Exercise**: *Have students write these on google doc or google poll. Instructor can briefly demonstrate data science workflow by categorizing data, merging into CSV file,  pulling out features, etc.*


#### Our Expectations

- You're ready to take charge of your learning experience.
- You're curious and excited about data science!
- You've installed [Anaconda with Python 2.7](https://www.continuum.io/downloads).

> Instructor Note: Check that all laptops have a *Python 2.7* distribution. [Anaconda is the recommended distro](https://www.continuum.io/downloads).


#### Our Objectives

> Note: Write workshop objectives on board before class

- Why this topic matters (general relevance)
- Why this topic rocks (interest/hook)

> Note: Tailor these 2 points to student interests. Relate to their career info & goals students described during attendance.


***

<a name="intro1"></a>
## Introduction: Why Data Science? What Can Data Science Do For Me? (15 mins)

**Data Science**: A set of tools and techniques used to extract useful information from data.

- An interdisciplinary, problem-solving oriented subject.
- The application of scientific techniques to practical problems.
- A rapidly growing field.

#### Qualities of a data scientist

- Programming skills
- Maths and Stats knowledge
- Business acumen (substantive expertise)
- Plus: Communication skills

**Check:** 

- What do you think are the most important qualities for a data scientist?
- Can you think of any other quality/skill we have not mentioned?

- What is your field of expertise?
- Do you use tools such as Excel, Stata, R, Python?
- Where are you in the intersection of these skills?

> Instructor Note: The discussion for this part of the lesson can be used to prompt the students to self-assess those areas where they are stronger/weaker. This will help with creating their "Learning Plan".

#### What can data science do for me?

* Ask good questions: what is what…? …we don’t know?… we’d like to know?
* Define and test a hypothesis. Run experiments
* Scoop, scrap, sink and sample business relevant data
* Munge and wrestle data
* Visualize data
* Understand data relationships
* Tell the machine how to learn from data
* Create data products that deliver actionable insight
* Tell relevant business stories from data

***

<a name="demo1"></a>
## Demo: Visualizing the Data Science Workflow (15 mins)

Walk through the steps of the Data Science Workflow.

> Instructor Note: Make sure to emphasize that the workflow is an iterative process and not necessarily a linear one.

Data Science Workflow:

- Acquire
- Parse
- Filter
- Mine
- Represent
- Refine
- Interact

**Demo:** Ask the students to consider these steps in light of a real data science problem. For example:

_"What are the leading indicators that a user will make a new online purchase?"_


**Check:** By this point, students should be able to write out specific actions related to the steps in the data science workflow.

***

<a name="guided-practice1"></a>
## Guided Practice: Exploring the Data Science Toolkit (20 mins)

Using a sample dataset, demonstrate how to carry out descriptive analytics using the well-known `pandas` library.

See the proposed example in the [code](./code) section.

**Check:** Were students able to successfully solve the problem or complete the task?


***

<a name="ind-practice1"></a>
## Independent Practice: Analyze Some Data! (20 mins)

Use the lesson topic/skill to create a deliverable that meets certain criteria.

> Instructor Note: This can be a pair programming activity or done independently.

Using a second dataset, ask the students to carry out similar analysis to the one demonstrated in during the "Guided Practice".

See the proposed example in the [code](./code) section.

**Check:** Were students able to create the desired deliverable(s)? Did it meet all necessary requirements / constraints?


***

> **BREAK** (5-10 mins)

***

<a name="intro2"></a>
## Introduction: What's an Algorithm, Anyway? (15 mins)

> Instructor Note: Before re-starting the class, check for any questions the students may have about the first part of the workshop

*Algorithm*: A set of steps to accomplish a task.

Discussion: Ask students to list the steps they follow to achieve an every-day task, e.g. make cheese on toast, commute to work, make a cup of tea.

*Computer Science Algorithm*:

- Start with input data
- Do (complex) calculations
- Stop when the answer is found

Good algorithms are:

1. Correct
2. Efficient


***

<a name="demo2"></a>
## Demo: Algorithms in Action (15 mins)

Discuss a well-known computer science algorithm such as sorting. See the [Resources](#resources) Section for examples.

### Algorithms in the context of Machine Learning

Machine learning is a branch of artificial intelligence. It is concerned with the construction and study of systems that can learn from data.

The core of machine learning deals with representation and generalization.

- Representation – extracting structure from data
- Generalization – making predictions from data

**Machine learning problems**

- Supervised: Making predictions (generalization)
- Unsupervised: Extracting structure (representation)

***

<a name="guided-practice2"></a>
## Guided Practice: Thinking Logically (20 mins)

> Instructor Note: Run through the example with the students and ask them to draw a decision tree based on the  "business rules" below in plain English (you can also show pseudo-code).

### **EXAMPLE**

During a doctor's examination some patients show the following characteristics:

	X1: temperature
	X2: coughing
	X3: reddening throat

The doctor has the following outcomes for the patients:

	Y = {W1, W2, W3, W4, W5}
	W1: cold
	W2: quinsy
	W3: flu
	W4: pneumonia
	W5: healthy

It is required to find a model where `Y` depends on `X`. The rules below illustrate such a model:

1. If `X1 < 37` , `Y`="is health".2. If `X1 ∈ [37,38.5]` and `X3`="there is no reddening of throat", then `Y=`"cold";3. If `X1 ∈ [37,38.5]` and `X3=`"there is reddening of throat", then `Y=`"quinsy";4. If `X1 > 38.5` and `X2=`"there is no cough", then `Y=`"flu";5. If `X1 > 38.5` and `X2=`"there is cough", then `Y=`"pneumonia";

Any new (unseen) patient can now be diagnosed using these rules.

***

<a name="ind-practice2"></a>
## Independent Practice: Data Science Case Study (20 mins)

Using the dataset(s) from [Part 1 - Guided Practice](#guided-practice1) or [Part 1 - Independent Practice](#ind-practice1) implement a decision tree algorithm using scikit-learn.


***

<a name="conclusion"></a>
## Conclusion: Review + Recap Topics (10 mins)

> Review Deliverables

> Review Topics Covered

In this workshop, we've covered the following topics:

- Why data science?
- What can data science do for me?
- The data science worflow
- Analyse and visualise data using Python (pandas, matplotlib, NumPy, etc)
- Understand the role of algorithms and their relationship with machine learning
- Understand the main concepts behind a decision tree to make predictions

***

<a name="takeaway"></a>
## Takeways: Learning Plan + Q&A (10 mins)

#### What Should You Do Next?

Encourage the students to continue learning by producing a plan based on the skills discussed in [Part 1 - Introduction](#intro1).

Suggest sonme resources such as books, podcasts, GA courses, etc.

#### Q & A

> Instructor Notes: Encourage the students to share any thoughts or questions before closing the session.

***

<a name="resources"></a>
## ADDITIONAL RESOURCES
- [Sorting algorithms](https://www.toptal.com/developers/sorting-algorithms)
- [15 sorting algos in 6 min](https://www.youtube.com/watch?v=kPRA0W1kECg)
- [Decision trees in scikit-learn](http://scikit-learn.org/stable/modules/tree.html)
- [Decision trees tutorial](http://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/)
