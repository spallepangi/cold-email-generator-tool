**Cold Email Generator for Services Companies**

This project leverages Llama 3.1, Groq, Langchain, and Streamlit to automate the process of generating personalized cold emails for business development purposes. The tool allows users to input the URL of a company’s careers page, from which it extracts job listings. It then creates tailored cold emails with links to relevant portfolios sourced from a vector database. The emails are personalized based on specific job descriptions, enabling service companies to pitch their services to potential clients more effectively.

==This automation can reduce time and effort spent on manual outreach and improve the relevance of cold emails sent to target companies.==

**Why did I do this project?**
I wanted to automate and streamline the process of business development outreach, specifically for services companies aiming to offer specialized staffing solutions. Cold emailing is a common method used in business development, and I saw an opportunity to improve its efficiency by generating personalized, data-driven emails that directly target potential client needs.

**What is the purpose/objective of this project?**
The main objective is to build a tool that automates the process of cold email generation, personalized to each job posting. This helps business development teams to reduce the time spent on manual email crafting and improves the quality and relevance of emails, leading to higher response rates from potential clients.

**What problems did I solve using this tool?**
The tool solves the problem of manual, time-consuming cold email creation for business development executives. It automates the extraction of job listings from a company's careers page, analyzes the job descriptions, and generates a personalized email pitch with portfolio links that are relevant to the job being offered. This saves time, ensures relevance, and increases the likelihood of engagement from the target company.

**What technologies did I use in this project?**
Groq for computational optimizations
Langchain for natural language processing and linking to external data like job descriptions and portfolios
Streamlit as the user interface framework
A vector database to store and retrieve relevant portfolio links based on job descriptions

**Project Workflow**
**Input URL:** 
The user provides the URL of a company’s careers page.

**Job Listings Extraction:**
The tool uses Langchain and web scraping techniques to extract job postings from the provided URL.
The job details are processed and stored temporarily.

**Portfolio Matching:**
The tool searches a vector database for relevant portfolio links based on job descriptions.
These portfolio links are carefully selected to match the specific skills and requirements listed in the job posting.

**Cold Email Generation:**
Using the job details and matched portfolios, the tool generates a personalized cold email.
The email includes a custom pitch tailored to the job description and includes relevant portfolio links.

**Email Preview & Edit:**
The user is shown a preview of the generated email and can make any necessary edits before sending.

**Email Delivery (optional):**
Depending on the implementation, the email can either be copied for manual sending, or directly sent using an integrated email API.
 
