---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, Northeastern University
* M.S. in International Business Administration, UMSL
* B.S. in Finance, Sourtheast University

Academic experience
======
* Spring 2022: Genetically modified crop identification
  * Terahertz time-domain spectroscopy is a powerful detection technique that has been applied to the detection of
biochemical molecules such as proteins, amino acids, and DNA. In recent years, there are also some methods to
identify transgenic crops using THz-TDS.
  * Detection of transgenic maize absorbance data by THz-TDS, because the terahertz spectrum is high-dimensional
data, the absorption spectrum was reduced to 3 dimensions by using PCA denoising, and then the identification
rate was 98.75% by K-means calculation.

* Fall 2021: Improving supply chain tea ordering accuracy through machine learning
  * The project focused on improving the accuracy of tea orders in the supply chain by utilizing machine learning to
predict the likelihood of a user clicking on a tea product link in an e-commerce platform. By accurately predicting
user behavior, we were able to reduce the ordering cycle from months to days, which helped to minimize
inventory costs for tea suppliers.
  * Moreover, the project required a deep understanding of tea processing, packaging, and shipping, as well as the
ability to analyze large volumes of data related to tea orders and customer behavior. This required collaboration
with experts in the tea industry to ensure that the machine learning models accurately reflected the complex and
nuanced nature of the tea supply chain. Overall, the project demonstrated the potential for machine learning to
drive efficiency and cost savings in the agriculture sector.

* Sping 2021: Automatic detection of protective equipment at power construction sites
  * In order to ensure the safety of power construction personnel, the video camera real-time capture of the power
construction site screen, the use of TuriCreate to establish a convolutional neural network (CNN) model to
identify whether the personnel at the power construction site wear the necessary protective equipment, the
construction location, time, and images that do not meet the protective conditions through the large screen
monitoring system for the back-end monitors to provide a real-time alarm.
  * The project divided 80% of the data into training sets and set a random seed value of 2. The prediction accuracy
of the model reached 0.96.

* Fall 2018: Investment Analysis System
  * Crawled industry data from the internet, perform analysis and forecasting on AWS and GCP using Numpy,
Pandas, Scipy, and Sklearn with Time Series Forecast, ARR, MRR, Decision Tree, etc. Organized dashboards with
Google Analytics and Tableau to visualize data and provide expert investment recommendations to support
investment decisions.
  
Skills
======
* System Platform – GCP, AWS, z/OS, AIX, Linux, Microsoft Windows Server, ESXI, Citrix Hypervisor
* Database Management – Teradata, SAP Sybase IQ, DB2, Microsoft SQL Server, Oracle, MySQL, Da Meng,
HBase, MongoDB, DynamoDB, Redis, Elastic Search
* Programming – Java, Python, C, Cobol, Perl, Bash, PeopleSoft code, SAS, SPSS, SQL, PHP, HTML,
CSS, JavaScript, React, Vue

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
