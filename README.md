# HSE-salary-prediction
HSE Salary Prediction
The Problem:

The cost of HSE job offer rejections
One of the most neglected costs in Human Resources is the 10% of job offers rejected by High Salary Expectation ("HSE") candidates.

While a few job sites have taken a shot at salary prediction, most fail to recognize better salary estimates can reduce the cost of high salary expection ("HSE") job offer rejections for employers. The hiring process holds complexity and subtle nuances which is an opportunity for continuous data science innovation. There will always be some irreducible error with human behavior, but in the same way Zillow revolutionized a baseline range for home values, the goal of this work is to predict a baseline salary range for public job postings.

This salary prediction model aims to mitigate the waste of employers interviewing candidates who expect higher salaries than offered by the position. According to Glassdoor, the average U.S. company spends about 4,000 USD to hire a new employee, and takes on average 42 days to fill an open position.

Today, most applicant screening softwares efficiently filter out applicants who do not qualify for positions, but most algorithms fall short of filtering out applicants who expect higher salaries. According to Jobvite 2017 Recruiting Funnel Benchmark Report, 17% of candidates will reject a job offer, up 6% since 2015. According to the 2017 Recruiter Sentiment Study by the MRI Network, 57% of candidates reject job offers due to compensation.

Publicly displaying salary predictions should act as a filter that discourages HSE candidates from entering into a company's hiring pipeline. An accurate salary prediction is good for both job seekers and companies because it mitigates the chances of everything falling apart at the last minute due to misaligned salary expectations.

Note, the recruitment process of high-level employees can cost multiples of the average...

Cost of HSE Candidates include:

Cost of advertising the job posting (paid clicks from applicants expecting a higher salary)
Cost of time spent reviewing applications and interviewing "higher salary expectation" candidates.
Lost productivity (job seekers/employers time wasted if salary expectations don't match)
Cost of HSE Candidates = (Advertising + Application Review + Interviews + Lost Productivity) x (# Job Offers x HSE Rejection Rate)

Cost per HSE Candidate = 600 + 600 + 2,000 + 800 = 4,000 USD

# of HSE Candidates per 1k Job Offers = 1,000 x (0.17 * 0.57) = 97 HSE Candidates

Cost of HSE Candidates per 1k Job Offers = 4,000 x 97 = 388,000 USD

Salary Prediction Model Objectives:

Reduce the cost of HSE candidate job offer rejections.

To understand which job posting features contribute most to salary.

To tune a machine learning model that predicts the salary range of public job postings within 15%.

To implement a salary estimate that discourages HSE candidates from sending applications to lower salary positions.
