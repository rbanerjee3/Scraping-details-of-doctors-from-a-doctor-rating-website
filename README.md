# Web-Scraping details of Doctors available on doctor rating website

**Website to scrape:** https://www.ratemds.com/

**Motivation:**

After I decided to choose the data-science path, my first question was like every other data-science aspirant: How, What and where should I start with? Some of the popular answers were: Learn advance statistics, SQL, R/Python, machine learning, etc. So, following the herd, I spent 3 months learning Statistics, Python and SQL, I was ready for my next task i.e dive into the exciting world of Machine Learning. My plan was to take a MOOC course for the same. Parallely, I also used to read 2-3 articles on KDNuggets every day in order to understand the world of data-science. So, one fine day, I came across this interesting article: https://www.kdnuggets.com/2018/11/get-hired-as-data-scientist.html. What attracted me the most in that post was the last point:

_"Do things that seem crazy. Everyone goes to the UCI repository, or uses some stock dataset (yawn) to build their project. Don’t do that. Learn how to use a web scraping library, or some under-appreciated API to build your own, custom dataset. Data is hard to come by, and companies often need to rely on their engineers to get it for them. Your goal should be to come across as the kind of data science-obsessed lunatic who will build your own goddamn dataset if that’s what it takes to get the job done."_

And I agreed so much with the statement. Its true that if you don't have the required dataset, what's the use of all the Statistics, Database and Machine Learning you have learnt. So, I started learning about web-scraping and luckily, during that period, I also got a chance to work under my professor at Graduate School on a Data-Analytics Project where my first task was to scrape data from a Doctor Rating Website in the US. This way I started with my Web-scraping project.

**Overview:**

The code is designed to help us scrape data for all the doctors from a popular Doctor Rating website https://www.ratemds.com. The doctors can be filtered based on specialty, City, Gender, whether verified or not and whether accepting patients or not. These filters need to be applied on the website and the corresponding URL needs to be entered as an input over and rest will be taken care of by the code.

The details of Doctor includes:
a. Name of the Doctor
b. Specialty
c. Star-Rating
d. No. of Reviews
