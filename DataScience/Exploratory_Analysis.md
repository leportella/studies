## Exploratory Data Analysis

**Data exploration** is look for something you are not always sure what it is (until you find it). 
In a more strinct way, the **exploratory data analysis** (EDA) is a well-established statistical tradition that provides conceptual and 
computational tools for discovering patterns to foster hypothesis development and refinement (Behrens, 1997). 
The underlying assumption of the exploratory approach is that the more one knows about the data, the more effectively data can be used 
to develop, test and refine theory. 

Data analysts and scientists must work interactively in a cyclical process of pattern extraction (mathematics) and pattern 
interpretation (science). Neither can function without the other. 

"Exploratory data analysis can never be the whole story, but nothing else can serve as the foundation stone -- as the first step"
(Tukey, 1977)

## EDA vs Statistics

The idea is not to reject probabilistic approaches, but rather considers them within a larger context of the many tools and ideas
that bear on scientific work. In the case of outliers, the probabilistic question to be asked is: "If the underlying process 
has a distribution of X and I exclude data from it, is the result biased in the long run?" while in the exploratory analysis 
the question should be "Given that I do not know the underlying distribution of X, what do I know about the processes that 
may help me decide if extreme values are from the same process as the rest of the data?".

## Summarization

When faced with numerous pieces of data, the goal of the analyst is to construct a terse yet rich mathematical description of the
data. After reading a long book, one does not recall every individual word, but rather remembers a major themes. In a similar 
way, the data analyst want to come away with a useable and parsimonious description rather than a long list of data. An essential
concept associated with summarization is that every summary represents a loss of information.

## General concepts of EDA

According to Hoaglin, Mosteller and Tukey (1983) there are four Rs of EDA:

  * Revelation - Graphics are the primary tool for the exploratory data analyst. 
  The most known graphical device for EDA is the box-plot.
  
  * Residuals and Models - DATA = FIT + RESIDUALS. This simple formula reminds us that our primary focus is on the development of 
  compact descriptions of the world and that these descriptions will never be perfect; thus, there will always be some misfit
  betwen our model and the data. Errors and error's patterns and size should be analyzed in other to understands the models limitations 
  and how to improve it.
  
  * Reexpression - same as appropiate scaling of data. Although mathematically equivalent to what is called transformation in other traditions,
  reexpression is so named to reflect the idea that the numerical changes are aimed at appropriate scaling rather than radical
  change.
  
  * Resistance - Because a primary goal of using EDA is to avoi being fooled, resitance is an importante aspect of EDA.
  Resistant methods are methods that are not easily affected by extreme or unusual data. T


## Principles of Analytic Graphics

	### Principle 1: Show comparisons
  
		* Evidence for a hypothesis is always relative to another hypothesis
    
	### Principle 2: Show causality, mechanism, explanation, systematic structure
	
    * What is your causal framework for thinking about a question?

	### Principle 3: Show multivariate data
		
    * Multivariate = more than 2 variables
		
    * The real world is multivariate

	### Principle 4: Integration multiple modes of evidence
		
    * Completely integrate words, numbers, images, diagrams
		* Data graphics should make use of many modes of data presentation
		* Don't let the tool drive the analysis

	### Principle 5: Describe and document the evidence with appropriate labels, scales, sources, etc
  
		* A data graphic should tell a complete story that is credible

	### Principle 6: Content is king
		
    * Analytical presentations ultimately stand or fall depending on the quality, relevance and integraity of their content

## Why do we use graphs in data analysis?

	* To understand data properties
	* To find patterns in data
	* To suggest modeling strategies
	* To debug analysis
	* To communicate results

## Exploratory Graphs
	* Tend to be made very quickly (quick and dirty)
	* Tend to make a large number of them
	* The objective is to develop a personal undestanding of the dataset (What are the properties, what are the problems?)
	* Let you summarize the data (usually graphically) and highlight any broad feature
	* Explore basic questions and hypotesis 
  
  
  

-----------------------------------------------------------

Behrens, J. T.. Principles and procedures of Exploratory Data Analysis. American Psychological Association Inc. 1997. Vol.2, No.2, 131-160
