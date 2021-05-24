# Web-mining


# Web mining

Web Mining deals with analytics on web-related data. How do search engines return relevant results so quickly for various queries? How do these search engines work? How does Amazon recommend products to its users? How are social networks formed and how do they grow? How do people influence each other on social networks? How do search engines make money through ads? How can you use the wisdom of the crowds to generate useful and credible information?

The course will takes the participants through understanding of the basic information retrieval concepts, web mining concepts, the architecture of search engines, and applications. This module aims to provide a conceptual and practical understanding of various aspects of web mining starting with the basics of web search to discussions about recent topics studied in the World Wide Web community. Topics covered will include: crawling, indexing, ranking, analysis of social networks, recommendation systems, and basics of computational advertising.



![image](https://user-images.githubusercontent.com/67232573/114186497-cb4d8300-98fb-11eb-944d-626bca18705d.png)




# Text indexing

Term-Document Incidence Matrices

Inverted Indexes

Inverted Index Construction

Sorting for Inverted Index Construction

Query Processing using Inverted Indexes

Query Optimization for Inverted Indexes

Phrase Query Processing using Bi-word Indexes

Phrase Query Processing using Positional Indexes

Heap’s Law

Zipf’s Law

Motivation for Compression of Inverted Indexes

Dictionary Compression using Fixed-width terms or a single string

Dictionary Compression using blocking and front coding

Dictionary Compression using BTrees and Tries

Postings Compression by coding gap

Variable Length Encoding for Postings Compression

Unary and Gamma codes for Postings Compression

What is Lucene?

Java code: Indexing Shakespeare’s plays.

Java code: Searching Shakespeare’s plays.

Fields in Lucene

Analyzers in Lucene

QueryParsers and Scoring in Lucene



![image](https://user-images.githubusercontent.com/67232573/114186658-f7690400-98fb-11eb-973c-3c26120f5506.png)




# Crawling

Basics of Crawling

What any crawler must/should do?

URL frontier, politeness, robots.txt

Processing Steps in Crawling

Webpage and Web Graph processing

Using Nutch for Crawling


# Relevance ranking

Need for Relevance Ranking

Jaccard Similarity for Relevance Ranking

TF and IDF

Vector Space Model, Cosine Similarity, and Okapi BM25

Efficient Cosine Ranking

Parametric, zone and tiered indexes

Evaluating Search Engine Quality: Factors, NDCG

Evaluating Search Engine Quality: Kappa Measure, AB testing

Python code: TFIDF Computation from scratch

Python code: TFIDF computation using SKLearn

Python code: TFIDF computation using gensim



![image](https://user-images.githubusercontent.com/67232573/114186720-0cde2e00-98fc-11eb-9d9d-af2c4da28b25.png)





# Link analysis algorithms

Link-based Ranking of Web Pages

Power Iterations Method

Random Walk Interpretation

Spider traps and dead-ends

Problems with PageRank

Topic Sensitive PageRank

HITS (Hypertext-Induced Topic Selection)

Web Spam

TrustRank to Handle Link Spam

Python code: PageRank and HITS using networkx

Python code: PageRank from Scratch




![image](https://user-images.githubusercontent.com/67232573/114186838-2c755680-98fc-11eb-977a-0fc1d3626977.png)





# Recommendation Systems

Introduction to Recommender Systems

User-based Collaborative Filtering

Problems with User-based Collaborative Filtering

Item-based Collaborative Filtering

Hybrid Recommendation Methods

Recommendation System Case Studies: Video and Software Items

Tag Recommendations

People Recommendations within an enterprise

Friend Recommendation on Twitter

Recommendations for Groups

Cold Start Problem

Explanations for Recommendations

Evaluation of Recommendation Systems: Offline Evaluation

Evaluation of Recommendation Systems: User Studies and Online Evaluation

Python Code: User-user collaborative filtering and item-based CF from scratch

Python Code: Introduction to User Article Interaction Dataset

Python Code: Pre-processing dataset before building recommendation models

Python Code: Defining recommendation evaluation measure

Python Code: Popularity based recommender

Python Code: Content based recommender

Python Code: Collaborative Filtering based recommender

Python Code: Simple Hybrid Recommender

Python Code: Comparison across multiple types of recommenders

Python Code: Obtaining recommendations for a person




![image](https://user-images.githubusercontent.com/67232573/114186940-4747cb00-98fc-11eb-97cf-f67cee1230de.png)





# Social Network Analysis

Introduction to Social Network Analysis

Erdös-Renyi Model

Small World Model

Kleinberg’s Model

Power Laws

Preferential Attachment Model

Copying Model

Forest Fire Model

Model with Network Components

Summary of Various Network Generation Models

Python code: Generate Graphs, Traverse Nodes and edges, Save and Load Graphs using snap

Python code: Graph Manipulation using snap

Python code: Computing Structural Properties using Snap

Python code: Plot graphs and their degree distributions




![image](https://user-images.githubusercontent.com/67232573/114187062-70685b80-98fc-11eb-96a7-5ccec86eccdd.png)




# Social Influence Analysis

What is Social Influence?

Does Social Influence really matter?

Examples of Social Influence

Measuring Social Influence: RCT test

Measuring Social Influence: Shuffle test and reverse test

Measuring Social Influence: Reachability and action-based methods

Social Theories: Structural Balance and Social Status

Models for Social Influence Analysis: Linear Threshold Model

Models for Social Influence Analysis: Independent Cascade Model

Influence Maximization Problem

Solutions for Influence Maximization Problem

Applications of Social Influence Analysis

Python Code: Independent Cascade Model on Facebook Social Circles Dataset

Python Code: Influence maximization heuristics on wiki-Vote data




![image](https://user-images.githubusercontent.com/67232573/114187171-8c6bfd00-98fc-11eb-88e6-e07bb6112796.png)




# Twitter Data Analysis

Twitter data characteristics and challenges

Burstiness to detect events from Twitter

Detecting Events using Graph Community Analysis

Detecting Events using CRFs

Detecting Events using Tag Correlations

Detecting Events by Label Propagation from News

Finding best phrase to describe an event

Finding event types

Finding event timespans

Detecting sporting events

Detecting local festivals

Detecting drug related adverse events

Detecting emerging controversial events

Python Code: Retreiving trends from Twitter

Python Code: Collecting search results and extracting text, screen names and hashtags from tweets

Python Code: Lexical analysis of tweets

Python Code: Analysis of retweets




![image](https://user-images.githubusercontent.com/67232573/114187296-ac9bbc00-98fc-11eb-90fb-401462dc3f60.png)




# Mining Structured Information from the Web

Introduction to Information Extraction

What all can be extracted?

Wrapper Induction: Why and what

Extraction rules for Wrapper Induction

Learning Extraction rules for Wrapper Induction

Wrapper Maintenance

Extracting Tables from the web

Extracting Tables from the web: Recovering relations from raw HTML tables

Extracting Tables from the web: Applications

Python Code: Get list of all Presidents of India with related information from Wikipedia page using just pandas!

Python Code: Understanding Basics of BeautifulSoup

Python Code: Scraping weather forecasts using BeautifulSoup

Python Code: Scraping apartment information using beautiful soup from apartments.com
OpenIE and Tagme




![image](https://user-images.githubusercontent.com/67232573/114187405-cb9a4e00-98fc-11eb-9a01-6330ce0dd147.png)





# Computational Advertizing

Introduction to Computational Advertising

Computational Ads Basic Concepts: Stakeholders and Revenue Models

Display Ads: Problems and Methods

Introduction to Textual Ads

Selection of Textual Ads: Part 1

Selection of Textual Ads: Part 2

Sponsored Search

Introduction to Game Theory and Nash Equilibrium

Game Theory for Ads

Vickrey Auction

VCG Auction

Auctions for Sponsored Search

Generalized First Price Auction

Generalized Second Price Auction

Comparison between GFP, GSP, VCG

Python Code: Introduction to the Ad Click Through Rate (CTR) Prediction Problem

Python Code: Exploratory Data Analytics for Ad CTR Prediction: Part 1

Python Code: Exploratory Data Analytics for Ad CTR Prediction: Part 2

Python Code: Developing Logistic Regression Prediction model for Ad CTR Prediction

Python Code: Developing Gradient Boosting Prediction Models for Ad CTR Prediction




![image](https://user-images.githubusercontent.com/67232573/114187484-e79def80-98fc-11eb-847c-6df9fbad200a.png)





# Crowdsourcing

Introduction to Crowdsourcing

Applications of Crowdsourcing: Part 1

Applications of Crowdsourcing: Part 2

Cons of Crowdsourcing

Quality and Incentives Control in Crowdsourcing

Managing Complex tasks in Crowdsourcing

Security Challenges in Crowdsourcing

Fake reviews and social network sybils in Crowdsourcing

Managing Quality of Annotations

Weighted voting to get final labels

Gold testing with bad worker quality and unbalanced datasets

Integrating crowdsourcing with machine learning

Tips for Iterative HitApp Design

Introduction to the Amazon Mechanical Turk Platform

An Example of a crowdsourcing project using Mechanical Turk




![image](https://user-images.githubusercontent.com/67232573/114187561-fe444680-98fc-11eb-98cc-ea3a1f0804a7.png)






# Entity Resolution in the Web of Data

Entities and Knowledge Bases

The Entity Resolution Problem

Examples of Entity Resolution

Similarity Function for Entity Resolution

Entity Resolution Workflow

Standard Blocking and the Sorted Neighborhood Method

Canopy Clustering and Token Blocking

Attribute Clustering Blocking

ZenCrowd Blocking

Prefix-Infix(-Suffix) Blocking

Block Post-Processing

Meta-Blocking

Python Code: Link two datasets using the recordlinkage Python package

Python Code: Data deduplication using recordlinkage Python package

Python Code: Classification Algorithms for Record Linkage

Using the dedupe package in Python




![image](https://user-images.githubusercontent.com/67232573/114187668-1b791500-98fd-11eb-8475-93851ba897ce.png)




