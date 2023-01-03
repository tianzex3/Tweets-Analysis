# Tweets-Analysis (Big Data Platform)
__Whether Twitter can be considered a credible source of information, reflects the emergence of important trends or topics in education, specifically: “Biden’s college student debt relief”.__

![image](https://user-images.githubusercontent.com/90085137/210304292-49b1056c-0308-44a7-8727-814904cec084.png)

## Methodology
Tool: Google Cloud Platform <br>
File Type: Json <br>
Language: PySpark, Hadoop <br>
Data Frame: PySpark DataFrame, Spark RDD, Pandas <br>
Method and Techniques: MinHash LSH for Jaccard Distance <br>

## Available Data
I have access to a collection of Twitter data that is stored in Google Cloud Storage. Once  combine individual JSON files, there will be around 100 million Tweets (~500GB).  These tweets are collected on the topics of education, schools, universities, learning, knowledge sharing, etc., but only a fraction of them would be directly related to either primary, secondary or higher education.

## The Objective
The objective is to identify whether Twitter can be considered a credible source of information, which reflects the emergence of important trends or topics in education, and the topic is “Biden’s college student debt relief”.

## Questions to Answer
-Based on the analysis, are higher Tweet volumes reflective of the emergence of new hot topic in education?  <br>
-Or they are more related to other events, such as sports, viral social media posts, university application cycles, being admitted to the university, etc.? <br>
-Who are these Twitterers that are tweeting about K-12 Links to an external site.or Higher Education? <br>
-Are these mostly government institutions, universities and credible non-profit organizations? <br>
-Or random users tweeting about their schools, teachers, application processes, or attitudes toward going (or not going) to schools. <br>
-Do you see most of these messages being original content or just copies of the original tweets / retweets?

## Conclusion
Twitter could be considered a source of information that can reflect the emergence of important trends or topics in education. It also could be useful for understanding the public’s opinion on a certain topic or trend in education.

However, based on the current analysis, it should not be considered a creditable source to obtain knowledge for the topic in general until further tweet analysis. Since most tweets are original content created by social media influencers other than authority agencies such as governments, schools, news, and non-profit organizations.

## Future Work
In addition to the current analysis, the analysis of the credibility of original tweets created by social media influencers could be the aim for the next step:

__“How credible are the original tweets could be taken for topic knowledge gaining from non-authority entities?”__
