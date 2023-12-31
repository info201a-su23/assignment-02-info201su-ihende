# Assignment 2: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and many other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is ocassionally [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

Through this assignment, you will be able to answer questions about protests, including:

* What were the most attended and least attended protests in the US in the last 5 years?
* How many protests occurred in Washington state?
* How did the number of protests in 2019 compare to 2020, and why?
* Why are people protesting in the US? What are the biggest motivators?

## Learning objectives
By completing the assignment, you will develop or skills for:

- **Version control** tools for managing code (git and GitHub)
- Writing documents with **markdown** syntax
- Coding in R
- Thinking critcally about data.

# 1. Critical Analysis & Reflection: Before You Code

Before diving into this (or any) dataset, it's important to know where the data came from, and it's important to have or to seek out _domain familiarity_ — that is, knowledge about the topic of the dataset. Sometimes the topic is very narrow; more often it is expansive, as in the case of CountLove. We don't want to be "strangers in the dataset," as Catherine D'Ignazio and Lauren Klein describe it. To get more familiar, we are going to begin by doing some background reading.

**Note:** Please write your answers below under the heading "Your Responses and Reflections."

- First, please read [this FAQ](https://countlove.org/faq.html) from the CountLove website and the opening of [this blog post](https://www.tommyleung.com/countLove/index.htm).  **(R1a)** Based on the information in these pieces, why did the creators start collecting the CountLove data?

- Next, we would like you to read this [New York Times piece that uses CountLove data](https://www.nytimes.com/interactive/2020/06/13/us/george-floyd-protests-cities-photos.html) and that describes the Black Lives Matter protests that occurred in the summer of 2020. **(R1b)** Please summarize the main point or argument of this article.

Next, we're going to reflect about who collected this data, and what's actually inside it. 

**(R1c)** Who collected and shared the CountLove data, and what do they do for a living?

**(R1d)** As Klein and D'Ignazio remind us, when it comes to data, "what gets counted counts." What types of demonstrations does CountLove include in their data, and what types do they exclude? 

**(R1e)** How and where does CountLove get their data about the protests? 

**(R1f)** How does CountLove make their estimates about the number of people who attended a protest? What potential problems might arise from this method of estimation? 

**(R1g)** What are two central values of Count Love? Name and briefly describe them. (See the Envisioning Cards for a defintion of "value".)

**(R1h)** Name and briefly describe one direct stakeholder and one indirect stakeholder (See the Envisioning Cards)? 

# 2. Coding in R: Parts 1-6
**Instructions**. Assignment instructions and prompts are in this file: [analysis.R](analysis.R).

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to think and write in English below, in this file (README.md).

**Formatting Your Responses and Reflections**.

* When formatting your written responses and reflections below, please *retain* all
reflection prompt IDs (e.g., R1a, R2a, etc.).
* Fill in the elipses (...) with your own words. 
* Remove expected word counts.
* To write clearly, use markdown code appropriately (e.g., **bold**, _italics_, and `code`). As appropriate, include images, links, and so forth.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: October 2022, Your Teaching Team_)

# 3. Critical Analysis & Reflection: After You Code

In the second chapter of *Data Feminism*, Klein and D'Ignazio describe 4 ways that data scientists can challenge power and take action:
> Taking action can itself take many forms, and in this chapter we offer four starting points:  
> (1) Collect: Compiling counterdata—in the face of missing data or institutional neglect—offers a powerful starting point as we see in the example of the DGEI, or in María Salguero’s femicide maps discussed in chapter 1.  
> (2) Analyze: Challenging power often requires demonstrating inequitable outcomes across groups, and new computational methods are being developed to audit opaque algorithms and hold institutions accountable.  
> (3) Imagine: We cannot only focus on inequitable outcomes, because then we will never get to the root cause of injustice. In order to truly dismantle power, we have to imagine our end point not as “fairness,” but as co-liberation.  
> (4) Teach: The identities of data scientists matter, so how might we engage and empower newcomers to the field in order to shift the demographics and cultivate the next generation of data feminists?  

**(R1h)** How does the CountLove project embody one or more of these 4 forms of challenging power? 

**(R1i)** What is the most interesting or surprising thing you learned from this analysis? Please answer in at least 2-3 sentences (2 points)

**(R1j)** What is a kind of analysis that you would like to do or that would be interesting to do with the CountLove data that you don't have the time or skills to accomplish at this moment? Please answer in at least 2-3 sentences (2 points)

## Your Responses and Reflections

### Critical Analysis & Reflection: Before You Code (questions above)

* **(R1a)** 
The creators started collecting CountLove data in order to improve coverage on data about protests. In the United States, there is a lack of media coverage about regional protests and aggregate protest data is not readily available. This data helps document and understand trends in protests related to important societal issues.

* **(R1b)** 
The main idea in this article is how the Black Lives Matter protests of summer 2020 reached almost every setting and demographic in the United States. The author uses the CountLove data to demonstrate the reach of this movement and the varying locations and sizes of the protests.

* **(R1c)** 
This data was collected and shared by Tommy Leung and Nathan Perkins. They are engineers and scientists with interests in civic responsibility and public policy.

* **(R1d)** 
CountLove includes information like the locations of protests and the quantity of protests at each one. It does not include information about the sizes of some of the individual protests, or any injuries, arrests, etc.

* **(R1e)** 
They get their data from local newspaper and television sites. They use software and various models to aggregate this data as well.

* **(R1f)**
 They record the most conservative attendance number from the news articles that they link. For example, they interpret a "dozen" as 10. This may cause some problems to arise with underestimating attendance and your data will not be as truly reflective of the actual number of attendees. This may be an issue when trying to predict possible trends in the protests.

* **(R1g)** There are 2 related central values of CountLove which are...
- Increasing access to valuable information that may not have consistent or widespread coverage
- Creating a more diverse, empathetic and kind world due to more coverage on protests, and exposing more people to inpsiring movements that will better our society

* **(R1h)** 
- Direct stakeholder: people who organize or participate in protests because this information directly reports on and affects the protests they participate in. They can gather more information on the protests with this data as well.
- Indirect stakeholder: people who aren't participating in the protests or involved in them, but are still affected. This could include people who live in heavily protested areas and their neiighborhoods are affected by the traffic or any possible police activity. Another example could be the government, because the protests put a lot of pressure on government policies.

### Part 3: Locations (`analysis.R`)
* **(R3a)** 
I'm honestly not too surprised by the number of protests in Washington. Proportionally to the rest of the country the number makes sense. Washington is also a liberal state that often advocates for policy change, so I'm not surprised at the relatively high number of protests.

* **(R3b)**
Yes, being able to sort through the whole dataset with just one function was really surprising. It makes me wonder what other functions we will end up using to be able to interpret and analyze data.

* **(R3c)** 
One data quality issue I noticed with this table was that the states were case-sensitive. So, a state being recorded as "WA" and "wa" would be in different categories. I would change my analysis of this data by considering that some states may have multiple groupings, and then group those together.

### Critical Analysis & Reflection: After You Code (questions above)
* **(R7h)** 
The main forms of challenging power that CountLove embodies are collecting and teaching. As said on the website, CountLove compiles data that may be "in the face of missing data or insititutional neglect". These protests may not often be reported on and cause their to be missing data. CountLove counters that neglect. Secondly, CountLove teaches. Through identifying themselves and their purpose on the FAQ page, CountLove empowers potential data scientists and those who care about social issues. This can help shift the power dyanmics surrounding data and affect change.
* **(R7i)** 
I think the most important thing I learned from this assignment was about the capabilities to sort through and extract information from large datasets. This interested me because of the insights I could gain through extracting certain aspects of data and I'm excited to keep learning what I can do with data and R!
* **(R7j)** 
I would like to go more into the locations aspect of the protest data. I think uncovering trends regarding concentrations of protests in one location over a period of time, or even connecting the protest purposes to certain locations. I think this can allow us to see what states implement government policies that tend to be protested more often.
