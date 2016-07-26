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

- Review & modify lesson plan & slide deck
- Write learning objectives & relevant information on board
- Review student roster
- Prepare handout to distribute to students

### WORKSHOP AGENDA
| TIMING  | TYPE  | TOPIC  |
|:-:|---|---|
| 10 min  | [Opening](#opening)  | Greetings + The GA Experience  |
| 10 min  | [Introduction and Guided Practice](#intro1)   | Why Data Science? What Can Data Science Do For Me? |
| 5 min  | [Independent Practice](#ind-practice0)   | Data Science Skills|
| 20 min  | [Demo](#demo1)  | Visualizing the Data Science Workflow  |
| 20 min  | [Guided Practice](#guided-practice1)  | Exploring the Data Science Toolkit |
| 20 min  | [Independent Practice](#ind-practice1)  | Analyze Some Data! |
| 5 min  | BREAK  |   |
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

> **Example Exercise**: *Have students write these on a Google doc or in a Google poll. Instructor can briefly demonstrate data science workflow by categorizing data, merging into CSV file,  pulling out features, etc.*


#### Our Expectations

- You're ready to take charge of your learning experience.
- You're curious and excited about data science!
- You've installed [Anaconda with Python 2.7](https://www.continuum.io/downloads).

> Instructor Note: Check that all laptops have a *Python 2.7* distribution. [Anaconda is the recommended distro](https://www.continuum.io/downloads).


#### Our Objectives

> Note: Write workshop objectives on board before class


* What we’ll cover:
	* Why Data Science & what it can do for me?
	* Data Science skills
	* Explore the Data Science Toolkit
	* Analyze data
	* Algorithms in action
* Why this topic matters:
	* Data Science is a sought-after skill 
	* Using Python due to its increased popularity and simplicity
* Why this topic rocks:
	* Data Science opens up a door to a variety of opportunities
	* Remember it has been dubbed the “Sexiest job of the 21st century”! 

> Note: Tailor these points to student interests. Relate to their career info & goals students described during attendance.


***

<a name="intro1"></a>
## Introduction: Why Data Science? What Can Data Science Do For Me? (15 mins - 5 min + 10 min)

**Data Science**: A set of tools and techniques used to extract useful information from data.

- An interdisciplinary, problem-solving oriented subject.
- The application of scientific techniques to practical problems.
- A rapidly growing field.

### Guided Practice: Qualities of a data scientist

- Programming skills
- Math and statistics knowledge
- Business acumen (substantive expertise)
- Plus: Communication skills

**Your Turn:**
Let's talk through the following questions as a group: 

- What do you think are the most important qualities for a data scientist?
- Can you think of any other quality/skill we have not mentioned?

- What is your field of expertise?
- Do you use tools such as Excel, Stata, R, or Python?
- Where are you in the intersection of these skills?

> Instructor Note: The discussion for this part of the lesson can be used to prompt the students to self-assess those areas where they are stronger/weaker. This will help with creating their "Learning Plan".

#### What can data science do for me?

* Ask good questions: 
	* What is required?
	* How are results evaluated? (measures of success)
	* What do we currently know? (existing data)
	* What has happened? (descriptive analytics)
	* What will happen (if)? (predictive analytics)
	* What to do to achieve what we require? (insight)
* Define and test a hypothesis/run experiments
* Scoop, scrap, sink, and sample business relevant data
* Manipulate, sanitize, and wrestle data
* Visualize data
* Understand data relationships
* Tell the machine how to learn from data
* Create data products that deliver actionable insight
* Tell relevant business stories from data
 
***

<a name="ind-practice0"></a>
## Independent Practice: Data Science Skills

Create a table for the qualities of a data scientist and then rate yourself on each of these skills on a scale from 1-10. 

We will then use the data to show how simple statistics in action are part of the data science workflow.

| Quality/Skill | Student 1 | Student 2 | ... | Average| 
|:-:|---|---|---|---|
| Programming | score 1 | score 2 | ... | Average| 
| Math | score 1 | score 2 | ... | Average| 
| Statistics | score 1 | score 2 | ... | Average| 

> Instructor Note:
> 
> Check: With one minute left, have one student share their answer with the class.

***

<a name="demo1"></a>
## Demo: Visualizing the Data Science Workflow (20 mins)

Walk through the steps of the Data Science Workflow.

> Instructor Note: 
> 
> Make sure to emphasize that the workflow is an iterative process and not necessarily a linear one.

Data Science Workflow:

* Identify the problem
	* Identify business/product objectives
	* Identify and hypothesize goals and criteria for success
	* Create a set of questions for identifying correct dataset
* Acquire the data
	* Identify the "right" dataset(s)
	* Import data and set up local or remote data structure
	* Determine most appropriate tools to work with data
* Parse the data
	* Read any documentation provided with the data
	* Perform exploratory data analysis
	* Verify the quality of the data
* Mine the data
	* Determine sampling methodology and sample data
	* Format, clean, slice and combine data (in Python)
	* Create necessary derived columns from the data (new data)
* Refine the data
	* Identify trends and outliers
	* Apply descriptive and inferential stats
	* Document and transform data
* Build a data model
	* Select appropriate model
	* Build model
	* Evaluate and refine model
* Present results
	*  Summarize with narrative, storytelling techniques
	*  Present limitations and assumptions of your analysis
	*  Identify follow up issues for future analysis
*  Deploy and validate
	*  Write unit tests and documentation
	*  Deploy stable production-ready code
	*  Retrain and validate models over time

### Demo: Visualizing the Data Science Workflow

**_"What are the leading indicators that a user will make a new online purchase?"_** 

You are a junior data scientist at Amazon. Your boss asks you about the leading indicators that a user will make a new online purchase. How would you go about solving this question?

- **Acquire Data**: What could we do first here? What are some considerations we should make?
- **Parse Data**: What do you think this means? Why is it important?
- **Mine and Refine**: Is the raw data enough? What calculations/transformation do you recommend doing? How do you determine the presence of outliers?
- **Data model**: What attributes would you include in the modelling stage? How do you know if the model is performing well?
- **Results**: Who is your audience? What is the best way to present your results?

Take 10 minutes to work with the person next to you and talk through answers to these questions. Then, we'll take 5 minutes at the end of this period to come back and discuss.


> Instructor Note:
> 
> **Suggested Answer**
> 
> You can walk the student through the example all together in class. Use the discussion points below. 
> 
> **Check:** By this point, students should be able to understand specific actions related to the steps in the data science workflow. To assess this, you can then break the class into group and tackle a similar problem in their groups and share their results with the class:
> 
>  * Collect data around user retention, user actions within the product, potentially find data outside of company
> * Extract aggregated values from raw data
> 	* How many times did a user share through Facebook within a week? A month?
> 	* How often did they open up our emails?
> * Examine data to find common distributions and correlations
> * Extract new meaning to predict if user would purchase again
>
>  * Share results via an interactive presentation with a Jupyter Notebook (and probably also go back to the drawing board)

***

<a name="guided-practice1"></a>
## Guided Practice: Exploring the Data Science Toolkit (20 mins)

**Packages**

Libraries of code written to solve particular set of problems

In Python there are many related packages relevant to data science: pandas, Scikit-learn, NumPy, etc. Some widely-used packages include

* pandas
	* Ever used Excel? How would you like working with data structured in a similar way, but without the irritation of formatting, long formula, and better graphics? Well, use *pandas*.
* SciPy/NumPy
	* Does your application require the use of advanced mathematical functions or numerical operations with arrays, vectors, or matrices? Try *SciPy* (scientific python) and *NumPy* (numerical python).
* Scikit-Learn
	* Are you interested in using python in a data science workflow and exploiting the use of machine learning in your applications? Look no further than *Scikit-learn*.
* matplotlib
	* Are you tired of the boring-looking charts produced with Excel? Are you bored of looking for the right menu to move a label in your plot? Take a look at the visuals offered by *matplotlib*.
* statsmodels: statistical tests
	* Is your boss asking about significance testing and confidence intervals? Are you interested in descriptive statistics, statistical tests, plotting functions, and result statistics? Well *statsmodels* offers you that and more.
* Beautiful Soup
	* All the data you require is available freely on the web but there is no download button and *you* need to scrape the website. You can extract data from HTML using *Beautiful soup*.

In this guided practice we are using a sample dataset; demonstrate how to carry out descriptive analytics using the `pandas` library we introduced above.

> Instructor Note:
> 
> IDE to be used
> 
> You can show the following commands and concepts using a python/ipython shell. We encourage you to use a **Jupyter notebook** in the second part of the workshop.

### Instructions for students
We recommend using a Jupyter notebook for this guided practice. This makes it easier for all as it is homogenous for various environments (mac, win, linux).

> Instructor Note:
> 
> If you use Dropbox to get the material to your students follow these steps:

The Dropbox link provided has a Zip file with the materials for the class. 

1. Unzip the file downloaded in a known location in your file system
2. Locate the file called [DataScience101_Part1_GuidedPractice.ipynb](./code/DataScience101_Part1_GuidedPractice.ipynb) 
3. Open Jupyter: Open a terminal 

	- **Mac**: Using spotlight search for "Terminal" 
	- **Windows**: Click the "Start" button and type "cmd"
	- In the terminal type: `jupyter notebook`
	
4. Navigate to the  folder where you have saved the file in step 1
5. Open the file from the Jupyter interface
6. Voilà, you are ready to type the commands we will cover below

> Instructor Note:
> 
> If you use GitHub to get the material to your students follow these steps:

To get a hold of the starter code, you'll need to download these materials.

1. First, visit this page: [https://github.com/generalassembly-studio/data-science-101-cwe-materials](https://github.com/generalassembly-studio/data-science-101-cwe-materials)
2. Then, click on the "Clone or Download" button, and click "Download ZIP"
3. Unzip the file downloaded in a known location in your file system
4. Locate the file called [DataScience101_Part1_GuidedPractice.ipynb](./code/DataScience101_Part1_GuidedPractice.ipynb) 
5. Open Jupyter: Open a terminal 

	- **Mac**: Using spotlight search for "Terminal" 
	- **Windows**: Click the "Start" button and type "cmd"
	- In the terminal type: `jupyter notebook`
	
6. Navigate to the  folder where you have saved the file in step 3
7. Open the file from the Jupyter interface
8. Voilà, you are ready to type the commands we will cover below

***

<a name="ind-practice1"></a>
## Independent Practice: Analyze Some Data! (20 mins)
> Instructor Note: 
> 
> Using a second dataset, ask the students to carry out similar analysis to the one demonstrated during the "Guided Practice".
> 
> This can be a pair programming activity or done independently depending on the size of the class and on students' abilities. 
> 
> In either case, make sure that discussion of the results is done with the entire class.
> 

# Now You Try!

You are a business intelligence manager at a fast moving startup that deals with flowers. You need to analyze some data for iris flowers of three different species.

You have received a sample data set with typical measures for the following three species for iris:

- Verginica
- Setosa
- Versicolor

Let us use Python to perform some analytics that will help us differentiate the three species later on in the modelling part of our workflow.

### Instructions for students

> Instructor Note:
> 
> If you use Dropbox to get the material to your students follow these steps:

The Dropbox link provided has a Zip file with the materials for the class. 

1. Navigate to the location where you unzipped the file from the Dropbox link
2. Locate the file called [DataScience101_Part1_IndPractice.ipynb](./code/DataScience101_Part1_IndPractice.ipynb)
3. Open Jupyter: Open a terminal 

	- **Mac**: Using spotlight search for "Terminal" 
	- **Windows**: Click the "Start" button and type "cmd"
	- In the terminal type: `jupyter notebook`
	
4. Navigate to the  folder where you have saved the file in step 2
5. Open the file from the Jupyter interface
6. Voilà, you are ready to type the commands we will cover below

Instructor Note:
> 
> If you use GitHub to get the material to your students follow these steps:

To get a hold of the starter code, you'll need to download these materials.

1. Navigate to the location where you cloned or downloaded the GitHub repo for the class
2. Locate the file called [[DataScience101_Part1_IndPractice.ipynb](./code/DataScience101_Part1_IndPractice.ipynb)
3. Open Jupyter: Open a terminal 

	- **Mac**: Using spotlight search for "Terminal" 
	- **Windows**: Click the "Start" button and type "cmd"
	- In the terminal type: `jupyter notebook`
	
4. Navigate to the folder where you have saved the file in step 1
5. Open the file from the Jupyter interface
6. Voilà, you are ready to type the commands we will cover below

> 
> Instructor Note: 
> 
> **Solutions**
> 
> You can find a Jupyter notebook with solutions to the independent practice exercise in [DataScience101_Part1_IndPractice_Solutions.ipynb](./code/DataScience101_Part1_IndPractice_Solutions.ipynb)

***

> **BREAK** (5 mins)

***

<a name="intro2"></a>
## Introduction: What's an Algorithm, Anyway? (15 mins)

> Instructor Note: 
> 
> Before re-starting the class, check for any questions the students may have about the first part of the workshop.
> 

# Discussion

###_**What comes to mind when you hear the word algorithm?**_

> Instructor Note:
> 
> Amass a list of different descriptions from students.
> Use that to lead to the information below.

*Algorithm*: A set of steps to accomplish a task.

Algorithms need to have their steps in the right order.

Think about an algorithm for getting dressed in the morning. 

- What if you put on your coat before your shirt? 
	- Your shirt would be on top of your coat and that would be silly! 

When you write an algorithm the order of the instructions is very important.

In computer science, algorithms are a formal way of describing very precisely how to carry out certain computational tasks. 

Computers are very good at carrying out series of precisely defined instructions, and algorithms can be seen as formal description of computer programs. 

#### Criteria of a good algorithm

* An algorithm is an **unambiguous description** that makes clear what has to be implemented. 
	* In a recipe, a step such as “Bake until done” is ambiguous because it doesn’t explain what “done” means.
	* A more explicit description such as “Bake until the cheese begins to bubble” is better. 
	* In a computational algorithm, a step such as “Choose a large number” is vague: what is large? 1 million, 1 billion, or 100? Does the number have to be different each time, or can the same number be used on every run?
* An algorithm expects a defined set of **inputs**. For example, it might require two numbers where both numbers are greater than zero. Or it might require a word, or a list of zero or more numbers.
* An algorithm produces a defined set of **outputs**. It might output the larger of the two numbers, an all-uppercase version of a word, or a sorted version of the list of numbers.
* An algorithm is **guaranteed to terminate** and **produce a result**, always stopping after a finite time. If an algorithm could potentially run forever, it wouldn’t be very useful because you might never get an answer.

We can condense some of this information as follows:

```
Data In -> Change -> New Data Out
```

### Discussion

> Instructor Note:
> 
> Divide the class in three groups and ask students to list the steps they follow to achieve an every-day task, e.g. making buttered toast, commuting to work, making a cup of coffee.
> Student need to break down steps into the smallest, discrete, sequential items, etc.

What is the algorithm for:

- Making buttered toast
- Commuting to work
- Making a cup of coffee

Break down the steps into the smallest discrete, sequential items and think of the logical order in which things have to be done to achieve the task.


***

<a name="demo2"></a>
## Demo: Algorithms in Action (15 mins)

Let us see how we can write a useful algorithm in python.

#### An Example Algorithm

**Problem**: Given a list of positive numbers, return the largest number on the list.

**Inputs**: A list L of positive numbers. 

This list must contain at least one number. (Asking for the largest number in a list of no numbers is not a meaningful question.)

**Outputs**: A number n, which will be the largest number of the list.

Algorithm:

1. Set the variable `max` to 0.
2. For each number `x` in the list `L`, compare it to `max`. If `x` is larger, set `max` to `x`.
3. `max` is now set to the largest number in the list.

Here is the Python implementation:

```python
def find_max(L):
    max = 0
    for x in L:
        if x > max:
            max = x
    return max
```

#### Discussion

Does the algorithm above meet the criteria for being an algorithm?

<details>
<summary>
* Is it unambiguous? 
</summary>
Yes. Each step of the algorithm consists of primitive operations, and translating each step into Python code is very easy.
</details>

<details>
<summary>
* Does it have defined inputs and outputs? 
</summary>
Yes.
</details>

<details>
<summary>
* Is it guaranteed to terminate? 
</summary>
Yes. The list L is of finite length, so after looking at every element of the list the algorithm will stop.
</details>

<details>
<summary>
* Does it produce the correct result? 
</summary>
Yes. In a formal setting you would provide a careful proof of correctness. In the next section I’ll sketch a proof for an alternative solution to this problem.
</details>

### Algorithms in the context of Machine Learning

Machine learning is a branch of artificial intelligence. It is concerned with the construction and study of systems that can learn from data.

The core of machine learning deals with representation and generalization.

- Representation – extracting structure from data
- Generalization – making predictions from data

**Machine learning problems**

- **Supervised**: Making predictions (generalization)

For example, suppose you want to predict whether someone will make a purchase the week after they visit your portal. 

You have a set of data on previous customers, including age, interests, previous purchases, time of visit, etc. 

You know whether the previous customers made a purchase within a week of their last visit. So, the problem is combining all the existing data into a model that can predict whether a new person will make a purchase within a week.

You can then take action and make an offer, or recommend a product. 

Amazon, Netflix, and others do this based on the history of their existing customers.

- Some supervised learning algorithms include:
	- linear regression
	- decision trees 
	- neural networks 

- **Unsupervised**: Extracting structure (representation)

For example, suppose you want to understand your customer base so that you can produce appropriate segments that you can target with your next marketing campaign. You may not know what the main characteristics to use.

You have a set of data about your customers, including age, location, previous purchases, time of visit, etc. 

Based on these attributes you can find similarities and differences that provide groupings (segments) of customers.

You can then take action and make an offer, or recommend a product specifically to these segments.

- Some unsupervised learning algorithms include:
	- clustering 
	- anomaly detection
	- principal component analysis

***

<a name="guided-practice2"></a>
## Guided Practice: Thinking Logically (20 mins)

> Instructor Note: Run through the example with the students and ask them to draw a decision tree based on the  "business rules" below in plain English (you can also show pseudo-code).
> 

We just reviewed types of machine learning models at a high level. 

We mentioned decision trees in the context of supervised learning. 

- Do you remember what  a supervised learning model is again?
- Why are they called "trees"?


### **EXAMPLE**

During a doctor's examination some patients show the following characteristics:

	X1: temperature
	X2: coughing
	X3: reddening throat

The doctor has the following outcomes for the patients:

	Y = {W1, W2, W3, W4, W5}
	W1: cold
	W2: tonsillitis
	W3: flu
	W4: pneumonia
	W5: healthy

The doctor is required to find a diagnosis bases on the symptoms presented by the patient. 

In data science terms, the doctor requires a model where `Y` (the diagnosis) depends on `X` (the symptoms). 

The rules below illustrate such a model:

1. If `X1 < 37` , `Y`="is healthy".
2. If `X1` has values between `[37,38.5]` and `X3`="there is no reddening of throat", then `Y`="cold";
3. If `X1` has values between `[37,38.5]` and `X3`="there is reddening of throat", then `Y`="tonsillitis";
4. If `X1 > 38.5` and `X2`="there is no cough", then `Y=`"flu";
5. If `X1 > 38.5` and `X2`="there is cough", then `Y`="pneumonia";

Any new (unseen) patient can now be diagnosed using these rules.

***

<a name="ind-practice2"></a>
## Independent Practice: Data Science Case Study (20 mins)

> Instructor Note:
> 
> Activity
> 
> Using the dataset(s) from [Part 1 - Guided Practice](#guided-practice1) or [Part 1 - Independent Practice](#ind-practice1) implement a decision tree algorithm using scikit-learn.
> 
> Remind the students of that scikit-learn is, from the discussion from [Guided Practice](#guided-practice1).
> 
> Provide a copy of the notebook [DataScience101_Part2_DecisionTree.ipynb](./code/DataScience101_Part2_DecisionTree.ipynb) and the [Iris dataset](./code/data/iris.csv).
> 
> The notebook makes use of the Scikit-learn library. 
> We have not had an opportunity to demo the library or the decision tree model. 
> 
> Therefore, we suggest providing the complete notebook and let the students work in pairs to run and discuss the code.
> 
> Bring the class together to explain the code and allow for questions.


***

<a name="conclusion"></a>
## Conclusion: Review + Recap Topics (10 mins)

> Review Deliverables

> Review Topics Covered

In this workshop, we've covered the following topics:

- Why data science?
- What can data science do for me?
- The data science workflow
- Analyze and visualize data using Python (pandas, matplotlib, NumPy, etc.)
- Understand the role of algorithms and their relationship with machine learning
- Understand the main concepts behind a decision tree to make predictions

***

<a name="takeaway"></a>
## Takeaways: Learning Plan + Q&A (10 mins)

> Instructor Note:
> 
> Encourage the students to continue learning by producing a plan based on the skills discussed in [Part 1 - Introduction](#intro1).
> 
> Return to the student poll in the [Introduction](#intro1) and ask them what they want to do.
> 
> Suggest some resources such as books, podcasts, GA courses, etc.

### What Should You Do Next?

Remember the skills and qualities of a data scientist?

- Programming skills
- Math and statistics knowledge
- Business acumen (substantive expertise)
- Plus: Communication skills

Bearing in mind your self-assessment for these, what are you interested in learning more about and getting a deeper understanding of?

### Resources

- Books:
	- [**Data Analysis with Open Source Tools**, P. K. Jannert](https://www.amazon.com/Data-Analysis-Open-Source-Tools/dp/0596802358?ie=UTF8&camp=1789&creative=9325&creativeASIN=0596802358)
	- [**Data Science for Business**, F. Provost and T. Fawcett](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323?ie=UTF8&camp=1789&creative=9325&creativeASIN=1449361323)
	- [**Pattern Recognition and Machine Learning**,
C. Bishop](https://www.amazon.com/Pattern-Recognition-Learning-Information-Statistics/dp/0387310738?ie=UTF8&camp=1789&creative=9325&creativeASIN=0387310738)
	- [**Data Science and Analytics with Python**, J Rogel-Salazar](https://www.crcpress.com/Data-Science-and-Analytics-with-Python/Rogel-Salazar/p/book/9781498742092)
	- [An Introduction to Statistical Learning with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) (free PDF)
	* [Elements of Statistical Learning](http://www-stat.stanford.edu/~tibs/ElemStatLearn/) (free PDF)
	* [Think Stats](http://www.greenteapress.com/thinkstats/) (free PDF or HTML)
	* [Mining of Massive Datasets](http://www.mmds.org/) (free PDF)

- MOOCs
	- Andrew Ng's Machine Learning Class on Coursera [link](https://www.coursera.org/course/ml)
	- MIT's Artificial Intelligence course [link](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/)
	- Johns Hopkins' Data Analysis Methods [link](https://www.coursera.org/course/dataanalysis)
	- Cal Tech's Learning from Data course [link](http://work.caltech.edu/lectures.html)

- Blogs:
	- FiveThirtyEight [link](http://fivethirtyeight.com)
	- Data Science & Psychology [link](http://www.polipsych.com/)
	- Inherent Uncertainty [link](http://www.inherentuncertainty.org/)

- Twitter
	- Hillary Mason ([@hmason](https://twitter.com/hmason)): Data Scientist in Residence at Accel and Scientist Emeritus at bitly.
	- Dj Patil ([@dpatil](https://twitter.com/dpatil)): VP of Product at RelateIQ.
	- Jeff Hammerbacher ([@hackingdata](https://twitter.com/hackingdata)): Founder and Chief Scientist at Cloudera and Assistant Professor at the Icahn School of Medicine at Mount Sinai.
	- J Rogel-Salazar ([@quantum\_tunnel](https://twitter.com/quantum_tunnel)): Data scientist at IBM and GA instructor
	- Peter Skomoroch ([@peteskomoroch](https://twitter.com/peteskomoroch)): Equity Partner at Data Collective, former Principal Data Scientist at LinkedIn.
	- Drew Conway ([@drewconway](https://twitter.com/drewconway)): Head of Data at Project Florida


- Aggregators

	* [DataTau](http://www.datatau.com/): Like [Hacker News](https://news.ycombinator.com/), but for data
	* [MachineLearning on reddit](http://www.reddit.com/r/MachineLearning/): Very active subreddit
	* [Quora's Machine Learning section](http://www.quora.com/Machine-Learning): Lots of interesting Q&A
	* [Quora's Data Science topic FAQ](https://www.quora.com/What-is-the-Data-Science-topic-FAQ)
	* [KDnuggets](http://www.kdnuggets.com/): Data mining news, jobs, classes and more

- Other Resources

	* [Open Source Data Science Masters](https://github.com/datasciencemasters/go): Huge list of resources
	* [Data Science Trello Board](https://trello.com/b/rbpEfMld/data-science): Another list of resources
	* [The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/): Online guide to understanding Python and getting good at it
	* [Python Reference](https://github.com/rasbt/python_reference): Python tips, tutorials, and more
	* [videolectures.net](http://videolectures.net/Top/Computer_Science/): Tons of academic videos
	* [Metacademy](http://www.metacademy.org/list): Quick summary of many machine learning terms, with links to resources for learning more
	* [Terms in data science defined in one paragraph](https://github.com/rasbt/pattern_classification/blob/master/resources/data_glossary.md)

### Data Science at GA

At GA we offer a part time and immersive course on data science! 

Some of the topics covered include:

- linear and logistic regression
- decision trees
- natural language processing
- time series analysis, and more! 

However, to qualify for the course you'll need to brush up on some basic statistics and review python syntax fundamentals beforehand.

#### Q & A

> Instructor Notes: 
> Encourage the students to share any thoughts or questions before closing the session.

***

<a name="resources"></a>
## ADDITIONAL RESOURCES
- [Sorting algorithms](https://www.toptal.com/developers/sorting-algorithms)
- [15 sorting algos in 6 min](https://www.youtube.com/watch?v=kPRA0W1kECg)
- [Decision trees in scikit-learn](http://scikit-learn.org/stable/modules/tree.html)
- [Decision trees tutorial](http://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/)

For more resources see the list provided in the [Takeaways Section](#takeaway).
