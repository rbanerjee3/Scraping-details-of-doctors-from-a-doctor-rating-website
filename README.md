# Scraping details of doctors from a doctor rating website

**Motivation:**

After finishing my basics (Statistics, SQL and Python), I was quite excited to jump into the world of Machine Learning. Reading about the cool projects on GitHub every day, I always used to wonder, when will I start doing such things. So, as usual like others, I completed a MOOC on Machine Learning and started searching for a dataset to get my hands dirty. But, one fine day, I came across this [article](https://www.kdnuggets.com/2018/11/get-hired-as-data-scientist.html) on KDNuggets called **To get hired as a Data Scientist, don't follow the herd**. This article changed the way I looked at Data-Science projects and what attracted me the most in that article was the last point:

_"Do things that seem crazy. Everyone goes to the UCI repository, or uses some stock dataset (yawn) to build their project. Don’t do that. Learn how to use a web scraping library, or some under-appreciated API to build your own, custom dataset. Data is hard to come by, and companies often need to rely on their engineers to get it for them. Your goal should be to come across as the kind of data science-obsessed lunatic who will build your own goddamn dataset if that’s what it takes to get the job done."_

There is no use of statistics, databases or machine learning if we don’t have the required dataset. So, I started learning about web-scraping and eventually I started working on a research project at my Graduate School where my first task was to scrape data from a Doctor Rating Website in the US. This way I started my Web-scraping project.

**Overview:**

The code is designed to help us scrape data for all the doctors from a popular Doctor Rating website [RateMDs](https://www.ratemds.com). The doctors can be filtered based on specialty, City, Gender, whether verified or not and whether accepting patients or not. These filters need to be applied on the website and the corresponding URL needs to be entered as an input here and rest will be taken care of by the code.

The details of the doctor obtained as an output includes:
1. Name of the Doctor
2. Specialty
3. Star-Rating
4. No. of Reviews
