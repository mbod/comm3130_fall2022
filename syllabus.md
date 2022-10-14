## COMM3130: Computational Text Analysis for Communication Research
**Fall 2022: Tu/Th 12.00-1.30pm**  
**Room: ASC111**

**Professor**: Dr. Matt O'Donnell (he/him/his)
  - **Email**: mbod@asc.upenn.edu
  - **Office hours**: Virtual online meetings through Zoom (email to set up time and see Canvas Announcements for specific times)


**Coding Assistant**: Jonah Charlton
  - **Email**: jcharlto@sas.upenn.edu
  - **Office hours**:
	- Tuesady 5-6pm Zoom (see link in Canvas)
	- Thursday 1.30-2.30 In person (See Jonah in class for location)
  - **IMPORTANT** Jonah will only be available in class sessions and during his two office hours.

----

## IMPORTANT NOTICE - <u>Masks are required in this class</u>
* Please make sure you are wearing a face mask fully covering both mouth and nose _before_ you enter the classroom and keep it in place _at all times_.
* Make sure you have a "properly-fitting, high-quality mask (preferably a surgical mask, KN95/KF94, N95, or [EHRS-recommended Aries mask](https://ehrs.upenn.edu/covid-19/universal-mask-and-cloth-face-covering-precautions) as opposed to a single layer cloth mask)." (UPenn Public Health Guidance).

----

## Course Description, Goals and Objectives

In this hands-on course students will learn how to manage large textual datasets (e.g. Twitter, news stories, song lyrics, YouTube comments) to investigate research questions. They will work through a series of steps to _collect_,
_organize_, _analyze_ and _present_ textual data by using basic Python coding toward a final project of relevant interest.  The course will cover linguistic theory and techniques that can be applied to textual data (particularly from the fields of corpus linguistics and natural language processing).

**_No prior programming experience is required._** Through this course students will gain skills writing Python programs to handle large amounts of textual data and become familiar with one of the key techniques used by data scientists, which is currently one of the most in-demand jobs.

* This course will provide an introduction to Python programming for collecting, preparing and analyzing text data from various sources including
social media (e.g. Twitter), weblogs, online news media and various publicly available archives (e.g. presidential speech archive, congressional sessions).

* Each week one session will be in lecture and seminar form and provide background for the theory and techniques and the second will be a lab session
in which students will work through programming exercises using Jupyter notebooks [A web-based programming environment well suited for data science and class-based assignments].

* By completing this course students will:
	* gain an understanding of relevant linguistic concepts for the analysis of text
	* understand the field of corpus linguistics and how its concepts and tools can be applied to text analysis questions of relevance to Communication
	* be exposed to a range of techniques from natural language processing and understand how they can be used to improve content analyses
	* gain a basic level of programming proficiency in the Python programming language and have completed a number of programming exercises to build, clean and analysis corpora of text
	* complete a data science project focused the analysis of text data and gain group work and collaborative skills

----

## Textbooks and resources

* The main readings on corpus linguistics will come from:
	* Baker, P. (2006) _Using Corpora in Discourse Analysis_. London: Continuum

* and on Python programming and NLP concepts from:
	* Bird, S., Klein, E. & Loper, E. _Natural Language Processing with Python - Analyzing Text with the Natural Language Toolkit._ Updated version for Python 3. Available free online at http://www.nltk.org/book/

----

## Assessment

1. **Complete the assigned readings and corpus building exercises (10%)**
	* Readings for each week will be posted on Canvas when electronic versions are available or taken from one of the recommended textbooks.
	* Throughout the course you will be asked to complete short writing exercises that will be used to build a class corpus for analysis. Details will be discussed in class and posted on Canvas.
		* Examples of the prompts might be:
			* _Describe your interest in Communication research._
			* _Look at this picture closely for a minute and then write a paragraph describing what you see._
			* _Write about your earliest memory._
			* _Create a recipe for a fried or boiled egg for your room mate who doesn't know how to cook._
2. **Attend weekly lab sessions and complete the assigned exercises (40%)**
    * Thursday class sessions will _usually_ be programming labs. Students are required to bring a laptop. Please contact the me if this is difficult and we can see if a machine can be made available for use in lab.
	* We will be using Jupyter notebooks to learn Python, which are a web-based interactive programming environment. You will need a `github` account (https://education.github.com/) to access the class server. Assignments will be completed in this and submitted to the instructor. Details of using this system for assignments will be covered in the first lab session.
	* Weekly assignments will be due at 5pm on the Tuesday following lab session (see schedule for details). These assignments are intended to help students practice the programming concepts and structures introduced in lab and build confidence. They should not be difficult or take excessive time but they do build from week to week so it is _very_ important to keep up.
3. **Complete a _group project_ that uses the techniques and theory covered in class to 
carry out a text analysis of a specific research question agreed upon with the instructor (50%)**
     * The goal of the project is to practice the coding skills and analytic techniques learned in the class by carrying out a focused data science project. The steps involved will include:
	   1. Select a tractable research question that involves analysis of textual data
	   2. Identify, retrieve and prepare a relevant corpus
	   3, Carry out linguistic analysis of corpus and produce a series of well documented analysis notebooks
	   4. Visualize the data and findings
	   5. Interpret the findings
	   6, Finally, produce a data blog post (similar to those on medium.com) to communicate your findings
	   
     * You will work in a group of 3 or 4
	* You can build your own group with those you know in the class and you share an 
interest for a particular research topic
	* If there are pairs who want to work together we will find another one or two 
people to make up the group

     * More details of the kinds of projects that would be appropriate and manageable will be discussed during the first few weeks of class.


## Note about learning programming

A central goal of this class is to help students begin to develop programming skills that they can use to approach questions of interest using the growing amounts of textual data available in the era of 'big data'. But like learning any new skill, such as a new language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python code examples that you can find on the web etc.

----

## Course Schedule

* **N.B.** - This is a tentative schedule that is subject to change

### Week 1 - Overview
* Tue 08/30/22 - **Course overview**
	* Language as a social tool and language data as traces of communicative acts
	* Review of course overview notebook
* Thu 09/01/22 - **Lab Session 1**

### Week 2 - Introduction
* Tue 09/06/22 - **Introduction to Corpus Linguistics and NLP**
	* _Topics_:
	   * What are _corpus linguistics_ and _natural language processing_?
	       - Counting _words_ and finding patterns in language
	       - Constructing _models_ of language data
	* _Coding_:
		* __Python Basics Part 1__
			* Objects
			* `str` objects
			* general functions
			* string functions
			* Indexing and Slicing strings
    	        * Jupyter and Python basics
	       		- Using JupyterHub and notebooks
		       - Markdown
		       - Python string objects

* Thur 09/08/22 - **Lab session 1**
	* _Topics_:
		* Jupyter notebooks.
		* First scripts for text analysis.
		* Working with Python `string` objects
			* `string` functions
			* Indexing and slicing `string` objects
		* Reading text files into string objects.
	* __Assignment 1__: Working with Python String Objects

### Week 3 - What is a corpus?
* Tue 09/13/22 - **Types of corpora**
    - _Topics_:
        * What is a corpus?
        * Types of corpus
          - _general vs specialized_
          - _matched genre vs variety_
          - _synchronic vs diachronic_
    - _Coding_:
        * Working with sequences using Python `list` objects
        * List indexing and slicing
    - **Readings**: *Baker Chs. 1&2*; *NLTK Book Ch. 1 (sections 1, 2 & 4 )* http://www.nltk.org/book/ch01.html  

* Thur 09/15/22 - **Lab session 2**
	* _Topics_:
	    * Working with Python `list` objects
	    * Basic tokenization, turning text strings to lists of strings
	    * Listing files and directories
	* __Assignment 2__: Working with Python lists

        - **Assignment 1 DUE 11.59pm** - Submit through JupyterHub


### Week 4 - Frequency lists  
* Tue 09/20/22 - **How and what to count**
    - _Topics_:
        * Word and N-Gram lists
        * Dispersion
    - _Coding_:
        * `Counter` object
        * Loops
        * Conditions
    - __Readings__: _Baker Chs. 3_; _NLTK Book Ch. 2 (esp. sections 1,2&4 )_ http://www.nltk.org/book/ch02.html

* Thur 09/22/22 - **Lab session 3**:
	* _Topics_:
	    * Using `Counter` to create frequency distributions.
	    * `for` loops
	    * Conditional constructions
	    * Filtering lists and objects.

        - **Assignment 2 DUE 11.59pm** - submit through JupyterHub


### Week 5 - Finding, building and using corpora - Part 1

* Tue  09/27/22 - **Corpus compilation**
    - _Topics:_
	* Extracting texts from documents
        * Organizing a corpus
	- **Readings**: _Baker Chs. 3&4_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html
    - _Coding:_
        * Dictionaries
        * Writing files
        * Working with JSON
	      * Functions


* Thur 09/29/22 - **Lab session 4**:
    - _Topics_:
        * Splitting up a string into chunks
        * Writing a `string` object to a file
        * List of dictionaries structure
	* Functions

    - **Assignment 3 DUE 11.59pm** - submit through JupyterHub


### Week 6 - Corpus organization and data structures 

* Tue 10/04/22 - **Data structures for corpus organization***
	* Python Basics Part 4
		* Dictionaries
		* List-of-dictionaries data structure
		* Functions
	* Working with a list-of-dictionaries
		* Short texts
			* Twitter example
		* Structured documents
	`		* Lexis-Nexis documents in dictionaries

* Wed 10/05/22 -  **Assignment 4 DUE 11.59pm** - submit through JupyterHub

* Thur 10/06/22 - **NO CLASS - FALL BREAK**


### Week 7 - Incorporating Context Part 1: _Concordance Analysis_
* Tue 10/11/22 - **Working with KWIC concordances**
    - _Topics_:
    	* Using concordances (Keyword-in-context = KWIC) to find patterns and meaning
    - _Coding_:
        * Nested lists
        * Sorting lists
      	* Functions
    - **Readings**: _Baker Ch. 4_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html

* Thur 10/13/22 - **Lab session 6**
    - _Topics_:
        * sorting lists
        * the list-of-lists structure
        * creating and using functions
        * Analysis KWIC concordances


### Week 8 - Finding, building and using corpora - Part 2
* Tue 10/18/22 - **Online corpus compilation**
    - _Topics_:
        * Using APIs to compile a corpus (e.g. Twitter, Genius.com)
	* Understanding web page structures
	* HTML and CSS basics
        * Using web scraping and crawling to build a corpus
    - _Coding_:
        * Using `requests` for web page and API access
	* Using `BeautifulSoup` to extract text from HTML
	* Accessing an API from Python
	* Working with JSON in Python

    - **Readings**: _Baker Chs. 2_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html


* Thur 10/20/22 - **Lab session 6**

    - **Final Project Planning**

    - _Topics_:
        * downloading web pages (using `requests` module)
	* navigating HTML documents and extracting text
	* building a web corpus
	* accessing the genius.com API from Python

    - **Assignment 5 DUE 11.50pm submit through JupyterHub**


### Week 9 - Incorporating Context Part 2: _Collocation_
* Tue 10/25/22 - **Words _have_ friends**
    - _Topics_:
        * Discovering meaning through context
		* Comparing words through collocation
		* Collocation profiles
		* Measuring _strengh of friendship_
		* Building collocation networks

	- _Coding_:
		* Working with list-of-lists
		* Use a dictionary with complex values
		* Dictionary-of-dictionaries data structure

    - **Readings**: _Baker Ch. 5_; _NLTK Book Ch. 4 (sections 1&2)_ http://www.nltk.org/book/ch03.html


* Thur 10/27/22  - **Lab session 7**

    - _Topics_:
	* calculating collocates
	  - from KWIC object (individual keyword)
	  - from collocates (e.g 2nd order collocates or collocates of collocates)
          - from all tokens
	* building a collocate network
        * displaying collocates as a network

    - __Assignment 6__ DUE 11.59pm submit through JupyterHub


### Week 10 - Keyness Analysis

* Tue 11/01/22 - **Discovering distinctive vocabulary**

    - _Topics_:  
        * 'Aboutness' in text
        * Kinds of comparison
        * Statistical significance and association

    * **Readings**: _Baker Ch. 6_; _NLTK Book Ch. 4 (sections 3&4)_ http://www.nltk.org/book/ch04.html


* Thur 11/03/22 - **Lab session 8**

    - **Final Project Initial Presentations**
		- Each project group will give a quick 3-5 minute overview of their research topic, planned corpus and analysis strategy
		- 3 or 4 slides 

    - _Topics_:
		* Creating keyness profile
		* Filtering and analyzing keyness lists

    - __Assignment 7__ DUE 11.59pm submit through JupyterHub


### Week 11 - Introduction to NLP

* Tue 11/08/22 - **NO CLASS - Engagement Day**

* Thur 11/10/22 - **Core concepts and techniques in NLP**

	- _Topics_: 
		* NLP pipeline
		* Key tasks: POS tagging, parsing, sentiment analysis, anaphora resolution, role identification
		* Example Applications
	
	- _Coding_:
		* Using `nltk` module and functions
			- word tokenization
			- sentence segmentation
			- POS tagging
		* Filtering by POS categories 

    * **Readings**: _NLTK Book Ch. 1 (section 5)_ (http://www.nltk.org/book/ch01.html) and _Ch. 5_ (http://www.nltk.org/book/ch05.html)


    - __Assignment 8__ DUE 11.59pm submit through JupyterHub


### Week 12 - NLP: Affect and Sentiment analysis

* Tue 11/15/22 - **Measuring emotion in text**
	- _Topics_: 
		* Sentiment analysis and opinion mining
		* Approaches: lexicons and classifiers
		* Using affect lexicons
		
	- _Coding_: 
		* Using VADER
		* Crowdsource lexicons

  * **Readings**: _NLTK Book Ch. 6_ (http://www.nltk.org/book/ch06.html)


* Thur 11/17/22 - **Sentiment classification**
  
  	- _Topics_: 
		* Building your own sentiment classifier
		* Representing text as a _document term matrix_ (DTM)
		* Supervised machine learning
		* Building a training corpus
		* Measuring accuracy
	
    - __Assignment 9__ DUE 11.59pm submit through JupyterHub


### Week 13 - NLP: Named Entity Recognition (NER): Who, what, when and where?
* Tue 11/22/22 - **Identifying actors and actions in text**
  	- _Topics_: 
		* Quick introduction to spaCy
			* A state-of-the-art NLP pipeline
			* Processing documents
			* Extracting phrases, entities
		* Finding who does what to whom in a corpus

	* **Readings**: _NLTK Book Ch. 7_ (http://www.nltk.org/book/ch07.html)

* Thur 11/24/22 - **NO CLASS: Thanksgiving Break**


### Week 14 - NLP: Topic models

* Tue 11/29/22 - **Discovering clusters of words in text collections**

   - _Topics_: 
      * Extending collocation pairs to clusters of co-occuring terms
      * Generative model of a corpus
      * Examples

* Thur 12/01/22 - **Lab session 11**: Topic models and visualization

   - _Topics_: 
      * Building and tuning a topic model
	  * Visualizing and exploring the results

### Week 15 - Class projects

* Tue 12/06/22 - **Project presentations**

* Thur 12/08/22 - **Project presentations**

* __Presentations__
	* Groups will have 5-8 minutes to give an update on their project progress so far
	* 5 or 6 slides, covering:
		* _Research question_
		* _Corpus descriptives_
		* _Analysis so far_
		* _1 or 2 interesting results_
		* _Next steps_




