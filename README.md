# Indeed-Job postings web scraping and analysis
Scrapping job postings for analytics jobs posted in California within the past week.

Job searches can be onerous. People spend much time on job hunting websites and easily get overwhelmed by tons of information. Through this project I aim to simplify this process by using web scraping to automate tailored job search and thus deliver the right fit for every hire. 
The job details of interest are: **Job title, Company name, Job location, Job list date, Job description, Job application link. **

I begin with BeautifulSoup to parse these “parameters” from Indeed, and save results to a csv file as well on MongoDB, a NoSQL database, that would allow me flexibility in case of future addition of job postings from other websites like LinkedIn or Glassdoor.

In this project, the default search parameters I used are:
**Job title:  Data Analyst or Business Analyst or Business Intelligence or Project Management or Product Management or Product Analyst or Data Scientist
Job location: California (CA)
Job list date: within last 7 days

The final result is a summary of analytical relevant job posting information for quick perusal and application by job seekers. 

Conclusion: My analysis further shows that in the last week in the month of March 2021, the jobs scenario for analytical roles in CA is as follows: 
**Top 5 Highest number of openings: Apple, Tesla, Workday, Google, and PG&E Corporation
This would help job seekers target their search to company websites that have high openings and take steps to network with current employees of these firms.

**Top 5 Best locations: San Francisco, Fremont, San Jose, Santa Clara, Palo Alto 
This allows prospective employees to look for homes/rentals in the locations closest to areas that have a high presence of companies that hire.
